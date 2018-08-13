# Artin Hackers rozcestník

ARTIN Hackers není kroužek, není to ani příležitost zabít volnej čas pařením her. ARTIN Hackers je cesta. Cesta k tomu stát se fakt dobrým IT týpkem, kterej opravdu rozumí počítačům a programům, nejde po povrchu, ví, co se děje uvnitř a hledá další možnosti, jak z toho všeho dostat ještě víc!
Být ARTIN Hackerem není jednoduchý, ale nemusí to být ani zas tak těžký. Nejdůležitější je jediná věc - musíš opravdu chtít a vědět, že za každým chováním počítače, ať už chtěným nebo nechtěným, je schovaný nějaký jeho řádek kódu. Magie v tomhle světě neexistuje.
Bude to tvrdý, ale když to zvládneš, bude to stát za to.

Parametry:
* Kdy: každý pondělí 16-18 (Začínáme 13.8.2018)
* Kde: ARTIN, Mojmírovo nám. 11, Brno
* Základní princip: Chceme ty, kteří chtějí opravdu programovat a jde jim to. Když už nemůžeš, pomůžeme, když neumíš, naučíme, když nechceš, nepotřebujeme. Když to fakt nepůjde, nebudeme to hrotit, prostě půjdeš jinam a zkusíš něco jinýho - svět nění jen o programování.
* Lektoři: Zdeněk Němec, Ondra Budai, Tom Ondráček, Tom Masník, Ron Luc
* Cena: Zdarma – nechceme po Tobě peníze, chceme abys měl opravdovej zájem a nějaké ty schopnosti
* Počítač: jestli máš vlastní notebook, vezmi si jej s sebou, jestli nemáš, půjčíme

## Cesta Hackera - miniprojekty a levely
ARTIN Hackers je cesta, dokonce hned několik cest, které vedou do různých oblastí, se kterými se můžeš seznámit. V každé oblasti jsou miniprojekty a po jejich splnění a odevzdání získáš Cestu Hackera pro tuto oblast. Ten, kdo získá všechny, se dostane na nejvyšší Level. A dál ... dál už to bude jen na něm ... může to všechno nechat být ... nebo jít a změnit svět.

Cesta Hackera - jednotlivé cesty:
* Minecraft vývoj
* Robotika
* Algoritmy
* 3D Tisk
* Počítač a operační systém
* Mobilní vývoj
* Šifrování
* Umělá inteligence
* Vlastní projekt

## Nástroje
* [Git](https://github.com/artin-hackers/artin-hackers/blob/master/git.md)

## [Minecraft vývoj](https://github.com/artin-hackers/minecraft)

### Miniprojekty

* tvorba moba
  * tvorba pluginu
  * reakce na příkaz
  * vytvoření moba 

* stavění budovy 
  * postavení řady cihel (for cyklus)
  * postavení zdi (dva for cykly, případně jeden s další pomocnou proměnnou, jak to vymyslel Kuba N. :))
  * postavení zdi o 90° otočené (funkce)
  * postavení ohrady (využití funkcí)
  * okna, dveře
  * střecha

* zbraň, která šlehá firebally
  * vlastní zbraň (tvorba itemu, úprava metadat)
  * reakce na klik (reakce na události)
  * seslání fireballu (událost seslání fireballu)

* statistiky [T]
  * počítání smrtí (reakce na událost smrti, použití proměnné)
  * počítání smrtí per player (práce s mapou)
  * počítání dalších událostí per player (vlastní objekt počítadla)

* aréna pro hru po síti [T]
  * spojení přes IP adresu (jak zjistit IP adresu)
  * tvorba arény v creative modu
  * vlastní pravidla, příkazy atd.
  
* mob - robot - vytvoř moba, který bude plnit příkazy



