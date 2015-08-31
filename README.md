# Veebiprogrammeerimine sügis 2015

* **Kursuseprogramm:** [IFI6076](https://www.tlu.ee/et/informaatika/oppetoo/Kursuseprogrammid)
* **Õpetaja:** Romil Rõbtšenkov, [romilr@tlu.ee](mailto:romilr@tlu.ee)
* **Testserver:** greeny.cs.tlu.ee, [tunneli loomise juhend](http://minitorn.tlu.ee/~jaagup/kool/java/kursused/09/veebipr/naited/greenytunnel/greenytunnel.pdf)
* **Tunni näited testserververis:** ~romil/if15
* **Rühmad:** [I rühm](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=I+r%C3%BChm), [II rühm](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=II+r%C3%BChm), [III rühm](https://github.com/veebiprogrammeerimine-2015s?utf8=%E2%9C%93&query=III+r%C3%BChm)
* **Stiilijuhend:** [Coding Style Guide](http://www.php-fig.org/psr/psr-2/)
* **GIT õpetus:** [Become a git guru.](https://www.atlassian.com/git/tutorials/)
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
  git clone https://github.com/USERNAME/REPOSITORY.git
  ```
  ```
  git remote set-url origin https://USERNAME@github.com/USERNAME/REPOSITORY.git
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

### 1 Tund

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

## Litsents
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Käesolev <span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" rel="dct:type">leht</span> ja kõik teised https://github.com/veebiprogrammeerimine-2015s materjalid on <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International Litsensiga</a>.
