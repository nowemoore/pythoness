# Pre pokročilé

## ⭐ Úloha 01
Zoo má rôzne zvieratá s rôznymi harmonogramami kŕmenia. Mäsožravce jedia každých 8 hodín a konzumujú 5kg mäsa. Bylinožravce jedia každých 6 hodín a konzumujú 8kg rastlín. Všežravce jedia každých 7 hodín a konzumujú 3kg mäsa + 4kg rastlín. Zoo má 3 levy (mäsožravce), 4 slony (bylinožravce) a 2 medvede (všežravce). Prvýkrát každý týždeň sú mäsožravce kŕmené v pondelok o 7:00, bylinožravce v pondelok o 5:00 a všežravce v pondelok o 6:30. Jeden zamestnanec môže kŕmiť len jednu skupinu zvierat naraz. Zisti, koľko zamestnancov musí zoo zamestnať na kŕmenie všetkých skupín, aby všetky zvieratá mohli jesť včas bez oneskorenia.

## ⭐ Úloha 02
Vytvor triedu `Person`, kde každá osoba má dve alely pre farbu očí (BB, bb, alebo Bb, kde B reprezentuje hnedú (dominantná farba) a b modrú (recesívna farba)). Hnedé oči sa objavia, ak je prítomná aspoň jedna B (BB alebo Bb), zatiaľ čo modré oči sa objavia len pri bb. Keď majú dve osoby dieťa, dieťa náhodne zdedí jednu alelu od každého rodiča pomocou `random.choice()`. Vytvor funkciu, ktorá vezme počet generácií a vyprodukuje pomer ľudí s modrými očami po danom počte generácií. Začni s populáciou 10 ľudí (6 s BB, 3 s Bb, 1 s bb) a ukáž, že tvoja funkcia funguje.

## ⭐ Úloha 03
Vytvor základnú triedu `Message` s podtriedami `TextMessage` (ktorá je zoznamom znakových reťazcov), `ImageMessage` (zoznam RGB trojíc) a `VoiceMessage` (zoznam float frekvencií). Každý typ musí vedieť, ako sa komprimovať. Vytvor funkciu `decompress()`, ktorá vezme správu akéhokoľvek typu a obnoví pôvodnú správu v jej pôvodnej veľkosti.

## ⭐ Úloha 04
Vytvor základnú triedu `BankAccount` s atribútmi owner a balance. Podtriedky `CheckingAccount`, `SavingsAccount` a `InvestmentAccount` musia implementovať metódy `deposit()`, `withdraw()` a `end_of_day_update()` odlišne, aplikujúc pravidlá ako poplatky za prečerpanie, úroky alebo obchodné poplatky. Implementuj triedu `Bank`, ktorá drží viacero účtov a podporuje `transfer(from_account, to_account, amount)`. Denne banka automaticky aplikuje úroky, pokrýva prečerpania z prepojených sporiaci účtov a redistribuuje investičné zisky na iné účty na základe zostatkov. Simuluj týždeň náhodných vkladov, výberov a prevodov, pričom vypíš zostatok každého účtu na konci každého dňa.