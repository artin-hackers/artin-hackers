# Návod na Git

## Přehled

K čemu mi to vlastně je?
* Kód mám dostupný odkudkoliv, kde je připojení k internetu
* Mám k dispozici i starší verze svého kódu
* Mohu se inspirovat u ostatních, nebo jim pomoci

Jak si stáhnu a nastavím Git příkazovou řádku?
1. Prvně si stáhnu instalátor z [Git SCM](https://git-scm.com/)
2. Stažený soubor spustím a projdu instalací - Nechám všechna nastavení jak jsou a jen klikám na "Next" a na konci na "Install"
3. Spustím "Git Bash"

Jak si stáhnu a nastavím projekt Minecraft
1. Spustím "Git Bash"
2. Pomocí "cd" se přepnu do adresáře, kde chci mít repozitář
3. Naklonuji si repozitář `git clone https://github.com/artin-hackers/minecraft.git`
4. Přepnu se do nově vytvořené složky `cd minecraft`
5. Vytvořím si svou vlastní větev (s vlastním jménem) `git checkout -b zdenek`
6. Upravím soubor README.md (napíšu své jméno do souboru)
7. Vyzkoušíme, že git zaregistroval změny `git status`
8. Přidám změny do stage `git add -A`
9. Připravím commit `git commit -m "Muj první commit"`
10. Odešlu data na server `git push -u origin zdenek`

## Ovládání

Většina příkazů je jako na Linuxu:
* `cat` - Výpis obsahu souboru
* `cd` - Změna adresáře
* `ls` - Výpis obsahu adresáře

Po počátečním nastavení stačí používat:
* `git pull` - Stažení nejnovější verze
* `git add -A` - Přidání změn do stage
* `git commit -m "Zprava"` - Vytvoření commitu
* `git push` - Odeslání dat na server
