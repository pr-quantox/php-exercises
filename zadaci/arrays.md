# Nizovi u PHP-u

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

white, green, red

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

