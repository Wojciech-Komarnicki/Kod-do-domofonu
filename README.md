# 🚪 Projekt: Symulator Domofonu (Console Intercom System)

Minimalistyczny symulator systemu domofonowego zaimplementowany w Pythonie. Projekt demonstruje podstawową obsługę konsoli, walidację danych wejściowych oraz efekty wizualne (animacja odliczania i dynamiczne czyszczenie ekranu).

---

## 🌟 Funkcjonalności

* **Autoryzacja:** Wprowadzanie numeru mieszkania i odpowiadającego mu kodu dostępu.
* **Wieloplatformowe Czyszczenie Konsoli:** Funkcja `wyczysc_konsole()` zapewnia czysty interfejs użytkownika, działając na Windows (`cls`) i Linux/macOS (`clear`).
* **Animacja Odliczania:** W przypadku poprawnego kodu, program wyświetla 5-sekundowe odliczanie na tej samej linii, symulując czas otwarcia drzwi.
* **Obsługa Błędów:** Zabezpieczenie przed błędami wejścia (np. wprowadzaniem tekstu zamiast liczb) i obsługa niepoprawnych danych.

---

## 🚀 Wymagania i Uruchomienie

Projekt wymaga standardowej instalacji Pythona 3.x.

### Uruchomienie

Uruchom skrypt bezpośrednio w **terminalu systemowym** (CMD/PowerShell/Terminal) za pomocą polecenia:

```bash
python nazwa_pliku.py
