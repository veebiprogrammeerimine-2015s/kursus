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

### 9 tund
1. 5.tunni sisselogimise paigutamine eraldi klassi.
1. Piltide üleslaadimine [PHP 5 File Upload](http://www.w3schools.com/php/php_file_upload.asp) näitel.

### 10 tund
1. Tabelite sidumine. Tegime uued tabelid kasutajate huvialade jaoks (oluline, et oleks olemas varasem tabel user_sample) ja uue klassi kasutaja huvialade haldamiseks.
```PLSQL
CREATE TABLE IF NOT EXISTS `interests` (
  `id` int(11) NOT NULL,
  `name` varchar(255) NOT NULL
)

CREATE TABLE IF NOT EXISTS `user_interests` (
  `id` int(11) NOT NULL,
  `user_id` int(11) NOT NULL,
  `interests_id` int(11) NOT NULL,
  FOREIGN KEY (user_id) REFERENCES user_sample(id),
  FOREIGN KEY (interests_id) REFERENCES interests(id)
)
```

### 11 tund
1. Rühmatöö nõuete tutvustamine [php-ruhmatoo-projekt](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt)
1. Git koostöös koodi kirjutamisel [Become a git guru](https://www.atlassian.com/git/tutorials/)

## 12 tund
1. Bootstrap raamistiku tutvustamine [getbootstrap.com](http://getbootstrap.com)
1. Bootstrap studio [Bootstrap Studio](https://bootstrapstudio.io)

# Rühmatöö projektid

[#1](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/1) **[Noorte tööbörs](https://github.com/Raunts26/php-ruhmatoo-projekt)** liikmed: [@Raunts26](https://github.com/Raunts26)  
[#2](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/2) **[JOOKS24](https://github.com/karlmarkuswahlberg/php-ruhmatoo-projekt)** liikmed: [@karlmarkuswahlberg](https://github.com/karlmarkuswahlberg), [@katariinal](https://github.com/katariinal)  
[#3](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/3) **[Multirootor](https://github.com/Jaanmk/php-ruhmatoo-projekt)** liikmed: [@jissepo](https://github.com/jissepo), [@Jaanmk](https://github.com/Jaanmk)  
[#4](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/4) **[Mikid](https://github.com/p6hjanaba/php-ruhmatoo-projekt)** liikmed: [@p6hjanaba](https://github.com/p6hjanaba), [@oleloigu](https://github.com/oleloigu), [@aantsman](https://github.com/aantsman)  
[#5](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/5) **[TelliMindTööandja](https://github.com/naaber/php-ruhmatoo-projekt)** liikmed: [@naaber](https://github.com/naaber), [@merit26](https://github.com/merit26)  
[#6](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/6) **[PollNet](https://github.com/stenverkoop/php-ruhmatoo-projekt)** liikmed: [@rasmusreichardt](https://github.com/rasmusreichardt), [@stenverkoop](https://github.com/stenverkoop), [@Brandiit](https://github.com/Brandiit)  
[#7](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/7) **[Rate my professor](https://github.com/raikolepik/php-ruhmatoo-projekt)** liikmed: [@raikolepik](https://github.com/raikolepik), [@evilyeti89](https://github.com/evilyeti89), [@Raunts26](https://github.com/Raunts26)  
[#8](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/8) **[Loomakliinik](https://github.com/jormkop/php-ruhmatoo-projekt)** liikmed: [@helenpuhu](https://github.com/helenpuhu), [@aivarus](https://github.com/aivarus), [@jormkop](https://github.com/jormkop)  
[#9](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/9) **[Videolaenutus](https://github.com/Dralun/php-ruhmatoo-projekt)** liikmed: [@Dralun](https://github.com/Dralun), [@tom07140](https://github.com/tom07140)  
[#10](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/10) **[Foorum](https://github.com/MartinViidik/php-ruhmatoo-projekt)** liikmed: [@MartinViidik](https://github.com/MartinViidik), [@jalalaba](https://github.com/jalalaba)  
[#11](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/11) **[FOOTBALL FORUM](https://github.com/raoulkirsima/php-ruhmatoo-projekt)** liikmed: [@arkawa7](https://github.com/arkawa7), [@raoulkirsima](https://github.com/raoulkirsima), [@mikkmae](https://github.com/mikkmae)  
[#12](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/12) **[Phottle](https://github.com/ReioRaudheiding/php-ruhmatoo-projekt)** liikmed: [@matthias96](https://github.com/matthias96), [@ReioRaudheiding](https://github.com/ReioRaudheiding)  
[#13](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/13) **[Projekt Eesti Post](https://github.com/earist/php-ruhmatoo-projekt)** liikmed: [@janekos](https://github.com/janekos), [@RuziGg](https://github.com/RuziGg), [@earist](https://github.com/earist)  
[#14](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/14) **[ListIt](https://github.com/hendrikseemen/php-ruhmatoo-projekt)** liikmed: [@hendrikseemen](https://github.com/hendrikseemen), [@kar1ns](https://github.com/kar1ns)  
[#15](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/15) **[Üli-Kool](https://github.com/Ken299/php-ruhmatoo-projekt)** liikmed:[@Ken299](https://github.com/Ken299), [@JSiil](https://github.com/JSiil), [@KaarelTurkson](https://github.com/KaarelTurkson)  
[#16](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/16) **[Discgolf](https://github.com/Koidu/php-ruhmatoo-projekt)** liikmed: [@jarmhab](https://github.com/jarmhab/), [@sizenn](https://github.com/sizenn/), [@Koidu](https://github.com/Koidu)  
[#17](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/17) **[Arstiaja broneerimine](https://github.com/rimo9/php-ruhmatoo-projekt)** liikmed: [@rimo9](https://github.com/rimo9), [@lutsandre](https://github.com/lutsandre), [@ardobirk](https://github.com/ardobirk)  
[#18](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/18) **[Estonian muscle](https://github.com/kertkulp/php-ruhmatoo-projekt)** liikmed: [@kertkulp](https://github.com/kertkulp) ,[@janilv](https://github.com/janilv), [@ArthurDavid](https://github.com/ArthurDavid)  
[#19](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/19) **[TECHMASTER](https://github.com/Max1mov/php-ruhmatoo-projekt)** liikmed: [@Max1mov](https://github.com/Max1mov), [@katariin](https://github.com/katariin), [@kuznetsovatatjana](https://github.com/kuznetsovatatjana)  
[#20](https://github.com/veebiprogrammeerimine-2015s/php-ruhmatoo-projekt/pull/20) **[?](https://github.com/kkkaur/php-ruhmatoo-projekt)** liikmed: [@kkkaur](https://github.com/kkkaur), [@koitkorela](https://github.com/koitkorela), [@TaunoLainevool](https://github.com/TaunoLainevool)  

## Litsents
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Käesolev <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">leht</span> ja kõik teised https://github.com/veebiprogrammeerimine-2015s materjalid on <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Litsensiga</a>.
