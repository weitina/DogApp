DogApp
MovieApp - Jetpack Compose
Prosta aplikacja mobilna na system Android, służąca do przeglądania listy ras psów. Projekt został wykonany w celu przećwiczenia architektury MVC oraz nowoczesnego budowania interfejsu w Jetpack Compose.

O aplikacji
Aplikacja wyświetla listę ras psów. Użytkownik może przeglądać listę, a po kliknięciu w wybraną rasę, informacja o rasie jest przesyłana do logów systemowych (`Log.d`).

Kluczowe funkcjonalności:
* Wykorzystanie komponentu **Scaffold** (TopBar, BottomBar).
* Dynamiczna lista oparta na **LazyColumn**.
* Nawigacja pomiędzy ekranami (Home i Details).
* Obsługa motywów kolorystycznych (Light/Dark Mode).

Sensory i technologie
Mimo że aplikacja skupia się na UI, w ramach laboratorium wykorzystano/przygotowano:
Logcat (Diagnostic Sensor): Monitorowanie zdarzeń wyboru elementu.
State Management: Zarządzanie stanem nawigacji.
Material Design 3: Nowoczesne komponenty interfejsu.

Widok aplikacji

![Screen1](Obraz3.png) ![Screen2](Obraz2.png) ![Screen3](Obraz1.png) ![Screen4](image.png) 

Instrukcja uruchomienia
1. Sklonuj repozytorium:
   `git clone https://github.com/weitina/DogApp.git`
2. Otwórz projekt w **Android Studio**.
3. Poczekaj na synchronizację plików **Gradle**.
4. Uruchom aplikację na emulatorze lub fizycznym smartfonie z Androidem (min. API 24).
5. Otwórz zakładkę **Logcat** w Android Studio i przefiltruj po tagu `TAG`, aby zobaczyć logowanie wybranych filmów.
