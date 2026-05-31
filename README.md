# 🚲 Karta Rowerowa — egzamin próbny

Interaktywny **egzamin próbny z teorii na kartę rowerową** dla dzieci (ok. 10 lat).
Jeden plik HTML, bez żadnych zależności — działa offline po otwarciu w przeglądarce.

**▶️ Wersja online:** https://marad.github.io/karta-rowerowa/

## Co potrafi

- **81 pytań** pokrywających cały oficjalny zakres egzaminu: zasady ruchu, znaki i sygnały,
  pierwszeństwo na skrzyżowaniach, manewry, wyposażenie roweru, pierwsza pomoc i bezpieczeństwo
  (z obowiązkiem kasku dla osób poniżej 16 lat od 3 czerwca 2026).
- **Rysowane znaki drogowe** (inline SVG) i **diagramy skrzyżowań** generowane z konfiguracji —
  zielona strzałka to rowerzysta, czerwona to inny pojazd, droga główna na żółto.
- **Warstwa pytań podchwytliwych** — sprawdzających typowe błędy (np. „rower zawsze ma
  pierwszeństwo" → fałsz; mylenie znaku zakazu z nakazem; żółte/migające światło).
- **4 tryby:** pełny egzamin (25 pytań), szybka rozgrzewka (10), trening znaków, „kto pierwszy?".
- Natychmiastowa informacja zwrotna z wyjaśnieniem, licznik serii, pasek postępu,
  wynik procentowy z progiem **80%**, powtórka błędów, zapamiętywanie najlepszego wyniku.
- Sterowanie myszą lub klawiszami `1` `2` `3` + `Enter`.

## Uruchomienie

Otwórz `index.html` w przeglądarce (dwuklik). To wszystko — nie wymaga internetu ani instalacji.

## Jak powstały pytania

Pytania zostały wygenerowane i przeszły **adwersarialną weryfikację** poprawności pod kątem
polskich przepisów ruchu drogowego (każde sprawdzane niezależnie: czy odpowiedź jest poprawna,
czy jest dokładnie jedna poprawna, czy język jest zrozumiały dla dziecka). Pytania o pierwszeństwo
weryfikowano podwójnie.

> ⚠️ To narzędzie do **ćwiczeń**. Na prawdziwym egzaminie pytania mogą się różnić — nie istnieje
> jeden urzędowy, wiążący zestaw pytań; egzamin przeprowadza przeszkolony nauczyciel w szkole.

## Licencja

MIT — patrz [LICENSE](LICENSE).
