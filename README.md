# Gra w zgadywanie liczb 3 - Aplikacja webowa z Flask

## Opis

To aplikacja webowa, w której użytkownik wybiera sobie liczbę z zakresu 1–1000, a komputer zgaduje jej wartość. Gra jest realizowana przy użyciu frameworka Flask. Użytkownik kontroluje odpowiedzi komputera za pomocą formularza, w którym dostępne są trzy przyciski: `Too small`, `Too big`, oraz `You win`.

### Zasady gry

1. **Wybór liczby:** Użytkownik wybiera sobie liczbę z zakresu 1–1000 (nie wpisuje jej w aplikacji, tylko ją zapamiętuje).
2. **Formularz zgadywania:** Komputer proponuje zgadywaną liczbę, a użytkownik odpowiada:
   - `"Too small"` – jeśli liczba wybrana przez komputer jest za mała,
   - `"Too big"` – jeśli liczba jest za duża,
   - `"You win"` – jeśli komputer trafił poprawną liczbę.
3. **Pola ukryte:** Informacje o bieżących wartościach `min` i `max` przechowywane są w ukrytych polach formularza, co pozwala na ich dynamiczną aktualizację przy każdym odświeżeniu.