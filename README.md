# 4.2-repozytorium-4ta-2-hubert-a

Repozytorium startowe z konstytucją projektu oraz pierwszą decyzją architektoniczną (bez kodu aplikacji).

## Rozsortowanie 12 zdań

### Plik reguł (jak pisać kod — leci do kontekstu przy pracy z agentem)
- 1. Metoda nie może być dłuższa niż dwadzieścia linii.
- 8. Nie zmieniaj plików, o które nie było prośby.
- 10. Wszystkie pliki w UTF-8.

### Specyfikacja (co robi konkretna funkcja i jak to sprawdzić)
- 3. Kiedy tytuł notatki jest pusty, przycisk zapisu jest nieaktywny.
- 7. Notatki sortujemy od najnowszej.
- 11. Program uruchamia się w mniej niż dwie sekundy.

### Konstytucja (co jest zawsze prawdą niezależnie od funkcji)
- 5. Program jest dla jednej osoby na jednym komputerze.
- 9. Dane nigdy nie opuszczają komputera użytkownika.

### Zapis decyzji (dlaczego wybrano konkretne rozwiązanie i co odrzucono)
- 4. Wybraliśmy Markdown zamiast JSON, bo plik ma być czytelny w edytorze.
- 12. Zrezygnowaliśmy z wyszukiwania w tej wersji, bo wydłużyłoby tydzień o drugi.

### Zdania dwuznaczne — od czego zależy klasyfikacja
- **2. Program nie wymaga połączenia z internetem.** — Jeśli traktujemy to jako cechę lokalnego programu bez chmury/kont, pasuje do **konstytucji**; jeśli jako konkretne wymaganie działania funkcji w trybie offline bez zewnętrznych zapytań, trafia do **specyfikacji**.
- **6. Komunikaty o błędach są po polsku.** — Jeśli chodzi o ogólną spójność komunikacji z użytkownikiem, pasuje do **konstytucji** (lub ogólnego **pliku reguł**), a jeśli dotyczy konkretnych ekranów lub walidacji pól — do **specyfikacji**.

## Zasada z szablonu konstytucji Spec Kit
- **Wybrana zasada:** „Constitution supersedes all other practices” (konstytucja stoi ponad innymi praktykami).
- **Źródło i data:** GitHub Spec Kit (`constitution-template.md`), odczytano: 2026-09-02.
- **Dlaczego dla notatnika byłaby bez sensu:** Dla małego, lokalnego notatnika jednej osoby rozbudowana ceremonia procesowa jak dla dużych zespołów jest zbędna — wystarczy krótki zbiór kilku nienaruszalnych założeń.