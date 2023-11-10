# Zadanie z  PHP

- Wypisz liczby od 1 do 10, ale tylko parzyste.
- Oblicz sumę liczb od 1 do 100, ale wypisz ją tylko, jeśli suma przekroczy 500.
- Sprawdź, czy liczba jest dodatnia, ujemna czy równa zeru.
- Wypisz liczby parzyste od 2 do 20, ale tylko jeśli są podzielne przez 4.
- Oblicz silnię liczby 5, ale tylko jeśli liczba jest nieparzysta.
- Sprawdź, czy liczba jest podzielna przez 3 i 5 jednocześnie.
- Wypisz tabliczkę mnożenia dla liczby 7, ale tylko dla parzystych mnożników.
- Znajdź największą liczbę w tablicy liczb, ale tylko jeśli jest ona większa niż 10.
- Wypisz liczby od 10 do 1 w odwrotnej kolejności, ale tylko parzyste.
- Sprawdź, czy długość stringa wynosi dokładnie 5 znaków, a jeśli tak, wypisz go.
- Oblicz średnią arytmetyczną elementów tablicy liczb, ale tylko jeśli jest ona większa niż 20.
- Sprawdź, czy string zaczyna się od litery "A", a jeśli tak, wypisz go.
- Wypisz liczby pierwsze od 1 do 20, ale tylko te większe niż 10.
- Odwróć kolejność liter w stringu, ale tylko jeśli string ma co najmniej 3 litery.
- Wypisz wszystkie litery w stringu "PHP", ale tylko małe litery.
- Zsumuj tylko dodatnie liczby w tablicy liczb, a jeśli suma przekroczy 50, przerwij pętlę.
- Sprawdź, czy dwa stringi są identyczne (bez uwzględniania wielkości liter), a jeśli tak, wypisz komunikat.
- Znajdź najmniejszą liczbę w tablicy liczb, ale tylko jeśli jest ona mniejsza niż 5.
- Zlicz wystąpienia litery "a" w stringu, ale tylko dla dużych liter.
- Wypisz liczby od 1 do 50, ale przerwij pętlę po napotkaniu liczby 30.
- Pomnóż każdy element tablicy liczb przez 2, ale tylko jeśli liczba jest nieparzysta.
- Sprawdź, czy string jest pusty, a jeśli nie, wypisz go.
- Wypisz liczby nieparzyste od 1 do 15, ale tylko te większe niż 5.
- Znajdź sumę liczb parzystych od 1 do 50, ale tylko dla liczb mniejszych niż 30.
- Wypisz kwadraty liczb od 1 do 10, ale tylko dla liczb parzystych.
- Sprawdź, czy liczba jest liczbą pierwszą, a jeśli tak, wypisz ją.
- Wypisz litery stringu od tyłu, ale tylko dla stringów dłuższych niż 3 znaki.
- Znajdź różnicę między sumą liczb parzystych a sumą liczb nieparzystych od 1 do 20.
- Wypisz co drugą literę w stringu, ale tylko dla stringów dłuższych niż 5 znaków.
- Sprawdź, czy tablica liczb zawiera conajmniej jedną liczbę większą niż 50, a jeśli tak, wypisz komunikat.

```
<?php

// Deklaracja tablicy zamówień
$zamowienia = [
    [
        'numer_zamowienia' => 12345,
        'data_zamowienia' => '2023-11-10',
        'produkty' => [
            [
                'nazwa' => 'Laptop',
                'cena' => 1999.99,
                'ilosc' => 2
            ],
            [
                'nazwa' => 'Mysz',
                'cena' => 29.99,
                'ilosc' => 1
            ]
        ],
        'klient' => [
            'imie' => 'Anna',
            'nazwisko' => 'Nowak',
            'adres' => 'ul. Leśna 5, 30-001 Kraków'
        ],
        'suma' => 0
    ],
    [
        'numer_zamowienia' => 67890,
        'data_zamowienia' => '2023-11-12',
        'produkty' => [
            [
                'nazwa' => 'Smartfon',
                'cena' => 799.99,
                'ilosc' => 1
            ],
            [
                'nazwa' => 'Słuchawki',
                'cena' => 129.99,
                'ilosc' => 2
            ]
        ],
        'klient' => [
            'imie' => 'Tomasz',
            'nazwisko' => 'Kowalczyk',
            'adres' => 'ul. Kwiatowa 15, 05-001 Warszawa'
        ],
        'suma' => 0
    ],
    [
        'numer_zamowienia' => 13579,
        'data_zamowienia' => '2023-11-15',
        'produkty' => [
            [
                'nazwa' => 'Konsola',
                'cena' => 1499.99,
                'ilosc' => 1
            ],
            [
                'nazwa' => 'Gra',
                'cena' => 59.99,
                'ilosc' => 3
            ]
        ],
        'klient' => [
            'imie' => 'Marcin',
            'nazwisko' => 'Wiśniewski',
            'adres' => 'ul. Polna 8, 50-002 Wrocław'
        ],
        'suma' => 0
    ]
];

// Przykład użycia danych z tablicy zamówień
foreach ($zamowienia as $zamowienie) {
    echo "Numer zamówienia: " . $zamowienie['numer_zamowienia'] . "<br>";
    echo "Data zamówienia: " . $zamowienie['data_zamowienia'] . "<br>";

    echo "<br>Produkty:<br>";
    foreach ($zamowienie['produkty'] as $produkt) {
        echo "Nazwa: " . $produkt['nazwa'] . ", Cena: " . $produkt['cena'] . ", Ilość: " . $produkt['ilosc'] . "<br>";
    }

    echo "<br>Dane klienta:<br>";
    echo "Imię: " . $zamowienie['klient']['imie'] . "<br>";
    echo "Nazwisko: " . $zamowienie['klient']['nazwisko'] . "<br>";
    echo "Adres: " . $zamowienie['klient']['adres'] . "<br>";

    echo "<br>Suma zamówienia: " . $zamowienie['suma'] . " PLN<br><br>";
}

?>
```
- Dodaj nowe zamówienie do tablicy zamówień. Nowe zamówienie powinno mieć unikalny numer zamówienia i różne produkty niż już istniejące zamówienia.

- Oblicz łączną sumę wszystkich zamówień (sumę wszystkich sum).

- Znajdź i wyświetl informacje o produkcie o najwyższej cenie spośród wszystkich zamówień.

- Znajdź, ile razy produkt "Słuchawki" został zamówiony we wszystkich zamówieniach.

- Oblicz łączną ilość wszystkich produktów zamówionych we wszystkich zamówieniach.

- Sprawdź, czy któremuś z klientów zamówienia mieszka w Warszawie, i wyświetl informację na ten temat.

- Znajdź i wyświetl informacje o zamówieniu z najwcześniejszą datą zamówienia.






