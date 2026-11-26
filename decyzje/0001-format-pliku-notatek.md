# 0001 — Format pliku z notatkami

Kontekst: W poprzedniej wersji notatnika zapis notatek miał działać lokalnie i prosto, ale sposób przechowywania wpisów łatwo było rozbić przy modyfikacji pliku lub gubić przy nadpisywaniu, a dane powinny pozostać czytelne w zwykłym edytorze.
Decyzja: Notatki będą trzymane w jednym pliku tekstowym w formacie Markdown, gdzie każdy wpis ma własny nagłówek z datą i tytułem, a treść znajduje się pod nim.
Odrzucone: Zapis każdego wpisu w osobnym pliku (szybko robi się bałagan w katalogu przy większej liczbie notatek) oraz format JSON (mniej wygodny do ręcznego przejrzenia i poprawienia w zwykłym edytorze).
Skutki: Plik można łatwo podejrzeć w dowolnym edytorze i szybko sprawdzić w diffie, ale dopisywanie lub sortowanie wpisów w jednym pliku wymaga ostrożnego parsowania i przepisania pliku, co utrudnia bezpieczny zapis przy większej liczbie notatek i trzeba to ująć w kryteriach specyfikacji.