## Robotika
### LEGO EV3 (https://www.robotworld.cz/downloads/manual-lego-mindstorms-ev3-cs.pdf) 
* Postav jeden ze standardních projektů EV3 (vyber si), zprovozni vývojové prostředí Lego Mindstorms EV3 a nahrej standardní program do robota
* Vytvoř program, který bude simulovat hrací kostku – stiskem tlačítka / dotykového senzoru provede další hod, hody zobrazí na displeji graficky (jako na kostce) ne číslicí
* Udělej program, který bude mluvit. Na displeji bude mít oči a ústa a bude přehrávat některé připravené tebou namluvené věty, mezi nimi náhodná mezera 2-6 sekund. Při mluvení bude „hýbat pusou“ na displeji.
* Udělej program, který přehraje nějakou krátkou známou melodii (využij tónový generátor EV3, nikoli nahraný mp3 zvuk) a přitom bude blikat světýlky na kostce (barevná hudba)
* Udělej pojízdného robota a projeď s ním pevně definovanou trasu (trasa bude stanovena ohraničením, nebude možné je však detekovat senzory)
* Udělej pojízdného robota a nauč ho sledovat čáru (linefollower) s využitím dostupných senzorů (doporučený je color detection sensor)
* Udělej pojízdného robota a nauč ho jet podél zdi / mantinelu s využitím dostupných senzorů (doporučený je IR proximity sensor)
* Udělej pojízdného robota, který bude jezdit po místnosti a bude se vyhýbat překážkám (podobně jako to dělá robotický vysavač) – doporučený je IR senzor a dotykové senzory
* Udělej pojízdného (nebo něco jiného vykonávajícího) robota a ovládej ho na dálku telefonem
* Udělej pojízdného robota, který si zapamatuje trasu, kterou projede s dálkovým ovládáním pomocí telefonu, a poté ji přesně zopakuje.
* Udělej robota a zúčastni se s ním některé ze soutěží (Robotiáda, Robotic day, …)

Poznámky: u pojízdných robotů nezapomeňte na STOP tlačítko

## Algoritmy
TODO Tom O. - bude upřesněno
* Proveď sloučení dvou seřazených polí o délce n tak, aby výsledkem bylo seřazené pole o délce 2n
* Seřaď pole čísel bez využití hotových řadicích metod
* Vypiš listy stromu
* Vytvoř třídy implementující frontu a zásobník
* Vytvoř třídu implementující hash tabulku
* Napiš program, který bude realizovat kvíz tj. bude dávat posluchači otázky se seznamu a vyžadovat správnou odpověď. Vyberte vhodné datové typy pro reprezentaci kvízových otázek
* Práce se soubory
* Thready

  
## 3D Tisk
* Seznam se se zdrojem modelů https://www.thingiverse.com/ - najdi model matky a šroubu
* Nauč se nakalibrovat a nastavit tiskárnu, projdi si menu tiskárny
* Seznam se s nástroji na slicing (Slic3R) - zkus nastavit výšku vrstvy, teplotu a vytisknout předmět z předchozího úkolu s 2ma různými infily
* Seznam se s modelovacími nástroji - vytvoř model židle nebo hrnku (zmenšený) a vytiskni - po dohodě možno domluvit i jiný model
* Zkus vytisknout některý z předchozích modelů ve 3 různých materiálech (PLA / ABS / PET)
* Vyzkoušej si přesný tisk s kalibrací - vytiskni dvě kostičky https://www.thingiverse.com/thing:377523 a pokus se přenastavit Slic3r tak, aby do sebe hezky přesně zapadly


## Počítač a OS
* HW
    * Jak vypadá vnitřek počítače, k čemu co slouží (von Neuman), periferie
    * Rozebereme stolní počítač, nebo notebook
    * Základní deska, procesor, paměť, grafická/zvuková/síťová karta, zdroj, pevný disk, mechanika (?), chlazení
    * Myš, klávecnice, monitor, reproduktory
    * Navrhneme a postavíme si počítač (výběr a srovnání komponent, kompatibilita, montáž)
* OS MS Windows
    * Historie, princip a účel
    * BFU: Průzkumník a file-manager (TC), Office programy, přehrávač, herní klient nebo ne (Steam, GOG, Battle.net, ...)
    * Správce: ovladače, install/uninstall, správa uživatelů, oprávnění, čištění (defragmentace, smazání nepotřebných souborů)
    * Vývojář: textové editory, kompilátory, vývojová prostředí, build
* Windows server (?)
* OS Unix/Linux
    * Historie, princip a účel
    * Command line nástroje: uživatel i správce
    * Grafické rozhraní
* MacOS (?)
* Síťě
    * Server vs. terminál/PC
    * Router, switch, repeater
    * Wire vs. wireless
    * Konfigurace, WireShark
    * Programy (chat)
    * Sockety
* Web
    * Jak se dostat na internet (ping, ipconfig/ifconfig, DNS)
    * Prohlížeče (srovnání, možnosti, performance/benchmark)
    * Služby (jak efektivně vyhledávat, bezpečnost a soukromí na internetu, analýza e-mailů, komunikační nástroje)


## Šifrování
TODO Zdenek, pokud bude zájem


## Vlastní projekt
Vymysli a realizuj svůj vlastní cool projekt, dohodni se s někým z lektorů, co to bude a jak to uděláš. Zúčastni se s ním nějaké soutěže nebo ho uplatni přímo v praxi. Fantazii se meze nekladou.

### Poznámky a zkušenosti
* aplikace s kurzy pro programování na mobilu MIMO https://getmimo.com/


