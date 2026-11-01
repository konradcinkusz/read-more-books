# Więcej książek w roku

Jak znaleźć czas i przeczytać dwa razy więcej: arytmetyka czytania, bariery, mikroczas, wybór książek, formaty, nawyk, tempo, pamięć, czytanie z innymi i plan na rok.

* 10 rozdziałów w trzech częściach: cele, przykład, pułapka, ćwiczenia z kluczem, zadanie na tydzień.
* Liczby w tablicach i recepturach są **liczone z danych** (`data/`, `tools/gen.py`), nie wpisywane.
* Twierdzenia o świecie, których autor nie sprawdził w źródle, oznaczone są pomarańczowym **[?]** (`\verify{}`); ich liczba jest drukowana w rejestrze (ostatni dodatek).

## Budowanie

```bash
python3 tools/gen.py && python3 tools/check_book.py   # bramki źródłowe (sekundy)
latexmk -pdf main.tex                                 # PDF
python3 tools/check_log.py main.log                   # log: błędy, odwołania, overfull
```

## Status

**Wersja robocza.** Walidacja na czytelnikach: NIEUSTALONA. Treść: CC BY-NC-SA 4.0 (`LICENSE-CONTENT`), kod: MIT (`LICENSE`).
