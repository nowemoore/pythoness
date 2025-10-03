# Na hodinu

## ⭐ Úloha 01
Vytvor class `Ball` s funkciou `hop_height`, ktorá prijíma argument `h` pre výšku, z ktorej je lopta pustená, a vráti výšku k-tého skoku, ktorá sa znižuje exponenciálne.

## ⭐ Úloha 02
Vytvor class `Dice` s atribútom pre počet strán (predvolene 6). Pridaj metódu `roll`, ktorá vráti náhodné číslo medzi 1 a počtom strán. Vytvor dve kocky a simuluj 100 hodov, pričom sleduj zaujímavé statistiky, ako napríklad ktorá kocka hodila v priemere viac, rozdelenie hodených čísel celkovo atď. (Buď kreatívna!)

## ⭐ Úloha 03
Vytvor hru "hádaj číslo", kde počítač vyberie náhodné číslo medzi 1 a 100. Hráčka má 7 pokusov. Po každom hádaní jej povedz, či je "veľmi ďaleko" (20+ preč), "ďaleko" (10-19 preč), "blízko" (5-9 preč), alebo "veľmi blízko" (1-4 preč). Použi while cykly a break/continue vhodne. (Tip: Použi Python [input()](https://www.w3schools.com/python/python_user_input.asp) na zber vstupu od hráčov.)

## ⭐ Úloha 04
Vytvor class `Student` s parametrami `name`, `age` a `hours_studied`. Každý študent vo veku 10-15 rokov by získal 50% na teste, ak by sa vôbec neučil, a jeho známka by sa zvýšila o 7% za každú hodinu štúdia. Každý študent vo veku 15-18 rokov by získal 65% na tom istom teste, ak by sa vôbec neučil, ale jeho známka by sa zvýšila len o 5% za každú hodinu štúdia. Vytvor funkciu, ktorá prijme zoznam študentov a vráti percentuálny priemer známok týchto študentov. Ukáž, že tvoja funkcia funguje na testoch.

## ⭐ Úloha 05
Vytvor class `Child`, ktorá môže hodiť loptu a prijať loptu. Class by mala mať boolean atribút `tired`, ktorý vráti `True`, ak objekt tejto triedy prijal a hodil loptu aspoň päťkrát. Dieťa môže hodiť loptu len ak nie je unavené. Ukáž, že tri objekty typu `Child` môžu podávať loptu bez toho, aby sa lopta zasekla.

## ⭐ Úloha 06
Vytvor class `Tournament` pre Kameň-Papier-Nožnice, ktorý zapíše 6 hráčov s rôznymi stratégiami (napr. vždy hrá papier, vždy hrá kameň, hrá náhodné ťahy atď.; buď kreatívna!). Implementuj turnaj, kde každý hráč odohrá 20 hier proti každému inému hráčovi. Ukáž zaujímavé štatistiky.

## ⭐ Úloha 07
Navrhni class `ParkingLot`, ktorá má špecifikovaný počet objektov `ParkingSlot`. Simuluj 10 áut vchádzajúcich a vychádzajúcich z tohto parkoviska v čase, pričom každé auto zostane náhodne vygenerovaný počet minút (v rozumnom rozmedzí). Každá hodina (0-1, 1-2, 2-3 atď.) je účtovaná inou sadzbou. Ukáž, že tvoja class funguje na testoch. (Nápoveda: zváž, aká dátová štruktúra by bola vhodná na uchovávanie a sledovanie všetkých parkovacích miest.)

## ⭐ Úloha 08
Vytvor class `Elevator` pre 20-poschodovú budovu. Sleduj aktuálne poschodie, smer a frontu požadovaných poschodí (t.j. odkiaľ ľudia zavolali výťah). Implementuj algoritmus na efektívne vybavovanie požiadaviek (zvaž pohyb v jednom smere pred zmenením smeru). Ukáž, že tvoj algoritmus funguje podľa zámeru pomocou testov.

## ⭐ Úloha 09
Vytvor class `Auction` pre tichú dražbu. Objekty `Bidder` môžu podávať ponuky na objekty `Item`. Každá položka má štartovaciu cenu a minimálny prírastok. Implementuj automatické prihadovanie, kde dražitelia majú maximálne rozpočty a automaticky prihadzujú až do svojho limitu. Simuluj dražbu s 5 položkami a

## ⭐ Úloha 10
Vytvor class `Supermarket` s určeným počtom pokladničných pásov. Vytvor class `Customer` s náhodne vygenerovaným počtom položiek (1-30), kde každá položka trvá 2 sekundy na skenovanie. Implementuj systém radov, kde sú zákazníci pridelení do najkratšej fronty. Simuluj 100 zákazníkov pri pokladni a porovnaj priemerné čakacie časy pre rôzne počty pásov.