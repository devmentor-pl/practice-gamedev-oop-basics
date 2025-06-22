> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s10e05-gamedev-oop-basics` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#05` GameDev: Programowanie Obiektowe Część I

## Warcaby
Wzorując się na ćwiczeniu `Szachownica` z modułu 2, zaimplementuj prostą wersję gry w warcaby:
1. Klasa `Pawn` reprezentuje pionek, zawiera informację, czy jest biały, czy też czarny
2. Klasa `Field` reprezentuje pole na planszy, zawiera referencję do stojącego na nim pionka
3. Klasa `Board` reprezentuje planszę i zawiera wszystkie pola
4. Program wyświetla planszę wedle następujących zasad:
   - Nad planszą jest wyświetlona lista kolumn: `A B C`... etc.
   - Po lewej stronie planszy są wyświetlone numery wierszy
   - Białe piony są wyświetlane jako `W`, a czarne jako `B`
   - Puste pola są wyświetlane na takich samych zasadach, jak w ćwiczeniu `Szachownica`
5. Program decyduje o tym, który gracz (biały lub czarny) może teraz wykonać ruch
6. Gracz wpisuje numer pola (np. `A5`), na którym znajduje się jego pionek, i wpisuje numer pola, na które ma się przemieścić
7. Ruch pionków odbywa się zgodnie z zasadami gry w warcaby (tylko po skosie, na sąsiednie pola)
8. Mechanika bicia: przeskakiwanie nad wrogim pionkiem i usuwanie go z planszy
9. Gra się toczy aż jeden z graczy utraci wszystkie pionki
10. Program czuwa nad przestrzeganiem zasad gry oraz prawidłowością podawanych numerów pól, wyświetlając adekwatne komunikaty w przypadku niepoprawnych danych

Mechaniki dodatkowe:
1. Pionek po dotarciu do przeciwległego końca planszy zamienia się w damę i może poruszać się o dowolną ilość pól
2. Wielokrotne bicie w jednej turze
3. Zapisywanie historii ruchów w trakcie gry i możliwość ich przeczytania w jednolitym bloku tekstu po ukończonej grze

&nbsp;

> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-gamedev-oop-basics)*

> :arrow_left: [*poprzednie zadanie*](./../04) | ~~*następne zadanie*~~ :arrow_right:
