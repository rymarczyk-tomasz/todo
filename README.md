# ToDo App

Prosta aplikacja ToDo zbudowana przy użyciu **React** i **Vite**. Umożliwia dodawanie nowych zadań, oznaczanie ich jako ukończone oraz usuwanie. Aplikacja działa wyłącznie po stronie klienta, bez backendu, a dane są przechowywane w lokalnym stanie aplikacji.

## Funkcjonalności

-   Dodawanie nowych zadań
-   Oznaczanie zadań jako ukończone
-   Usuwanie zadań
-   Przechowywanie stanu w lokalnym stanie React (brak trwałości danych po odświeżeniu strony)

## Technologie

-   **React** (biblioteka do budowania interfejsu użytkownika)
-   **Vite** (narzędzie do szybkiego budowania i uruchamiania aplikacji)
-   **JavaScript** (ES6+)
-   **CSS** (stylowanie komponentów)

## Wymagania

-   Node.js (zalecana wersja: 18.x lub nowsza)
-   npm (zwykle instalowany z Node.js)

## Instalacja i uruchomienie

1. Sklonuj repozytorium:

    ```bash
    git clone <adres-repozytorium>
    cd todo-app
    ```

2. Zainstaluj zależności

```bash

npm install
```

3.  Uruchom aplikację w trybie deweloperskim

```bash
npm run dev
```

4.  Otwórz przeglądarkę i przejdź do adresu podanego w konsoli (domyślnie http://localhost:5173).

## Użycie

-   W polu tekstowym wpisz nazwę nowego zadania i kliknij przycisk "Dodaj" lub naciśnij Enter.

-   Aby oznaczyć zadanie jako ukończone, kliknij pole wyboru obok zadania.

-   Aby usunąć zadanie, kliknij przycisk "Usuń" obok wybranego zadania.

## Możliwe rozszerzenia

-   Dodanie lokalnego zapisu danych (np. localStorage) dla trwałości po odświeżeniu strony.

-   Filtrowanie zadań (np. wszystkie, ukończone, nieukończone).

-   Edycja istniejących zadań.

-   Stylowanie za pomocą frameworka CSS (np. Tailwind CSS, Material-UI).

## Znane ograniczenia

-   Dane są przechowywane tylko w stanie aplikacji, więc odświeżenie strony resetuje listę zadań.

-   Brak walidacji formularza (np. blokowania pustych zadań).
