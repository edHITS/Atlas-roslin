# Atlas roślin - Cyfrowy zielnik

Natywna aplikacja mobilna na system Android stworzona w języku **Java**, służąca do katalogowania gatunków roślin, tworzenia własnych kart zielnikowych oraz szybkiego wyszukiwania okazów w terenie i ogrodzie.

---

## Główne funkcje

- **Karty zielnikowe gatunków:** Przechowywanie pełnej charakterystyki rośliny — nazwa polska i łacińska, kategoria, zastosowanie, wysokość, rozstawa, kolor, termin kwitnienia, stanowisko, ozdobność oraz pokrój.
- **Galeria wielu zdjęć (`ViewPager2`):** Możliwość przypisania wielu zdjęć z pamięci urządzenia do jednej rośliny i płynnego przeglądania ich w formie karuzeli.
- **Wizualny pasek kwitnienia (`I–XII`):** Interaktywny 12-miesięczny kalendarz kwitnienia z automatycznym rozpoznawaniem zapisów rzymskich, arabskich oraz nazw miesięcy.
- **Zarządzanie kategoriami i kolorami:** Tworzenie własnych kategorii z licznikami przypisanych gatunków oraz definiowanie własnej palety kolorów z próbkami barw.
- **Zaawansowane filtrowanie i sortowanie:** Wyszukiwanie po nazwie polskiej i łacińskiej, filtrowanie po kategorii, wielokrotny wybór kolorów oraz sortowanie (od najnowszych, A–Z PL, A–Z Łac.).
- **Kopia zapasowa `.json`:** Eksport i przywracanie całej bazy roślin, kategorii i kolorów do pliku `.json` w folderze *Pobrane* — pełna odporność na odinstalowanie aplikacji lub zmianę telefonu.
- **Tryb jasny i ciemny:** Botaniczna paleta barw (pergamin i szałwiowa zieleń) w wariancie dziennym oraz nocnym.
- **Automatyczne aktualizacje z GitHub Releases (Wi-Fi):** Ciche sprawdzanie nowych wydań `v1.x` podczas uruchamiania aplikacji wyłącznie przy połączeniu przez Wi-Fi.

---

## Technologie i architektura

- **Język:** Java (Android SDK)
- **Interfejs użytkownika:** Material Design 3, `BottomNavigationView`, `ViewPager2`, `RecyclerView`, autorskie ikony wektorowe SVG/XML
- **Baza danych:** Lokalna baza **SQLite** (`SQLiteOpenHelper`) z automatyczną migracją schematu między kolejnymi wersjami aplikacji
- **Format kopii zapasowych:** `org.json` + `MediaStore.Downloads` / Storage Access Framework

## Autor

**Henryk** — [github.com/edHITS](https://github.com/edHITS?tab=repositories)
