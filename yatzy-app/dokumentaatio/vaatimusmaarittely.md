<h1> Vaatimusmäärittely </h1>

<h2> Sovelluksen tarkoitus </h2>
Sovelluksen tehtävänä on toimia vuoropohjaisena pelinä, Yatzyna, jota pelataan yksin.

<h2> Käyttäjät </h2>
Sovelluksella on ainoastaan yksi käyttäjärooli, normaali käyttäjä eli pelaaja.
Käyttäjät voivat tallentaa oman pelaajanimensä ja käyttää niitä myös myöhemmissä peleissä.
Pelaajanimen yhteyteen tallennetaan pelin loppupistemäärät, mikäli ne ovat parempia kuin aikaisemmin ansaitut pisteet.

<h2> Käyttöliittymä </h2>
Sovelluksella on yhteensä seitsemän eri näkymää:

- Etusivu, josta voi siirtyä uuteen peliin tai katsomaan parhaita tuloksia.

- Top Score -näkymä, jossa näkyy paremmuusjärjestyksessä eri pelaajanimien parhaat tulokset.

- Pelaajanimen luonti -näkymä.

- Pelaajanimen valinta -näkymä.

- Pelitilannenäkymä, jossa näkyy nykyinen pelin tilanne ja aikaisemmin valitut pisteet.

- Nopanheiton näkymä, jossa näkyy viisi noppaa, jota heitetään joka kierroksella enintään kolme kertaa.

- Valintanäkymä, jossa valitaan, mihin nopista saadut pisteet halutaan käyttää. Pisteet tulevat näkyviin pelitilannenäkymään.

<h2> Sovelluksen toiminnallisuus </h2>

- Sovellukseen voidaan lisätä rajoittamaton määrä pelaajanimiä, jotka tallennetaan tietokantaan. Pelaajanimi ei voi olla tyhjä eikä yli 20 merkkiä. Pelaajanimeen liitetyt pisteet ovat 0 ennen yhtäkään peliä.

- Pelaaja heittää jokaisella vuorolla viittä noppaa enintään kolme kertaa. Pelaaja voi joka heiton jälkeen valita, mitä noppia ei enää heitetä.

- Pelaaja voi kolmen nopan heittokerran jälkeen valita, mihin kohtaan pistetaulukkoa haluaa pisteensä laittaa, vai haluaako valita jonkin taulukon kohdista nollaksi.

- Sovellus ehdottaa automaattisesti pistetaulukon kohtia, joihin saatuja pisteitä on mahdollista käyttää.

- Sovellus antaa lisätä yhteen pistetaulukon kohtaan vain yhdet pisteet pelin aikana ja ilmoittaa virheestä, mikäli pelaaja yrittää lisätä pisteitä uudestaan samaan pistetaulukon kohtaan.

- Sovellus laskee pistetaulukkoon automaattisesti 50 pisteen bonuksen, mikäli ykkösten, kakkosten, kolmosten, nelosten, vitosten ja kutosten yhteenlaskettu summa on yli 63 pistettä.

- Pelin päätyttyä sovellus laskee automaattisesti yhteen lopputuloksen ja ilmoittaa erikseen ponnahdusikkunalla, mikäli tulos on kyseisen pelaajanimen paras tulos.

- Pelaajanimen paras tulos tallennetaan tietokantaan ja jokaisen pelaajanimen parhaita tuloksia voi ihailla erikseen "Top Score" -näkymässä.

- Pelin päätyttyä näytetään ponnahdusikkuna, jossa ilmoitetaan lopputulos. Ikkunasta voidaan sulkea sovellus.

<h2> Ideoita jatkokehitykseen </h2>

- Peliin voi osallistua kerralla 2-4 pelaajaa. Mikäli yritetään pelata yhdellä tai ei yhdelläkään pelaajalla, tulee virheilmoitus.

- Voidaan pelata yksinpeliä tietokonetta vastaan.
