# Ohjelmistotekniikan menetelmät, kevät 2018

Kurssilla tutustutaan ohjelmistokehityksen periaatteisiin sekä menetelmiin ja sovelletaan niitä toteuttamalla pieni harjoitustyö.

Kurssin kolmella ensimmäisellä viikolla on muutama ohjauksessa tai omatoimisesti tehtävä harjoitustehtävä. Kurssin pääpainon muodostaa viikolla 2 aloitettava, itsenäisesti tehtävä harjoitustyö. Työtä on tarkoitus edistää pala palalta viikoittaisten tavoitteiden ohjaamana. 

Kurssin arvostelu perustuu pääasiassa harjoitustyöstä saataviin pisteisiin. Osa pisteistä kertyy viikoittaisten välitavoitteiden kautta, osa taas perustuu työn lopulliseen palautukseen.

Kurssilla ei ole koetta. Harjoitustyö tulee tehdä kurssin aikataulujen puitteissa. Kesken jäänyttä harjoitustyötä ei voi jatkaa seuraavalla kurssilla (keväällä 2019), joten muista varata riittävästi aikaa (10-15h viikossa) koko periodin ajaksi.

Tarkemmat arvosteluperusteet sivun lopussa.

## Ajankohtaista

- Ennakkotiedoista poiketen kurssilla on vain yksi luento, ma 12.3. klo 12-14 A111
- Kurssilla on tarjolla runsaasti ohjausta salissa B221/BK107, ohjausajat selviävät myöhemmin
- Kurssilla on [Telegram](https://telegram.org/)-kanava 
<https://t.me/joinchat/EHqi4kgLX_5HIivn4MgjnA>
  - [Telegram](https://telegram.org/) on whatsappin/messengerin tyylinen ilmainen keskustelufoorumisovellus jota on mahollista käyttää selaimella, mobiililaitteilla ja windows/linux/osx-clienteillä
  -  **Huom:** kaikki epäasialliset, halventavat ja jotain ihmisryhmää syrjivät kommentit kanavalla ovat kiellettyjä ja tälläisten kommenttien esittäjät poistetaan kanavalta

## Linkkejä

- [kurssimateriaali](https://github.com/mluukkai/otm-2018/blob/master/web/materiaali.md)
- [OtmTodoApp](https://github.com/mluukkai/OtmTodoApp)
- [labtool](https://tktl-labtool.herokuapp.com/)
- ohjeita (**ohjeet eivät ole vielä ajantasalla!**)
  - [aiheideoita ja oheita työn harjoitustyön aloittamiseen](https://github.com/mluukkai/otm-2018/blob/master/web/aiheideoita.md)
  - [JUnit-ohje](https://github.com/mluukkai/otm-2018/blob/master/web/junit.md) 
  - [maven](https://github.com/mluukkai/otm-2018/blob/master/web/maven.md)
  - [checkstyle](https://github.com/mluukkai/otm-2018/blob/master/web/checkstyle.md)  
  - [javadoc](https://github.com/mluukkai/otm-2018/blob/master/web/javadoc.md)
- työkaluja kaavioiden piirtoon
  - <http://yuml.me/> luokkakaaviot
  - <https://www.websequencediagrams.com/> sekvenssikaavioihin
  - <https://draw.io/> kaikki kaaviot

## Aikataulu 

**aikataulu on vielä keskeneräinen!**

### viikko 1

- Maanantaina 12.3. klo 12-14 kurssin ainoa luento A111
- Komentorivi- ja Git-harjoittelu (2p)
  - Pajassa tehtävät tai omatoimiseset [tehtävät](https://github.com/mluukkai/otm-2018/blob/master/tehtavat/viikko1.md)
- Tehtävien palautus tapahtuu tekemällä repositorio githubiin ja rekisteröitymällä labtooliin

- Palautuksen deadline ma 19.3. klo 23:59

### viikko 2

- Oman aiheen alustava määrittelydokumentti (1p)
- JUnit-harjoittelu (2p)
  - Pajassa tehtävät tai omatoimiseset [tehtävät](https://github.com/mluukkai/otm-2018/blob/master/tehtavat/viikko2.md)
- oman projektin koodaus alkaa

- Palautuksen deadline ma 26.3. klo 23:59

### viikko 3

- Koodin runko valmiina (2p)
 - Edellytys pisteille ajettavissa oleva versio, joka toteuttaa ainakin osan jostain toiminnallisuudesta
- [Tehtävät](https://github.com/mluukkai/otm-2018/blob/master/tehtavat/viikko2.md) Luokka- ja sekvenssikaaviosta (1p)

- Palautuksen deadline ma 9.4. klo 23:59

### viikko 4

- Ohjelman perustoiminnallisuus (1p)
  - Lisää koodia edellisestä viikosta 
- Testien aloitus (1p)
- Alustava rakenne luokkakaavona (1p)

- Palautuksen deadline ma 16.4. klo 23:59

### viikko 5

- Release 1 (1p)
  - releasessa oleva suoritettava jar
  - Koodi kasvanut edellisestä viikosta
- Testejä lisää (1p)
  - Testikattavuusraportti
- Jotain päätoiminnallisuutta kuvaava sekvenssikaavio (1p)
- Koodikatselmointi

- Palautuksen deadline ma 23.4. klo 23:59

### viikko 6

- Release 2 (1p)
  - releasessa oleva suoritettava jar
  - Koodi kasvanut edellisestä viikosta
- Testejä lisää (1p)
  - testikattavuusraportti
- Alustava versio arkkitehtuuridokumentista (1p)

- Palautuksen deadline ma 30.4. klo 23:59

### viikko 7

- Demot

- Lopullisen palautuksen deadline pe 11.5. klo 23:59

## Kurssin suorittaminen ja arvostelu

Kurssilla jaossa 60 pistettä. Pisteet jakautuvat alustavan suunnitelman mukaan seuraavasti

- Viikkodeadlinet 17p
- Koodikatselmointi 3p
- Dokumentaatio	9p   
  - Määrittely		
  - Arkkitehtuuri		
  - Käyttö/asennusohje	
  - Repositorio		
- Testaus	8p	
  - Testit			
  - Testidokumentti	
- Lopullinen ohjelma 23p
  - Featuret		
  - Koodin laatu 		
  - Javadoc	

Arvosanaan 1 riittää 30 pistettä, arvosanaan 5 tarvitaan noin 55 pistettä.

Läpipääsyyn vaatimuksena on lisäksi vähintään 10 pistettä lopullisesta ohjelmasta.
