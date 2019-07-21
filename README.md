# FlightManagerREST
# FlightManagerREST
Zadanie dla Kandydatów
(sytuacja opisana w zadaniu jest hipotetyczna, w tej chwili nie budujemy takiego systemu...)
Zostaliśmy poproszeni o stworzenie aplikacji do zarządzania turystycznymi lotami w kosmos.
Klient chce, żeby system był dostępny przez przeglądarkę (standardowo używa najnowszego
Chroma, ale nie wyklucza, że niektórzy użytkownicy będa korzystać z innych przeglądarek, w
tym IE).
System ma przechowywać dane w bazie danych SQL lub NoSQL. Wymogiem jest stworzenie
architektury, w której w przeglądarce uruchamia się klienta w javascript komunikującego się
przez REST z serwerem implementującym logikę biznesową i zarządzającym połączeniem z
bazą. W ramach realizowanej usługi klient otrzyma źródła, dlatego wszystkie nazwy i
komentarze powinny być po angielsku.
Funkcjonalności
1. Zarządzanie turystami
a. Lista turystów
b. Dodawanie turysty
c. Usuwanie turysty
d. Edycja turysty
i.
Dodawanie lotu (wybór z istniejących w systemie lotów, uwaga na liczbę
miejsc)
ii.
Usuwanie lotu
2. Zarządzanie lotami
a. Lista lotów
b. Dodawanie lotu
c. Usuwanie lotu
d. Edycja lotu
i.
Dodawanie turysty do lotu (wybór istniejących w systemie turystów,
uwaga na liczbę miejsc)
ii.
Usuwanie turysty z lotu
Struktura danych
1. Turysta
a. Imię
b. Nazwiskoc.
d.
e.
f.
g. Płeć
Kraj
Notatki
Data urodzenia
Lista lotów
a.
b.
c.
d.
e. Data i czas wylotu
Data i czas przylotu
Liczba miejsc
Lista turystów
Cena biletu
2. Lot
Zadanie
Proszę przygotować prostą aplikację zgodną z powyższą specyfikacją.
