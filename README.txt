MOJE ROBÓTKI — aplikacja PWA

ZAWARTOŚĆ
- index.html — aplikacja
- manifest.webmanifest — ustawienia instalacji
- sw.js — obsługa offline i pamięci podręcznej
- icon.svg — ikona

JAK URUCHOMIĆ I DODAĆ NA ANDROIDZIE
1. Rozpakuj ZIP.
2. Umieść zawartość folderu na hostingu obsługującym HTTPS (np. GitHub Pages).
   Ważne: PWA wymaga adresu HTTPS (localhost jest wyjątkiem dla testów).
3. Otwórz uzyskany adres w Chrome na telefonie.
4. W menu Chrome wybierz „Zainstaluj aplikację” albo „Dodaj do ekranu głównego”.
5. Uruchom aplikację z nowej ikony.

DANE I PRYWATNOŚĆ
- Projekty, dziennik sesji i zdjęcia są zapisywane lokalnie w IndexedDB przeglądarki.
- Po instalacji aplikacja może działać offline po pierwszym poprawnym otwarciu.
- Dane nie synchronizują się automatycznie między urządzeniami.
- Przycisk „Eksport kopii” zapisuje plik JSON z projektami, historią i zdjęciami.
- Przycisk „Wczytaj kopię” pozwala przywrócić dane z pliku JSON.
- Nie czyść danych przeglądarki/aplikacji bez wcześniejszego eksportu kopii.

FUNKCJE
- dodawanie i edycja projektów, zdjęć, wzoru, rozmiaru szydełka/drutów, włóczki i wymiarów
- aktualny numer rzędu
- dziennik postępów: data, numer rzędu, różnica względem poprzedniego stanu, notatka i zdjęcie
- historia sesji bez nadpisywania wcześniejszych wpisów
- wyszukiwanie, filtrowanie, eksport i import kopii

UWAGA
To samodzielna wersja PWA przygotowana do umieszczenia na hostingu. Sam ZIP nie instaluje aplikacji automatycznie i nie publikuje jej w internecie.
