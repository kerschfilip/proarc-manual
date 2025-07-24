# ProArc

ProArc je open-source systém pro tvorbu popisných, technických a administrativních metadat pro digitalizované i born-digital dokumenty. Podporuje [standardy Národní digitální knihovny (NDK)](https://standardy.ndk.cz/) a produkuje data kompatibilní se systémem [Kramerius](https://github.com/ceskaexpedice/kramerius).

Systém je volně dostupný pod licencí [GNU GPLv3](https://github.com/proarc/proarc/blob/master/LICENSE.txt) a skládá se z:

- [jádra](https://github.com/proarc/proarc/) ([technická dokumentace](https://github.com/proarc/proarc/wiki)),
- [klientské aplikace](https://github.com/proarc/proarc-client/) ([technická dokumentace](https://github.com/proarc/proarc-client/wiki)).

**Poslední stabilní verze**

* [Jádro 4.2.9](https://github.com/proarc/proarc/releases/tag/v4.2.9),
* [Klient 2.3.5](https://github.com/proarc/proarc-client/releases/tag/v2.3.5).

## Podporované typy dokumentů
Systém v současnosti podporuje popis a zpracování:

- periodik,
- monografií,
- zvukových dokumentů (gramofonové desky, fonografické válečky),
- elektronických periodik a monografií,
- starých tisků, včetně konvolutů.

## Funkcionality systému
- Evidence digitalizačního workflow.
- Import skenů, konverze do JPG2000, prioritizace importu, správa zařízení.
- Generování UUID
- Popis skenů a celého dokumentu s uživatelsky volitelným nastavením obrazovek.
- Převedení katalogizačního záznamu MARC → MODS, editace metadat.
- Vyhledávání v metadatech.
- Kontrolní a validační mechanismy přímo v uživatelském rozhraní.
- Různé druhy exportů (FOXML, NDK PSP, Archivní export, BagIt), přímé importy do připojeného systému Kramerius.
- Podpora stávajících datových modelů systému Kramerius.
- Import NDK PSP nebo FOXML ze systému Kramerius.
- Možnost nahrazovat jednotlivé datastreamy (možnost výměny jednotlivých stran se zachováním UUID).
- Rozšířená komunikace s resolverem URN:NBN (možnost deaktivace, registrace následovníka dokumentu apod.).
- Tvorba nového ALTO/OCR pomocí [Projektu PERO OCR](https://pero-ocr.fit.vutbr.cz/index).
- Převod PDF dokumentů do archivního formátu PDF/A.
- Doplnění odkazu na digitalizovaný dokument do knihovního katalogu.
- Volitelná barevnost aplikace.

## Technologie

  * Open-source řešení (licence GNU GPLv3)
  * Fedora Commons repository >> Akubra
  * Java
  * PostgreSQL
  * Kakadu - použití pro vytvoření JPG2000. Pro získání instalace určené pro využití v ProArcu pro nekomerční účely je možné kontaktovat Národní knihovnu ČR [Ing. Petr Kukač, petr.kukac@nkp.cz](mailto:petr.kukac@nkp.cz)

Systémy, které navazují nebo poskytují dostupnou funkcionalitu
 - Systém Kramerius [https://github.com/ceskaexpedice/kramerius](https://github.com/ceskaexpedice/kramerius)

## Financování
Financování vývoje je průběžně hrazeno zejména díky podpoře z dotačních programů Ministerstva kultury ČR NAKI a VISK.

## Kontakt a zapojení
**Dotazy/chyby/návrhy na rozvoj/nedostatky dokumentace je možné hlásit prostřednictvím GitHub issues**: [https://github.com/proarc/proarc-client/issues](https://github.com/proarc/proarc-client/issues)  

**E-mailová skupina pro uživatele** sloužící k zasílání přehledu novinek: [https://groups.google.com/g/proarc-users/about](https://groups.google.com/g/proarc-users/about) 

Členy vývojového týmu jsou zástupci Knihovny AV ČR, Moravské zemské knihovny v Brně, Studijní a vědecké knihovny v Hradci Králové a městské knihovně v Praze

**Hlavní kontakt**: [info@proarc.cz](mailto:info@proarc.cz)

Vývoj projektu koordinuje Knihovna Akademie věd spolu s Národní knihovnou ČR a Moravskou zemskou knihovnou v Brně. 

- Ing. Martin Lhoták, Knihovna AV ČR, [lhotak@knav.cz](mailto:lhotak@knav.cz)
- Ing. Petr Kukač, Národní knihovna ČR, [petr.kukac@nkp.cz](mailto:petr.kukac@nkp.cz)
- Ing. Petr Žabička, Moravská zemská knihovna v Brně, [petr.zabicka@mzk.cz](mailto:petr.zabicka@mzk.cz)

