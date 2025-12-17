```mermaid
flowchart LR
    Student["👤 Student\n(wiek 18–25)"]

    subgraph System["📱Aplikacja planowania nauki"]
%% pusta linia robi offset

    A[Start] --> B[Krok 1]
        A["Szybkie dodawanie zadań"]
        B["Lista zadań z priorytetami"]
        C["Edycja / usuwanie zadań"]
        D["Tygodniowy kalendarz"]
        E["Szybka wizualizacja planu nauki"]
        F["Ustawianie przypomnień"]
        G["Otrzymywanie przypomnień"]
        H["Zarządzanie materiałami do nauki"]
        I["Proste statystyki postępów"]
        J["Ustawienia / personalizacja interfejsu"]
    end

    Student --> A
    Student --> B
    Student --> C
    Student --> D
    Student --> E
    Student --> F
    Student --> G
    Student --> H
    Student --> I
    Student --> J
