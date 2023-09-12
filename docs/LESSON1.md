# LEKCJA 1

## Edytor

Pobierz i zainstaluj (o ile nie jest zinstalowany :))
```
https://code.visualstudio.com/docs/?dv=win
```

Zainstaluj następujące rozszeżenia (Ctrl+Shift+X):

- Project Manager
- Markdown All in One
- Code Spell Checker
- Better Comments
- DotENV
- Error Lens
- Laravel Extra Intellisense
- Laravel Ide Helper
- Laravel Snippets
- Log File Highlighter
- PHP Create Class
- PHP Intelephense 
- PHP Namespace Resolver
- Polish - Code Spell Checker
- Prettier Formatter for Visual Studio Code
- SQL Formatter
- Todo Tree

## Serwery

Tutorial instalacji Laravel w środowisku Windows

https://www.youtube.com/watch?v=FC7JQItVqzM

### XAMPP 

https://www.apachefriends.org/pl/index.html

### Composer

https://getcomposer.org/download/

### Nodejs & npm

https://nodejs.org/en

## GIT

### Instalcja

```
https://git-scm.com/download/win
```

### Konfiguracja

Po instalcji wykonaj w wierszu poleceń następujące polecenia:

Set your username: 
```
git config --global user.name "FIRST_NAME LAST_NAME"
```
Set your email address: 
```
git config --global user.email "MY_NAME@example.com"
```

## Laravel

### Konfiguracja PHP

Włącz zip extension dla PHP

```
https://www.youtube.com/watch?v=mrwQoPE7AdM
```

Przejdź w konsoli do katalogu

```
C:\xampp\htdpcs
```

i wykonaj polecenie

```
composer create-project laravel/laravel my-app
```

po zainstalowaniu przejdź do katalogu

```
cd my-app
```

i wykonaj polecenie

```
php artisan server
```
Uruchom w przeglądarce poniższy adres

```
http://127.0.0.1:8000/
```

Utwórz swoje pierwsze repozytorium i wyślij zmiany. Jako nazwę repozytorium podaj 

```
my-app
```
Krótki tutorial Git I Github
```
https://www.youtube.com/watch?v=0X-_Boa0qx4
```

Przydatne polecenia:

```
git tag v0.1.0
git push origin v0.1.0
```