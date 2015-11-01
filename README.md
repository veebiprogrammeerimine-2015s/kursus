# Veebiprogrammeerimine sügis 2015

* **Kursuseprogramm:** [IFI6076](https://www.tlu.ee/et/informaatika/oppetoo/Kursuseprogrammid)
* **Õpetaja:** Romil Rõbtšenkov, [romilr@tlu.ee](mailto:romilr@tlu.ee)
* **Testserver:** greeny.cs.tlu.ee, [tunneli loomise juhend](http://minitorn.tlu.ee/~jaagup/kool/java/kursused/09/veebipr/naited/greenytunnel/greenytunnel.pdf)
* **Tunni näited testserververis:** ~romil/if15
* **Rühmad:** [I rühm](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=-I-ruhm), [II rühm](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=-II-ruhm), [III rühm](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=-III-ruhm)
* **Stiilijuhend:** [Coding Style Guide](http://www.php-fig.org/psr/psr-2/)
* **GIT õpetus:** [Become a git guru.](https://www.atlassian.com/git/tutorials/)
* **Abimaterjale:** [Veebirakenduste loomine PHP ja MySQLi abil](http://minitorn.tlu.ee/~jaagup/kool/java/loeng/veebipr/veebipr1.pdf), [PHP with MySQL Essential Training] (http://www.lynda.com/MySQL-tutorials/PHP-MySQL-Essential-Training/119003-2.html)
* **Vajad abi?**
    * [![Join the chat at https://gitter.im/veebiprogrammeerimine-2015s/kursus](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/veebiprogrammeerimine-2015s/kursus?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
        * Saad suhelda kaasüliõpilastega saates neile sõnumi koodijupiga, võid sõnumi kirjutada ka siis kui ühtegi aktiivset kasutajat ei ole.
    *  Loo [Issue](https://github.com/veebiprogrammeerimine-2015s/kursus/issues)
   * Kirjuta [email](mailto:romilr@tlu.ee) - 1:1 abi

## Kodused tööd ja projektid

Kõik kodused tööd on välja toodud [Kursus](#Kursus) tundide loendis.

### GitHub'i töövoog

1. *Fork*'i ülesande/projekti repositoorium (leiab [github.com/veebiprogrammeerimine-2015s](https://github.com/veebiprogrammeerimine-2015s)).
1. *Clone*'i see repositoorium enda arvutisse/serverisse ja määra repositooriumi URL kuhu edaspidi muudatusi salvestad.
  ```
  git clone https://USERNAME@github.com/USERNAME/REPOSITORY.git
  ```
1. Muuda faile ülesande lahendamiseks ja *Commit*'i iga olulisem muudatus, kasutades kahte käsku.
  ```
  git add .
  ```
  ```
  git commit -m "Added this functionality to the app"
  ```
1. Veendu, et kogu kood on *Commit*'itud.
  ```
  git status
  ```
1. *Push/sync*'i GitHub'i.
  ```
  git push origin
  ```
1. [Ava *pull request*](https://help.github.com/articles/creating-a-pull-request) ülesande originaalses repositooriumis. Ülesannete tähtajaks on järgmise tunni algus, kui pole teisiti kirjas.
1. Muudatusi ja täiendusi võib *push*'ida repositooriumisse, kuni ette antud  kuupäevani.

Tagasisidet saab otse *pull request*'i millele ootan Sinupoolseid kommentaare/mõtteid/küsimusi. Võid julgselt avada *pull request*'i kohe kui hakkad kodutöö kallal tegelama ja siis kui hätta jääd võid esitada sinna küsimuse. Maini kommentaaris minu kasutajat `@romilrobtsenkov` siis jõuan sellele kiiremini vastata.

### Nõuded

Need rakenduvad ka päris elus!

* Peab järgma "head programmeerimise stiili"
    * Muutujate nimed peavad kirjeldama muutujat ning peavad olema inglise keeles
    * Funktsiooni nimi peab olema "lühike"
    * Optimeeritud koodi lugemiseks
    * Projektide jaoks tuleb kasutada objektorienteeritud lähenemist
    * Laenatud koodile tuleb viidata
* Boonuspunktid:
    * Loomingulisus (nb! nõuded peavad olema täidetud)

## Kursus

### 1 tund

1. Sissejuhatus
    * Arutleme, mis antud kursus endas hõlmab
    * Igaüks tutvustab ennast
        * Nimi
        * Millised on Sinu huvid/hobid?
        * Mis toob Sind informaatikat õppima?
1. Ettevalmistus
    * Installi GitHub [Mac](https://mac.github.com) või [Windows](https://windows.github.com) (isiklikku arvutisse)
    * Tee endale [GitHub](https://github.com/)'i kasutaja
1. GitHub töövoog
    * Räägime läbi GitHub'i töövoo
    * Tee *pull request* repositooriumi [opilased](https://github.com/veebiprogrammeerimine-2015s/opilased)

### 2 tund

1. Alustame koodikirjutamist
    * muutujad, loogika, tsüklid, kuupäev
    * HTML vorm ja selle valideerimine
1. Abimaterjal
    * [PHP 5 Form Handling] (http://www.w3schools.com/php/php_forms.asp)
    * ...
    * [PHP 5 Form Complete] (http://www.w3schools.com/php/php_form_complete.asp)
1. Kodutöö
    * [1. kodutöö](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=1.kodutoo)

### 3 tund

1. Loome lehestiku eri faili osadest: päis, jalus
1. Täiendame kasutaja sisselogimise vormi
1. Igaüks loob endale lehestiku  

### 4 tund

1. Andmebaasi ühenduse loomine
    * [gitignore] (https://help.github.com/articles/ignoring-files/)
1. Andmebaasi andmete lisamine ja sealt andmete küsimine.
1. Kasutame näidistabelit ja igaüks rakendab tunnis õpitut oma rakenduses, kes ei jõua teeb kodus [2. kodutöö](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=2.kodutoo)
```PLSQL
CREATE TABLE user_sample (
	id INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
	email VARCHAR(255) NOT NULL,
	password VARCHAR(128),
	created TIMESTAMP DEFAULT CURRENT_TIMESTAMP,
	UNIQUE(email)
);
```

### 5 tund

1. Kasutaja sessioonis hoidmine ja välja logimine.
1. Andmebaasi andmete lisamine ja sealt andmete küsimine.
1. Lisame andmet ja näitame tabeli kujul, andmete muutmine. Kasutame eelmise tunni tabeliga seotud uut tabelit. Vajadusel abiks (SQL FOREIGN KEY Constraint)[http://www.w3schools.com/sql/sql_foreignkey.asp]
```PLSQL
CREATE TABLE car_plates (
  id INT NOT NULL AUTO_INCREMENT PRIMARY KEY,
  user_id INT NOT NULL,
  number_plate VARCHAR(200),   
  color TEXT,
  FOREIGN KEY (user_id) REFERENCES user_sample(id)
);
```

### 6 tund

1. Funktsioonid eraldi failis
1. Andmete tabeli kujul kuvamine, kustutamine (st arhiveerimine) ja muutmine
1. Eraldi fail andmebaasi ühenduse andmete hoiustamiseks
```PHP
// configglobal.php
  $servername = "localhost"; // ab
  $server_username = ""; // ab'i kasutajanimi
  $server_password = ""; // ab'i parool
```

### 7 tund

1. Andmete muutmine ja otsimine eelmise tunni näitel
1. Igaüks teeb vastavalt oma ideele koduse töö [3. kodutöö](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=3.kodutoo)

### 8 tund

1. Erinevad näited lihtsamatest PHP koodijuppidest `function`, `$_SESSION` jm
1. [3. kodutöö](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=3.kodutoo) lõpetamine ja täiendamine

## Litsents
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Käesolev <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">leht</span> ja kõik teised https://github.com/veebiprogrammeerimine-2015s materjalid on <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Litsensiga</a>.
