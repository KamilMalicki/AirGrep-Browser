# AirGrep Browser

AirGrep to minimalistyczna przeglądarka internetowa na Androida, skupiona na szybkości, prywatności i wygodnym pobieraniu plików. Zawiera wbudowany bloker reklam oraz tryb prywatny.

## Główne funkcje

### Przeglądanie stron
- Obsługa JavaScript, DOM storage, HTML5
- Pasek adresu z automatycznym dodawaniem `https://`
- Ładowanie stron z historii i ręczne wpisywanie adresów

### Nawigacja
- Przycisk Wstecz – cofanie do poprzedniej strony
- Przycisk Dalej – powrót do kolejnej strony
- Przycisk Odśwież – przeładowanie bieżącej strony
- Przycisk Strona domowa – otwiera `https://airgrep.rf.gd`
- Przycisk Informacje – pokazuje dane o aplikacji

### Tryb prywatny
- Włączenie: wpisz `airgrep://private-mode`
- Wyłączenie: wpisz `airgrep://private-mode-off`
- Nie zapisuje historii, cache, cookies

### Czyszczenie danych (komendy)
- `airgrep://clear-cache` – czyści cache
- `airgrep://clear-history` – czyści historię
- `airgrep://clear-cookies` – usuwa ciasteczka
- `airgrep://clear-all` – czyści wszystkie dane

### Pobieranie plików
- Automatyczne wykrywanie linków do plików
- Używa `DownloadManager` z powiadomieniami
- Długie przytrzymanie przycisku „Connect” pozwala pobierać pliki z GitHub (raw)

### Blokowanie reklam
- Wbudowany blok reklam popularnych domen
- Blokowanie na poziomie żądań HTTP

### Tryb offline
- Przy braku internetu ładuje lokalną stronę `offline.html`

## Jak korzystać

1. Uruchom aplikację – ładuje domyślną stronę `https://airgrep.rf.gd`.
2. Wpisz adres w pasku i kliknij „Connect”.
3. Nawiguj za pomocą przycisków Back, Forward, Reload i Home.
4. Kliknij link do pliku, by pobrać.
5. Wpisz komendy `airgrep://private-mode`, `airgrep://clear-cache` itd. w pasku adresu, by zarządzać trybem prywatnym i danymi.

## Informacje techniczne

- Minimalne SDK: 31 (Android 12)
- Uprawnienia:  
  - `WRITE_EXTERNAL_STORAGE` niepotrzebne przy SDK 31 i scoped storage  
- Autor: Kamil Malicki

## Prywatność

- Brak telemetrii i analityki
- Tryb prywatny nie zapisuje historii ani plików cookie
- Dane można ręcznie czyścić z poziomu paska adresu

---

Ciesz się szybkim i bezpiecznym przeglądaniem z AirGrep.
