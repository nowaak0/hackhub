# Dokumentacja projektu HackHub - Innowacyjna Platforma Społecznościowa

## I. Charakterystyka oprogramowania

**a. Nazwa skrócona:** HackHub

**b. Nazwa pełna:** System Zarządzania Interakcjami Społecznościowymi z Funkcjonalnościami Publikacji i Moderacji Treści

**c. Krótki opis ze wskazaniem celów:**
HackHub służy do zarządzania interakcjami społecznościowymi, umożliwiając użytkownikom rejestrację, tworzenie profili, publikowanie treści oraz interakcję z innymi użytkownikami. Głównym celem jest stworzenie platformy społecznościowej, która zapewnia użytkownikom narzędzia do komunikacji, udostępniania treści oraz monitorowania aktywności.

## II. Prawa autorskie

**a. Autorzy:** Franciszek Markul, Paweł Nowak

**b. Warunki licencyjne:** Oprogramowanie jest objęte licencją MIT, co pozwala na jego swobodne używanie, modyfikowanie oraz dystrybucję, pod warunkiem zachowania informacji o oryginalnych autorach.

## III. Specyfikacja wymagań

| Identyfikator | Nazwa                       | Opis                                                                                               | Priorytet | Kategoria      |
|---------------|-----------------------------|----------------------------------------------------------------------------------------------------|-----------|----------------|
| 1             | Rejestracja użytkowników    | Umożliwienie użytkownikom rejestracji konta za pomocą adresu e-mail, numeru telefonu na platformie społecznościowej. | 1         | Funkcjonalne   |
| 2             | Tworzenie profilu           | Możliwość dodawania podstawowych informacji o użytkowniku, takich jak imię, nazwisko, zdjęcie profilowe, biografia itp. | 1         | Funkcjonalne   |
| 3             | Publikowanie treści         | Umożliwienie użytkownikom publikowania krótkich wiadomości.          | 1         | Funkcjonalne   |
| 4             | Interakcje społecznościowe  | Możliwość polubienia i komentowania postów innych użytkowników.                      | 1         | Funkcjonalne   |
| 5             | Statystyki aktywności       | Dostęp do statystyk dotyczących aktywności użytkowników, takich jak liczba followersów, polubień. | 2         | Funkcjonalne   |
| 6             | Wyszukiwanie postów         | Możliwość wyszukiwania postów użytkowników na platformie.                                           | 1         | Funkcjonalne   |
| 7             | Zarządzanie kontem          | Panel użytkownika umożliwiający zarządzanie ustawieniami konta.                  | 2         | Funkcjonalne   |
| 8             | Wielojęzyczność             | Obsługa różnych języków w interfejsie użytkownika.                                                 | 2         | Funkcjonalne   |
| 9            | Responsywny interfejs       | Responsywny interfejs użytkownika.                      | 1         | Niefunkcjonalne |
| 10            | Monitoring wydajności       | Narzędzia monitorowania wydajności systemu.                                                        | 1         | Niefunkcjonalne |
| 11            | Skalowalność infrastruktury | Skalowalność infrastruktury w przypadku wzrostu liczby użytkowników i aktywności na platformie.     | 1         | Niefunkcjonalne |

## IV. Architektura systemu/oprogramowania

### 1. Architektura rozwoju - stos technologiczny

1. **Język programowania:** PHP
2. **Framework:** Laravel

### 2. Architektura uruchomieniowa - stos technologiczny

1. Środowisko: Visual Studio Code (VS Code) to zintegrowane środowisko programistyczne (IDE) opracowane przez firmę Microsoft. Jest to wszechstronne i darmowe narzędzie, które obsługuje wiele języków programowania, w tym np. Python, PHP. VS Code jest popularne wśród programistów dzięki swojej lekkości, wydajności i bogatej funkcjonalności.

### 3. Biblioteki

1. **Bootstrap**: Biblioteka CSS do stylizowania formularzy i komponentów.
2. **Font Awesome**: Biblioteka ikon używana do dodawania ikon do aplikacji webowej.
3. **Blade Template Engine**: Silnik szablonów używany w Laravelu do tworzenia dynamicznych widoków.

## V. Testy

**Scenariusze testów:**

1. **Test rejestracji:** Sprawdzenie poprawności procesu rejestracji użytkownika.
2. **Test publikowania treści:** Sprawdzenie możliwości publikacji tekstu.
3. **Test interakcji społecznościowych:** Weryfikacja działania funkcji polubień i komentarzy.
4. **Test statystyk:** Weryfikacja dostępności i dokładności statystyk aktywności użytkowników.
5. **Test wyszukiwania:** Sprawdzenie skuteczności wyszukiwania postów na platformie.
6. **Test zarządzania kontem:** Ocena panelu użytkownika do zarządzania ustawieniami konta.


**Sprawozdanie z wykonania scenariuszy testów:**

Wszystkie testy zostały przeprowadzone pomyślnie. System poprawnie obsługuje wszystkie wymagane funkcje.
