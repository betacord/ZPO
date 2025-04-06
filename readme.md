# Zaawansowane programowanie obiektowe

## Zasady zaliczenia
1. Obecność na zajęciach (obowiązują ogólnoakademickie reguły dotyczące dopuszczalnych nieobecności).
2. Systematyczna praca nad projektem zaliczeniowym.
3. Uzyskanie min. 51% punktów z testu kończącego wykład.
4. Uzyskanie min. 51% punktów z końcowego projektu zaliczeniowego oraz oddanie w wyznaczonym terminie.

## Projekt zaliczeniowy

### Tematyka projektu

Symulator zarządzania biblioteką

Projekt polega na stworzeniu aplikacji konsolowej przeznaczonej do zarządzania biblioteką. Użytkownicy mogą wypożyczać, oddawać, rezerwować książki. Projekt w finalnej wersji ma wykorzystywać minimum po 2 wzorce z każdej grupy: kreacyjnych, strukturalnych oraz czynnościowych. Dobór ich do realizacji konkretnych funkcjonalności jest w pełni dowolny.

### Zasady oceniania
**Ocena dostateczna**: poprawne i uzasadnione zastosowanie jednego wzorca kreacyjnego, strukturalnego oraz czynnościowego (łącznie 3).

**Ocena dobra**: poprawne i uzasadnione zastosowanie dwóch wzorców kreacyjnych, dwóch wzorców strukturalnych oraz jednego wzorca czynnościowego (łącznie 5).

**Ocena bardzo dobra**: poprawne i uzasadnione zastosowanie dwóch wzorców kreacyjnych, dwóch wzorców strukturalnych oraz dwóch wzorców czynnościowych(łącznie 6). Dodatkowo, wykorzystać dowolne narzędzie do utworzenia czytelnego interfejsu (np. biblioteka [typer](https://pypi.org/project/typer/)).

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

### Termin oddania
3 czerwca 2025.

## Samodzielność pracy
Wszystkie projekty zaliczeniowe będą poddawane sprawdzeniu systemem antyplagiatowym oraz systemem wykrywającym udział rozwiązań automatycznych w powstawaniu rozwiązania. W przypadku stwierdzenia niesamodzielności, student uzyskuje ocenę niedostateczną bez możliwości poprawy. Niewykluczone są również dalsze konsekwencje dyscyplinarne.

## Materiały dydaktyczne
1. [Programowanie zorientowane obiektowo](https://github.com/betacord/ZPO/blob/main/1_oop.ipynb)
2. [Wzorce kreacyjne](https://github.com/betacord/ZPO/blob/main/2_creational_patterns.ipynb)
3. [Wzorce strukturalne](https://github.com/betacord/ZPO/blob/main/3_structural_patterns.ipynb)
4. [Wzorce czynnościowe](https://github.com/betacord/ZPO/blob/main/4_behavioral_patterns.ipynb)
