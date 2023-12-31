﻿# Egzamin Zawodowy

Utwórz katalog egzamin i stwórz dla niego repozytorium. Każdy egzamin ma być zapisany ze wszystkimi plikami w katalogu egzaminX (gdzie X to numer lekcji). Postępuj zgodnie z instrukcją z punktu "Jak wysyłać prace/zadania?"

[Link do egzaminów](https://www.praktycznyegzamin.pl/inf03ee09e14/praktyka/)

1. Egzamin 1 (tag: v0.1.0)

- Utwórz repozyztorium o nazwie "egzamin"
- Stwórz katalog egzamin1/, a w nim utwórz plik github.html z aktywnym linkiem do swojego repozytorium.
- Postępuj zgodnie z instrukcją z punktu "Jak wysyłać prace/zadania?"

2. Egzamin 2 (tag: v0.2.0) Egzamin: EE.09-2022-01-03
3. Egzamin 3 (tag: v0.3.0) Egzamin: EE.09-2021-01-01


# Szybki kurs Laravel

[Kurs](https://laraveldaily.com/course/travel-api)

[Kurs na YT](https://www.youtube.com/watch?v=7WSECfg4UXA&list=PLdXLsjL7A9k2utMAieXUnUP8zyxaDA3mP)

## Środowisko pracy
1. (tag: v0.1.0) [Instrukcja instalacji Laravel z wykorzystaniem XAMPP](/docs/START.md)
2. (tag: v0.2.0) [Schemat DB: modele, migracje, atrybuty](https://laraveldaily.com/lesson/travel-api/database-schema-models-migrations-attributes)

# Jak wysyłać prace/zadania?

1. Utwórz swoje konto w serwisie github.com
2. Prześlij na e-mial zbaszynek.web@gmail.com 

    TYTUŁ: 

    ```
    Zbąszynek: IMIĘ NAZWISKO
    ```

    TREŚĆ:

    ```
    Imię Nazwisko: IMIĘ NAZWISKO
    Github: http://github.com/twojlogin
    ```
3. Po każdych zajęciach należy przesłać wszystkie zmiany na github.
   1. W momencie rozpoczęcia zajęć pobierz aktualne swoje repozytorium
   2. Przejdź na branch "develop" i utwórz branch "feature/lessonX" (X - zgodny z numerem zajęć, zgodnie z numerem filmu lub kolejnościa egzaminów)
   3. Po zakończeniu zajęć wyslij zmiany na github:
   
- Wyślij zmiany z brancha "feature/lessonX" na github
- Przejdź na branch develop i połącz "feature/lessonX" z develop
```
git merge feature/lessonX
```

- Wyślij zmiany z develop
- Przejdź na branch "main" połącz z "develop"

```
git merge develop
```
- Wyślij zmiany z main
- Utwórz tag i wyślij zmiany (TYLKO W MOMENCIE WYKONANEGO ZADANIA w 100%!)

```
git tag v0.X.0
git push origin v0.X.0
```

Oceniany będzie czas przesłania pracy. Każdy dzień opóźnienia -5% pkt za zadanie (maksymalnie 50%). Zaliczone jest tylko zadanie ukończone w 100%. 
Zadanie można dokończyć w domu lub na następnych zajęciach. 

NIE ROZPOCZYNAJ KOLEJNEGO ZADANIA JEŻELI NIE MASZ UKOŃCZONEGO POPRZEDNIEGO!

Jeżeli uznasz, że lekcja została przez ciebie źle wykonana, a już utworzyłeś tag z tych zajęć możesz je poprawić. Tylko zamiast tworzyć branch "feature/leassonX" tworzysz branch "hotfix/lessonX-Y" (gdzie Y to numer poprawki). I następnie utworzyć tag "v0.X.Y".
