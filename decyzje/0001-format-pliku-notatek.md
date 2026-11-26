# 0001 — Format pliku z notatkami

Kontekst: W notatniku z Budowy 2 zapisywanie notatek działo się lokalnie, ale przy pracy nad plikiem łatwo było o utratę lub rozjechanie wpisów przy nadpisywaniu, a notatki miały pozostać czytelne i edytowalne także w zwykłym edytorze poza aplikacją.
Decyzja: Notatki będą przechowywane w jednym pliku tekstowym w formacie Markdown, gdzie każdy wpis ma nagłówek z datą i tytułem, a treść znajduje się pod nim.
Odrzucone: Zapis każdej notatki w osobnym pliku (przy większej liczbie wpisów tworzy się bałagan w katalogu) oraz format JSON (słabsza czytelność i wygoda przy ręcznym przeglądaniu lub poprawianiu w zwykłym edytorze).
Skutki: Plik jest czytelny w każdym edytorze i łatwy do przejrzenia w diffie, ale dopisywanie lub sortowanie wpisów w jednym pliku wymaga parsowania i przepisania całości, co przy błędnym zapisie utrudnia bezpieczne utrzymanie treści i trzeba to uwzględnić w kryteriach specyfikacji.