**Uniwersytet w Siedlcach**  
**Wydział Nauk Ścisłych i Przyrodniczych**  
**Kierunek Informatyka**

---

**Przedmiot:** Podstawy Technologii WWW  
**Temat Projektu:** Kopia StackOverflow

**Opracował:** Łukasz Kopański,  
I rok informatyki,  
studia stacjonarne inżynierskie

**Prowadzący:** Mgr. inż. Maciej Nazarczuk

**Siedlce, rok akademicki 2024/2025, semestr letni**

---

## Cel projektu

Celem mojego projektu było stworzenie aplikacji webowej StackCode - kompleksowej platformy do dzielenia się wiedzą programistyczną, wzorowanej na popularnym serwisie StackOverflow. Aplikacja umożliwia programistom zadawanie pytań, udzielanie odpowiedzi, dzielenie się fragmentami kodu oraz budowanie społeczności wokół rozwiązywania problemów programistycznych.

Projekt został zaprojektowany z myślą o stworzeniu intuicyjnego interfejsu, który pozwala użytkownikom na łatwe nawigowanie między różnymi sekcjami, efektywne wyszukiwanie treści oraz interakcję z innymi członkami społeczności poprzez system głosowania i komentarzy. Szczególny nacisk położono na czytelne prezentowanie kodu źródłowego z podświetlaniem składni oraz responsywny design dostosowany do różnych urządzeń.

---

## Opis techniczny

Aplikacja została zbudowana w architekturze klasycznej aplikacji webowej z wykorzystaniem technologii PHP, MySQL, HTML5, CSS3 i JavaScript. Frontend charakteryzuje się nowoczesnym, ciemnym motywem z płynnymi animacjami i responsywnym designem. Backend zapewnia bezpieczne zarządzanie danymi użytkowników, postami i komentarzami z wykorzystaniem przygotowanych zapytań SQL chroniących przed atakami typu SQL Injection.

System uwierzytelniania oparty jest na sesjach PHP z bezpiecznym hashowaniem haseł algorytmem bcrypt. Aplikacja implementuje również system uprawnień, gdzie zalogowani użytkownicy mogą tworzyć posty, komentować i głosować, podczas gdy niezalogowani użytkownicy mają dostęp tylko do przeglądania treści.

---

## Spis funkcjonalności

Opracowana aplikacja umożliwia:

### Funkcjonalności dla wszystkich użytkowników:
- **Przeglądanie postów** - dostęp do wszystkich pytań i odpowiedzi
- **Wyszukiwanie** - zaawansowane wyszukiwanie po tytule i treści
- **Filtrowanie** - sortowanie po kategoriach, dacie, popularności
- **Przeglądanie kategorii** - organizacja treści według tematyki
- **Wyświetlanie kodu** - podświetlanie składni różnych języków programowania
- **Responsywny design** - dostosowanie do urządzeń mobilnych

### Funkcjonalności dla zarejestrowanych użytkowników:
- **Rejestracja i logowanie** - bezpieczne zarządzanie kontami
- **Dodawanie postów** - tworzenie pytań z kodem i obrazami
- **Komentowanie** - udzielanie odpowiedzi i sugestii
- **System głosowania** - ocenianie jakości postów i komentarzy
- **Zarządzanie profilem** - edycja danych osobowych i avatara
- **Edycja własnych postów** - modyfikacja i usuwanie treści
- **Odpowiedzi na komentarze** - zagnieżdżone konwersacje
- **Dodawanie sugestii** - proponowanie poprawek w kodzie
- **Upload plików** - dodawanie obrazów do postów

### Funkcjonalności zarządzania treścią:
- **Kategorie kolorowe** - wizualne oznaczanie tematyki
- **Liczniki wyświetleń** - śledzenie popularności postów
- **System reputacji** - budowanie wiarygodności użytkowników
- **Statystyki użytkownika** - przegląd aktywności i osiągnięć

---

**Autor:** [Łukasz Kopański]  
**Data:** czerwiec 2025
**Wersja:** 1.0
