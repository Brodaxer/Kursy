# KursySzkolenia

Tworzymy aplikację do sprzedaży kursów oraz szkoleń. Nasza wirtualna firma sprzedaje dwa rodzaje kursów:

    online - prowadzone drogą internetową,
    stacjonarne - prowadzone w siedzibach firmy w różnych miastach.

Niezależnie od typu kursu / szkolenia, mają one przypisany identyfikator (np. JAVA-ONLINE-123, albo JAVA-STACJO-WRO-234), cenę, nazwę i krótki opis. Kursy online posiadają dodatkowe informacje takie jak liczba minut wideo dostępnych w kursie i szacowany czas przerobienia takiego kursu (również w minutach). W przypadku szkoleń stacjonarnych przechowujemy informację o miejscowości, w której szkolenie się odbywa i dodatkowo liczbę zajęć.

Istnieje również specjalny typ kursów online, tzw. Bootcamp, gdzie uczestnik może liczyć na wsparcie trenera. Klasa opisująca taki kurs powinna przechowywać dodatkowo informację o prowadzącym (jego imię i nazwisko) oraz to, ile godzin konsultacji ma do dyspozycji uczestnik takiego szkolenia.

Wykorzystując dziedziczenie, zdefiniuj odpowiednie klasy, które będą odpowiadały powyżej opisanemu scenariuszowi, Nie muszą one posiadać konstruktorów. Stwórz co najmniej jeden obiekt reprezentujący kurs lub szkolenie i wyświetl o nim informacje w konsoli.
