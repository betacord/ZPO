# Zaawansowane programowanie obiektowe

## Zasady zaliczenia
1. Obecność na zajęciach (obowiązują ogólnoakademickie reguły dotyczące dopuszczalnych nieobecności).
2. Systematyczna praca nad projektem zaliczeniowym.
3. Uzyskanie min. 51% punktów z testu kończącego wykład.
4. Uzyskanie min. 51% punktów z końcowego projektu zaliczeniowego oraz oddanie w wyznaczonym terminie.

## Projekt zaliczeniowy

### Tematyka projektu

**Wariant 1**: Na ocenę bardzo dobrą.

Symulator zarządzania biblioteką

Projekt polega na stworzeniu aplikacji konsolowej przeznaczonej do zarządzania biblioteką. Użytkownicy mogą wypożyczać, oddawać, rezerwować książki. Projekt w finalnej wersji ma wykorzystywać minimum po 2 wzorce z każdej grupy: kreacyjnych, strukturalnych oraz czynnościowych. Dobór ich do realizacji konkretnych funkcjonalności jest w pełni dowolny.

### Zasady oceniania
**Ocena dostateczna**: poprawne i uzasadnione zastosowanie jednego wzorca kreacyjnego, strukturalnego oraz czynnościowego (łącznie 3).

**Ocena dobra**: poprawne i uzasadnione zastosowanie dwóch wzorców kreacyjnych, dwóch wzorców strukturalnych oraz jednego wzorca czynnościowego (łącznie 5).

**Ocena bardzo dobra**: poprawne i uzasadnione zastosowanie dwóch wzorców kreacyjnych, dwóch wzorców strukturalnych oraz dwóch wzorców czynnościowych(łącznie 6). Dodatkowo, wykorzystać dowolne narzędzie do utworzenia czytelnego interfejsu (np. biblioteka [typer](https://pypi.org/project/typer/), [rich](https://pypi.org/project/rich/)).

### Wymagania funkcjonalne
1. Zarządzanie użytkownikami:
   1. rejestracja według roli (np. student, wykładowca),
   2. logowanie,
   3. zróżnicowanie uprawnień według przypisanej roli.
2. Zarządzanie książkami:
   1. dodawanie nowych pozycji,
   2. usuwanie i edycja istniejących pozycji,
   3. przeglądanie dostępnych pozycji.
3. Wypożyczanie i zwroty:
   1. możliwość wypożyczenia książki przez zalogowanego użytkownika,
   2. zwrot książki przez zalogowanego użytkownika,
   3. sprawdzenie dostępności książki.
4. Rezerwacje książek:
   1. możliwość rezerwacji niedostępnej książki,
   2. automatyczne powiadomienie (komunikat w konsoli) o dostępności zarezerwowanej książki gdy zostanie zarezerowana (symulacja natychmiastowego zwrotu przez innego użytkownika).
5. Historia i cofanie działań:
   1. wyświetlanie historii wypożyczeń i zwrotów dla danego użytkownika,
   2. możliwość cofnięcia ostatniej operacji (wypożyczenie, zwrot).
6. Symulowane integracja z zewnętrzną bazą książek:
   1. możliwość "pobrania" danych książki z zewnętrznej bazy danych na podstawie ISBN.

**Wariant 2**: Na ocenę dostateczną
Aplikacja konsolowa przeznaczona do zarządzania domowymi zapasami spożywczymi (spiżarnia).

### Zasady oceniania
Na ocenę dostateczną wymagane jest oddanie w pełni funckjonującego i poprawnie opracowanego projektu.

### Wymagania funkcjonalne
1. Zarządzanie zapasami
    1. Dodawanie produktu (nazwa, ilość, jednostka, data ważności).
    2. Aktualizacja stanu.
    3. Usuwanie produktu.
2. Monitoring zapasów 
    1. Przegląd zapasów poprzez wyświetlanie przejrzystej tabeli .
    2. Ostrzeżenia przed upływem daty ważności, np. 3 dni przed terminem.
3. Automatyczna lista zakupów
    1. Lista ustalana na podstawie ustalonych minimów, np. jeśli w spiżarni znajdują się tylko 2 kg ziemniaków, to pozycja ta automatycznie trafia na listę zakupów celem uzupełnienia do minimalnego zapasu np. 5 kg.
    2. Generowanie gotowej listy zakupów za pomocą jednej komendy.
4. Zapis danych
    1. Do działania należy wykorzystać dowolną bazę danych lub plik przechowujący stan spiżarni.
  
**Wymagania pozostałe**
Z uwagi na charakter przedmiotu, aplikacja musi być zrealizowana z zastosowaniem najlepszych praktyk programowania zorientowanego obiektowo. Dodatkowo, podczas opracowywania proszę wykorzystać biblioteki [typer](https://pypi.org/project/typer/) oraz [rich](https://pypi.org/project/rich/)) do przygotowania przejrzystego interfejsu CLI.

### Termin oddania
9 czerwca 2026.

## Samodzielność pracy
Wszystkie projekty zaliczeniowe będą poddawane sprawdzeniu systemem antyplagiatowym oraz systemem wykrywającym udział rozwiązań automatycznych w powstawaniu rozwiązania. W przypadku stwierdzenia niesamodzielności, student uzyskuje ocenę niedostateczną bez możliwości poprawy. Niewykluczone są również dalsze konsekwencje dyscyplinarne.

## Materiały dydaktyczne
1. [Programowanie zorientowane obiektowo](https://github.com/betacord/ZPO/blob/main/1_oop.ipynb)
2. [Wzorce kreacyjne](https://github.com/betacord/ZPO/blob/main/2_creational_patterns.ipynb)
3. [Wzorce strukturalne](https://github.com/betacord/ZPO/blob/main/3_structural_patterns.ipynb)
4. [Wzorce czynnościowe](https://github.com/betacord/ZPO/blob/main/4_behavioral_patterns.ipynb)
