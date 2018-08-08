# Artin Hackers rozcestník

ARTIN Hackers není kroužek, není to ani příležitost zabít volnej čas pařením her. ARTIN Hackers je cesta. Cesta k tomu stát se fakt dobrým IT týpkem, kterej opravdu rozumí počítačům a programům, nejde po povrchu, ví, co se děje uvnitř a hledá další možnosti, jak z toho všeho dostat ještě víc!
Být ARTIN Hackerem není jednoduchý, ale nemusí to být ani zas tak těžký. Nejdůležitější je jediná věc - musíš opravdu chtít a vědět, že za každým chováním počítače, ať už chtěným nebo nechtěným, je schovaný nějaký jeho řádek kódu. Magie v tomhle světě neexistuje.
Bude to tvrdý, ale když to zvládneš, bude to stát za to.

Parametry:
Kdy: každý pondělí 16-18 (Začínáme 13.8.2018)
Kde: ARTIN, Mojmírovo nám. 11, Brno
Základní princip: Chceme ty, kteří chtějí opravdu programovat a jde jim to. Když už nemůžeš, pomůžeme, když neumíš, naučíme, když nechceš, nepotřebujeme. Když to fakt nepůjde, nebudeme to hrotit, prostě půjdeš jinam a zkusíš něco jinýho - svět nění jen o programování.
Lektoři: Zdeněk Němec, Ondra Budai, Tom Ondráček, Tom Masník, Ron Luc
Cena: Zdarma – nechceme po Tobě peníze, chceme abys měl opravdovej zájem a nějaké ty schopnosti
Počítač: jestli máš vlastní notebook, vezmi si jej s sebou, jestli nemáš, půjčíme

## Miniprojekty a levely
Co kdybychom udělali nějaký odborný postup - něco jako jsou barvy pásků v karate? Mohli bychom mít sadu miniprojektů (10-20) a účastníci by je mohli průběžně plnit a odevzdávat. Za splnění určitého počtu by byl další level (barva) a mohli by třeba mít tričko dané barvy s logem ARTIN hackers? To, kdy a v jakém pořadí miniprojekty budou řešit by bylo na nich. A nejvyšší level by byl splnění všech miniprojektů + dotažení nějakého vlastního většího projektu do konce.
Miniprojekty si představuju od nejjednodušších až po složitější - něco od všeho, hodně základy a abstraktní datové typy, obj. programování, dál třeba i něco z Minecraftu, 3D tisku, ... 

Cesta Hackera - jednotlivé cesty:
* Minecraft vývoj
* Robotika
* Algoritmy
* 3D Tisk
    * Vytvoř a vytiskni něco definovaného na 3D tiskárně
* Počítač a operační systém
* Mobilní vývoj
* Šifrování
* Umělá inteligence
* Vlastní projekt


 


## Minecraft vývoj

### Miniprojekty

Zatím sepsány projekty vyzkoušené v Lužánkách.
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

* statistiky
  * počítání smrtí (reakce na událost smrti, použití proměnné)
  * počítání smrtí per player (práce s mapou)
  * počítání dalších událostí per player (vlastní objekt počítadla)

* aréna pro hru po síti
  * spojení přes IP adresu (jak zjistit IP adresu)
  * tvorba arény v creative modu
  * vlastní pravidla, příkazy atd.

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

### ARDUINO
(TODO T.O.)

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
TODO Zdeněk

## Vlastní projekt
TODO Hacker

### Poznámky a zkušenosti
* první hodina musí být záživná. A pokračování pak ideálně taky. My jsme začali tvorbou zombie, což bylo dost zajímavé. Jen jsme předtím hrozně dlouho rozcházeli projekt, což až tak super nebylo. Minimálně to rozchození projektu už budeme umět líp.
* stavba budovy bavila jen někoho, zbraně bavily všechny, hra po síti taky (překvapivě...)
* Microsoft vytvořil [MakeCode for Minecraft](https://minecraft.makecode.com/), což bychom možná mohli aspoň prozkoumat
* co využít Kotlin místo Javy? Je tam míň závorek a kód je jednodušší, zároveň se dá použít cokoli z Javy. Nevýhody jsou, že to neumíme úplně na 100% a nedají se použít všechny návyky z Javy, co by kluci už mohli mít.
* aplikace s kurzy pro programování na mobilu MIMO https://getmimo.com/


