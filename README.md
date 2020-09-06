# bandikama
Tietojenkäsittelyoppi, Tietokantasovellus-harjoitustyö / 2020-P1 

Työn nimi: Bandikamojen vaihtopalvelu: versio 0.3

Bandikamojen vaihtopalvelun toiminnot: 
- Palvelua käyttämällä asiakkaat voivat tehdä ja hyväksyä bandikamojen vaihtotarjouksia. 
- Järjestelmä ylläpitää, etsii ja “matchaa” sekä lajittelee tuotteiden vaihtotarjouksia. 
- Tuotteesta kiinnostunut  henkilö voi lähettää kysymyksiä tarjoajalle erillisesti emailitse. 
- Palvelun asiakkaat voivat hyväksyä mitä tahansa vaihtotarjouksia. Onnistunut vaihtokauppa edellyttää hyväksyntää molemmilta osapuolilta toistensa   tarjouksista. Tarvittaessa asiakkaat voivat muokata tarjouksiaan kauppaan sopivammiksi. 
- Palvelussa olevia bändikamoja koskevat kysymykset ja niiden vastaukset välitetään vaihdantaosapuolten email-osoitteiden tai puhelinnumeroiden avulla   erikseen emailitse tai puhelimitse. 
Rahaa ei palvelussa liikutella, vaan sitä mahdollisesti koskevat asiat sovitaan myös erikseen palvelun ulkopuolitse esim. puhelimitse tai emailitse. 

Bandikamojen vaihtopalvelun asiakkaat:
- Webbi-käyttäjä: rekisteröitynyt tai rekisteröitymätön    

Asiakkaiden web-selaimella suorittamat toiminnot: 
- asiakkaan rekisteröityminen 

Asiakas kirjaa vaihtotarjouksen vaihdantatuoteryhmän tarjouslistalle: 

- soittimet 
- vahvistimet 
- mikit 
- säläkasa (standit, kaapelit, caset jne...)
- studiokamat

- asiakas suorittaa tarjottujen vaihdantatuoteiden tietojen syöttämisen vaihtotarjoukseen 
- määrittää vaihtotarjouksen alkamis- ja päättymisajan sekä asettaa kompensaatio- ja toimitus- yms. toiveet 
- ylläpitää vaihtotarjoustaan, mm. tilatietoja ja sovittaa tarvittaessa sen sisältöä kaupantekijäisiksi
- tarkistaa ja ylläpitää tarjouksiensa listan ja mm. yksittäisten kamatarjousten tilatiedot 
- poistaa toteutuneeseen vaihtoon liittyvät tarjouksensa 

Järjestelmän tarjoamat perustoiminnot:

- Bändikamalistojen luonti ja ylläpito.
- Avoimet tarjoukset-listan muodostaminen, lajittelu ja näyttö. 
- Järjestelmä ylläpitää, etsii ja “matchaa” sekä lajittelee bandikamojen eli tuotteiden vaihtotarjouksia. 
- Listaukset tarjoajittain tilan, tuoteryhmän, päivämäärien ja yhteensopivuuden (matching) perusteella.
- Tarjouksen tilatiedon ylläpito.
  - esim. vaihtokauppaan johtaneen tarjouksen tilan muuttaminen (toteutuneet).

Tietokannan tietokohteet:
 
Asiakastiedot: 
- Asiakastunnus 
- Nimi ja nimimerkki 
- salasana 
- Email  
- Puhelinnumero (näkyy vain rekisteröityneille) 
- Muu tarjouksiin liittyvä asiakastieto
- Tarjoajan referenssitiedot, esim. vaihdantahistoria tässä palvelussa (luotettavuuden arviointiin)
 
Vaihtotuoteryhmätiedot (vaihtokamaryhmittely): 
- Tuoteryhmäkoodi ja ryhmän nimi sekä muut otsikkotiedot
- Tuoteryhmän tilatiedot
 
Vaihtotuote (bändikama): 
- Tuotteen koodi 
- Tuotteen nimi ja tyyppitiedot, esim. vuosimalli 
- Tarkennettu kuvaus, kunnon, värin, soundin yms. 
- Vintage-tuotteen elämäntarina lyhyesti (arvokkaat tuotteet)
- Tuotteen tarjottu määrä 
- Tuotteen alkuperäinen hinta 
- Tuotteeseen liittyvät kommentit, esim. vaihdannaistoiveet 

Asiakkaan vaihtotarjous:
- Tarjouksen tunnus
- Asiakastunnus (Tarjoajan yhteystietojen hakua varten)
- Tarjouksen alkamis- ja päättymispäivä 
- Tarjouksen tilatieto 
- Tarjoustuotteiden tunnukset 
- Vaihtotoiveet: toivotut tuotteet  
- Muut tarjoukseen liittyvät tiedot, lisäkommentit, esim. toimitustavasta 

Historiatilastot: 
- Vaihdannan vuosi ja kk-tilasto tuoteryhmittäin 

Asiakkaan tarjouslistat:
- Tarjouksien tiedot asiakkaittain ja esim. tuoteryhmien ja/tai tarjousten tilatietojen perusteella ryhmiteltynä 

Perustietolistat:
- Asiakaslista nimen tai nimimerkin mukaan järjestettynä
- Tuoteryhmälista koodin mukaan järjestettynä
- Tuotelista (aktiivisessa tilassa vaihdannassa olevat bändikamat, aktiivisten tarjousten tunnukset)

