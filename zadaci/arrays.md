# Nizovi u PHP-u

[Sve ugradjene PHP funkcije za rad sa nizovima](https://www.php.net/manual/en/ref.array.php)

## Linkovi

[Osnove nizova](https://github.com/nebojsac/prakticno-programiranje/blob/master/poglavlja/osnove-nizova.md)
[Nizovi i for petlja](https://github.com/nebojsac/prakticno-programiranje/blob/master/poglavlja/napredniji-rad-sa-nizovima.md#nizovi-i-for-petlja)
[Nizovi i foreach petlja](https://github.com/nebojsac/prakticno-programiranje/blob/master/poglavlja/napredniji-rad-sa-nizovima.md#nizovi-i-foreach-petlja)
[Visedimenzionalni nizovi](https://github.com/nebojsac/prakticno-programiranje/blob/master/poglavlja/napredniji-rad-sa-nizovima.md#vi%C5%A1edimenzionalni-nizovi)

## Zadatak 1

```php
$colors = array('bijela', 'zeleni', 'crveni', 'plavo', 'crno');
```

Napišite skriptu koja će prikazati sljedeći string

"Sjećanje na tu scenu za mene je kao kadar filma zauvijek zamrznut u tom trenutku: crveni tepih, zeleni travnjak, bijela kuća, olovno nebo."

Rijeci 'crveni', 'zeleni' and 'bijela' uzmi iz niza $colors.


## Zadatak 2.

```php
$colors = array('white', 'green', 'red');
```

Napišite PHP skriptu koja će prikazati boje na sljedeći način:

white, red, green

## Zadatak 3.

```php
$ceu = [
    "Italy"          => "Rome",
    "Luxembourg"     => "Luxembourg",
    "Belgium"        => "Brussels",
    "Denmark"        => "Copenhagen",
    "Finland"        => "Helsinki",
    "France"         => "Paris",
    "Slovakia"       => "Bratislava",
    "Slovenia"       => "Ljubljana",
    "Germany"        => "Berlin",
    "Greece"         => "Athens",
    "Ireland"        => "Dublin",
    "Netherlands"    => "Amsterdam",
    "Portugal"       => "Lisbon",
    "Spain"          => "Madrid",
    "Sweden"         => "Stockholm",
    "United Kingdom" => "London",
    "Cyprus"         => "Nicosia",
    "Lithuania"      => "Vilnius",
    "Czech Republic" => "Prague",
    "Estonia"        => "Tallin",
    "Hungary"        => "Budapest",
    "Latvia"         => "Riga",
    "Malta"          => "Valetta",
    "Austria"        => "Vienna",
    "Poland"         => "Warsaw"
];
```
Napravite PHP skriptu koja prikazuje glavni grad i naziv zemlje iz gornjeg niza $ceu.

*Primjer*:

The capital of Netherlands is Amsterdam\
The capital of Greece is Athens\
The capital of Germany is Berlin

## Zadatak 4.

```php
$x = array(1, 2, 3, 4, 5);
```

Izbriši treci element iz niza i odstampaj niz. *pomoc: koristi se funkcija: unset()*

Nakon brisanja elementa, noramalizuj ključeve (moraju biti sukcesivni tj. 0,1,2,3...) i odstampaj niz. *koristi se funkcija: array_values()*


## Zadatak 5.

```php
$color = array(4 => 'white', 6 => 'green', 11 => 'red');
```

5.1 Odstampaj prvi element niza.

5.2 Isto uradi koristeci funkciju *[current()](https://www.php.net/manual/en/function.current.php)*

> Svaki niz ima interni pokazivač na "trenutni" element, koji se inicijalizuje na prvi element niza.
> Funkcija current() jednostavno vraća vrijednost elementa niza na koji trenutno ukazuje interni pokazivač. Ne pomjera pokazivač ni na koji način. Ako interni pokazivač pokazuje izvan kraja liste elemenata ili je niz prazan, current() vraća *false*.

5.3 Isto uradi koristeci funkciju *[reset()](https://www.php.net/manual/en/function.reset.php)*

> Funkcija *reset()* vraca unutrašnji pokazivač niza na prvi element i vraća njegovu vrijednost.

5.4 Odstampaj posljednji element niza, koristi funkciju *[end()](https://www.php.net/manual/en/function.end.php)*

> Funkcija *end()* postavlja unutrašnji pokazivač niza na posljednji element i vraća njegovu vrijednost.

## Zadatak 6.

```php
$x = [
    'ja' => 'ne',
    'sam' => 'znam',
    'konj' => 'nista',
];
```

Odstampaj sve kljuceve (indekse) niza $x. *pomoc: koristi funkciju [array_keys()](https://www.php.net/manual/en/function.array-keys.php)*

## Zadatak 7.

```php
$brojevi = "1,2,3,4,5";
```

String $brojevi konvertuj u niz [1,2,3,4,5]. *pomoc: koristi funkciju [explode()](https://www.php.net/manual/en/function.explode.php)*

## Zadatak 8.

```php
$brojevi = [1,2,3,4,5];
```

Niz $brojevi konvertuj u string `"1-2-3-4-5"` . *pomoc: koristi funkciju [implode()](https://www.php.net/manual/en/function.implode.php)*

## Zadatak 9.

```php
$gradovi = "rim,berlin,istambul,madrid";
```

String $gradovi konvertuj u string sa sadrzajem `'Rim, Berlin, Istambul, Madrid'`. *pomoc: koristi funkcije [explode(), ucfirst() i implode()](https://www.php.net/manual/en/function.ucfirst.php)*
