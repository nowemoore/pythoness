# Pre pokročilé

## ⭐ Úloha 01
Vytvor class `Projectile` s počiatočnou rýchlosťou a uhlom. Implementuj metódy `get_position(time)`, ktorá vráti tuple súradníc `x` a `y` v čase `t`. Potom implementuj metódy `get_max_height()`, `get_range()` a `time_to_ground()`. Použi fyzikálne vzorce.

## ⭐ Úloha 02
Vytvor class `Card` a `Deck`. `Card` má farbu, hodnotu karty a číselnú hodnotu. `Deck` má 52 kariet. Implementuj metódy pre Deck: `shuffle()`, `deal(n)`, `draw()`, `cards_remaining()`, `has_card()` a `sort_by_value()`. Sfunkčni jednoduchú hru: rozdaj 5 kariet 3 hráčom a urči, kto má najvyššiu celkovú hodnotu.

## ⭐ Úloha 03
Vytvor program, ktorý simuluje jednoduchý systém semaforu. Svetlo prechádza cez zelenú (30 sekúnd), žltú (5 sekúnd) a červenú (25 sekúnd). Pre daný čas v sekundách od zapnutia zelenej urči, akú farbu svetlo momentálne ukazuje. Použi if/elif/else príkazy a zvládni viacero kompletných cyklov. (Tip: Použi knižnicu [time](https://docs.python.org/3/library/time.html) na sledovanie času.)

## ⭐ Úloha 04
Vytvor class `Maze`, ktorá môže byť inicializovaná pomocou jediného celočíselného argumentu `n` a následne vygeneruje n*n grid, ktoré môžu byť buď blokované alebo voľné. Potom vytvor funkciu `find_path`, ktorá berie dve tuple súradníc x a y pre štartovací a koncový bod a vráti zoznam súradníc štvorcov, ktoré tvoria najkratšiu cestu medzi štartom a koncom. (Nápoveda: Pridaj si pomocné metódy ako `move_left`.)

## ⭐ Úloha 05
Vytvor simuláciu šírenia vírusu medzi objektami typu `Person`, ktoré môžu byť: zdravé, infikované, zotavené alebo zaočkované. Ak sa zdravý, zaočkovaný a zotavený človek stretne s infikovaným človekom, nakazí sa s pravdepodobnosťou 70%, 20% a 10%. V populácii 100 ľudí začni s konštantným počtom infikovaných ľudí a nastaveným počtom náhodne generovaných stretnutí jeden na jedného každý deň. Porovnaj šírenie vírusu pri 0%, 30% a 60% miere zaočkovania.