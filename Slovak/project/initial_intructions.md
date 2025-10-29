# 🧩 Ako rozmýšľať o záverečných projektoch

Vstupuješ do fázy kurzu, kde sa začneš presúvať **z "naučila som sa nejaké koncepty v Pythone" na "viem definovať problém a použiť tieto koncepty na jeho riešenie"**. Mám aj nejaké dobré správy: Takmer každý problém môže byť problémom na programovanie!

## 🤔 Čo sa ráta ako problém?
Svet je plný problémov! **"Problém" neznamená, že niečo je nutne zlé**&mdash;môže to tiež znamenať, že niečo treba zistiť alebo, že na niečo treba nájsť odpoveď. Problémy existujú vždy, keď je rozdiel medzi tým, ako veci sú, a tým, ako by si chcela, aby boli.

## 💻 Čo je programovací problém?
Problém z reálneho sveta sa stáva programovacím problémom, keď ho vieš **rozdeliť na kroky**, ktoré vie počítač vykonať (loopy, logické operácie, dátové štruktúry, funkcie, tabuľky) a použiť ich na vytvorenie riešenia (alebo čiastočného riešenia). Nezabúdaj, že pred sebou máš ešte 3 týždne obsahu, takže keď budeš rozmýšľať nad potenciálnymi problémami, neobmedzuj sa myšlienkami nad konkrétnymi riešeniami pomocou konceptov, ktoré zatiaľ poznáš!

## 🔍 Ako si vymyslím vlastný problém?
Vždy je dobré na začiatok si jednoducho všímať, čo sa deje vo svete okolo teba. Mnohé problémy okolo nás sú samozrejme príliš veľké na to, aby sme ich vedeli opísať, nieto ešte naprogramovať ich riešenie, takže moje odporúčanie je: **začni v malom**. Vyber si otázku, ktorú môžeš začať riešiť dnes, a potom ju môžeš bližšie rozpracovať neskôr.

Tu je zopár introspektívnych otázok, ktoré ti snáď pomôžu začať rozmýšľat nad tým, ktoré problémy okolo teba by si mohla vyriešiť programovaním:

1) Aké informácie si pravidelne zaznamenávaš alebo zbieraš (napr. minuté peniaze, hodiny učenia, počúvané pesničky)?
2) Keby som mohla vidieť jednu vec o svojom živote vizualizovanú ako graf, čo by to bolo?
3) Kedy si naposledy myslela "Kiež by to niekto zarátał/zotriedił/zorganizoval za mňa"?

## 💡 Problémy pre inšpiráciu
Nižšie sú príklady toho, ako môže problém vyzerať. Na (ne)šťasie, na dokončenie kurzu si budeš musieť vymyslieť vlastný problém, ale hádam sa inšpiruješ! 🙂

1) **Hra Hádaj Číslo**: Program náhodne vyberie číslo medzi 1-100. User má 7 pokusov uhádnuť ho. Po každom tipe program dáva hinty ("too high" alebo "too low"). Program trackuje zostávajúce pokusy a zobrazuje ich po každom pokuse. Ak user uhádne správne, vyhráva hru a vie si pozrieť, koľko pokusov mu to zabralo. Ak sa userovi minú pokusy, prehrá, a program odhalí číslo. Na konci sa program spýta, či chce hrať znova.

2) **Budget Cracker**: Vždy, keď chce user niečo kúpiť, tento program najprv skontroluje, či tento produkt už doma náhodou má. Ak je produkt drahší ako vopred nastavená hranica, program userovi položí sériu otázok, aby rozhodol, či by tento produkt user mal predsalen kúpiť. Ak je produkt mimo rozpočtu usera, program mu jednoducho nedovolí tento produkt kúpiť.

3) **Jednoduchý To-Do List Manager**: User môže pridávať tasky, označovať tasky ako hotové, zobraziť všetky tasky, alebo zobraziť len nedokončené tasky. Každý task má svoj čas potrebný na dokončenie a deadline. Niektoré tasky sú Priority Tasky, ktoré vždy migrujú úplne navrch to-do listu. User môže zadať počet minút, ktoré má k dispozícii v daný deň, a program prezentuje list taskov, ktoré by mal dokončiť na základe ich dĺžky a priority.

4) **Subscription Audit & Savings Calculator**: User zadá všetky predplatné (streaming, gym, appky, atď.) s mesačnou cenou a frekvenciou používania. Program vypočíta ročnú cenu, cenu za skutočné použitie, a identifikuje "zombie subscriptions" nepoužité 30+ dní. Kladie rozhodvacie otázky: "Zaplatila si €15, ale použila si to 0-krát minulý mesiac, chceš to zrušiť?" Ukáže potenciálne ročné úspory zo zrušení.

5) **Coffee Budget Tracker**: User si nastaví mesačný coffee budget (napr. €60). Vždy, keď si kúpi kávu, zadá cenu a program ju odpočíta zo zostávajúceho rozpočtu. Program trackuje koľko káv si user kúpil, vypočíta priemernú cenu za jednu kávu, a ukáže koľko dní v mesiaci zostáva. Ak user utráca svoj budget príliš rýchlo, program ho upozorní ("Týmto tempom ti dôjdu peniaze za 3 dni!"). Ak budget dôjde, program vypočíta o koľko user prečerpal a navrhne ako upraviť typ kávy a frekvenciu návštev kaviarní na nasledujúci mesiac.

