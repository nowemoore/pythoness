# Na hodinu

## ⭐ Úloha 01
Vytvor základnú triedu `Vehicle` s atribútmi `speed`, `fuel_capacity` a `fuel_consumption`. Vytvor podradené triedy `Car`, `Motorcycle` a `Truck`, ktoré dedia z `Vehicle`. Každá podradená trieda by mala mať metódu `travel_distance(hours)`, ktorá vypočíta, ako ďaleko dokáže cestovať.

## ⭐ Úloha 02
Útulok pre zvieratá eviduje zvieratá s ich vekom, váhou a adopčným poplatkom. Psy majú základný poplatok $50 plus $10 za každý rok veku. Mačky majú základný poplatok $40 plus $8 za každý rok. Vtáky majú fixný poplatok $25. Útulok práve dostal dar, ktorý pokrýva adopčné poplatky pre všetky zvieratá mladšie ako 2 roky. Vytvor systém, ktorý vypočíta, koľko peňazí z daru bude použitých, ak je momentálne v útulku 5 psov (vek: 1, 3, 5, 1, 7), 8 mačiek (vek: 2, 1, 4, 1, 6, 1, 3, 8) a 3 vtáky (vek: 1, 2, 4).

## ⭐ Úloha 03
Vytvor triedu `LaundryItem`, kde každá položka má farbu (biela, svetlá, alebo tmavá) a typ materiálu (bavlna, syntetické, alebo jemné). Biele veci sa musia prať oddelene, svetlé a tmavé sa môžu miešať, ak obe nie sú jemné. Jemné veci sa vždy perú samostatne. Vytvor funkciu, ktorá berie zoznam prádla a vráti minimálny počet potrebných pracích cyklov. Vygeneruj 30 náhodných kusov prádla pomocou `random.choice()` pre farby a materiály, potom ukáž, koľko pracích cyklov je potrebných a ktoré veci idú do ktorého cyklu.

## ⭐ Úloha 04
Vytvor základnú triedu `Shape` s abstraktnou metódou `area()`. Podtriedky `Circle`, `Rectangle` a `Triangle` musia každá implementovať svoj vlastný vzorec pre výpočet plochy. Potom napíš funkciu `total_area(shapes)`, ktorá vezme zoznam rôznych objektov tvarov a vráti celkovú plochu. Ukáž, že tvoja metóda funguje pomocou unit testov.

## ⭐ Úloha 05
Zoo má rôzne zvieratá s rôznymi harmonogramami krmenia. Mäsožravce jedia každých 8 hodín a konzumujú 5kg mäsa na krmenie. Bylinožravce jedia každých 6 hodín a konzumujú 8kg rastlín na krmenie. Všežravce jedia každých 7 hodín a konzumujú 3kg mäsa + 4kg rastlín na krmenie. Zoo má 3 levy (carnivores), 4 slony (herbivores) a 2 medvede (omnivores). Prvýkrát každý týždeň sú mäsožravce kŕmené v pondelok o 7:00, bylinožravce v pondelok o 5:00 a všežravce v pondelok o 6:30. Nakoniec, každá skupina spí osem hodín denne, v náhodných intervaloch po dve hodiny, a nemôžu byť kŕmené, keď spia. Printni presne, kedy bola každá skupina zvierat nakŕmená.

<details>
<summary>Tip</summary>
Nezabudni vypísať, kedy zviera *nebolo* nakŕmené z nejakého dôvodu (napr. kvôli spánku), aby si sa uistila, že tvoja funkcia funguje správne.
</details>

## ⭐ Úloha 06
Vytvor základnú triedu `Shape` s atribútmi pre názov a počet strán, a metódou `roll_distance()`, ktorá vezme silu použitú na odtlačenie daného tvaru a vráti, ako ďaleko sa tvar odkotúľa, keď je odtlačený. Potom vytvor podtriedky `Circle`, `Square` a `Hexagon`, kde každá definuje, ako počet strán ovplyvňuje kotúľanie, pričom vzdialenosť, ktorú každý tvar dokáže prejsť, je rovná (force * 10) / počet strán. Napíš funkciu `roll_tournament()`, ktorá vezme zoznam tvarov a jednu silu použitú na všetky tvary, zavolá metódu `roll_distance()` každého tvaru a vypíše, ktorý tvar sa odkotúľal najďalej. Ukáž, že tvoj program funguje s aspoň tromi rôznymi tvarmi.

## ⭐ Úloha 07
Každá podtrieda `Shape` (`Circle`, `Rectangle`, `Triangle`) implementuje metódu `cast_shadow`, ktorá vezme uhol svetla relatívne k povrchu, na ktorom je tvar umiestnený, a vráti dĺžku tieňa v závislosti od geometrie tvaru. Napíš funkciu, ktorá pre daný zoznam tvarov a jeden uhol svetla vráti najdlhší tieň.

## ⭐ Úloha 08
Vytvor základnú triedu `Message` s podtriedkami `TextMessage` (ktorá pozostáva zo zoznamu charakterov), `ImageMessage` (zoznam RGB trojíc) a `VoiceMessage` (zoznam float frekvencií). Každý typ musí vedieť, ako sa komprimovať. Komprimácia znamená, že ak sú dve ekvivalentné hodnoty hneď vedľa seba, správa si ponechá len jednu z nich (napr. ak textová správa pozostáva zo znakov `h`, `e`, `l`, `l` a `o`, komprimovaná textová správa bude pozostávať z `h`, `e`, `l`, `o`). Napíš funkciu, ktorá vezme zoznam zmiešaných správ a vypočíta celkové ušetrené úložisko po komprimácii.

## ⭐ Úloha 09
Vytvor základnú triedu `ElectricDevice` s metódou `consume_energy(hours, usage)`, ktorá vypočíta spotrebovanú energiu na základe toho, ako dlho zariadenie beží a koľko energie spotrebuje za hodinu. Podtriedky prvej generácie `Lights`, `HeatingDevice` alebo `ScreenDevice` definujú maximálny povolený čas prevádzky za deň pre daný typ. Podtriedky druhej generácie ako `LEDLight`, `HalogenLight`, `Heater`, `AirConditioner` a `TV` majú svoju vlastnú špecifickú spotrebu energie za hodinu a dedia limity času prevádzky od svojho rodičovského typu. Implementuj triedu `smarthome`, ktorá vezme zoznam viacerých zariadení a vypočíta, koľko bude domácnosť platiť pri rôznych denných a nočných tarifách elektriny.

## ⭐ Úloha 10
Navrhni základnú triedu `TrafficLight` s metódami na prechádzanie stavmi: 'Red', 'Yellow', 'Green'. Implementuj podtriedu `PedestrianCrossingLight`, ktorá prepíše logiku stavov; musí prepnúť z 'Green' na 'Red' len po zavolaní metódy `pedestrian_request()`. Zvaž interakciu týchto dvoch objektov: ak svieti zelená na chodcovom semafore, potom musí byť červená na dopravnom semafore a žiadne autá nemôžu prejsť. Keď svieti zelená, auto prejde cez semafor každých 5 sekúnd. Implementuj funkciu, ktorá vypočíta, koľko áut prejde počas hodinovej periódy, kde žiadosti chodcov sa vyskytujú v náhodných časoch.