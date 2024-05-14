## Grundlagen in der Informationstechnik

### Kenntnis des Zeichensatzes ASCII

ASCII steht für "American Standard Code for Information Interchange" und stellt einen standard zum Codieren von
Textzeichen dar. Die Erste veröffentlichung des Standards war 1963, wurde dann allerdings 1967 nochmal grundlegend
überarbeitet. Da es sich um einen amerikanischen Standard handelt, sind umlaute wie: ä,ö,ü,ß nicht enthalten.

#### Bullet Points:

* 7 Bit lang (128 Zeichen)
* keine Umlaute (ö,ä,ü,ß)

### Kenntnis der Einheiten Bit, Byte

Das Bit stellt die kleinste Informationseinheit dar, da es nur den Zustand 1 oder 0 einnehmen kann. Ein Byte besteht aus
8 Bit (2^8 = 256).

#### Bullet Points:

* Ein Byte besteht aus 8 Bit

### Kenntnis der Begriffe Gigabyte, Terabyte, Petabyte, Exabyte

| Name Dezimalpräfix | Symbol | Anzahl Bytes | Unterschied | Name Binärpräfix | Symbol | Anzahl Bytes |
|--------------------|--------|--------------|-------------|------------------|--------|--------------|
| Kilobyte           | kb     | 10^2         | 2,4         | Kibibyte         | KiB    | 2^10         |
| megabyte           | MB     | 10^6         | 4,9         | Mebibyte         | MiB    | 2^20         |
| Gigabyte           | MB     | 10^6         | 7,4         | Gibibyte         | GiB    | 2^30         |
| terabyte           | TB     | 10^9         | 10          | Tebibyte         | TiB    | 2^40         |
| Petabyte           | PB     | 10^15        | 12,6        | Pebibyte         | PiB    | 2^50         |
| Exabyte            | EB     | 10^12        | 15,3        | Exibyte          | EiB    | 2^60         |
| Zettabyte          | ZB     | 10^21        | 18,1        | Zebbibyte        | ZiB    | 2^70         |
| Yottabyte          | YB     | 10^24        | 20,9        | Yobbybyte        | YiB    | 2^80         |

### Kenntnis der gebräuchlichen Zahlensysteme in der IT

Der elektronischen Komponenten des Computers arbeiten mit dem Binär-system, da so mit dem Anliegen von Spannung
gerechnet und gespeichert werden kann. Um Zahlen leserlich für Menschen zu machen wird das Hexadecimal System verwendet.
Dieses besteht aus den zahlen 0-9 und danach den Buchstaben A-F. Mit einer Hex Zahl kann somit der ganzzahlige Bereich
von 0-16 dargestellt werden.

#### Bullet Points:

* Binär (Basis 2)
* Octal (Basis 8)
* Hexadecimal (Basis 16)

### Umwandlung zwischen Binär-, Dezimal- und Hexadezimalzahlen

Gehe nach [folgendem Verfahren](https://www.arndt-bruenner.de/mathe/scripts/Zahlensysteme.htm) vor:

(1) Teile die Zahl mit Rest durch 2.  
(2) Der Divisionsrest ist die nächste Ziffer (von rechts nach links).  
(3) Falls der (ganzzahlige) Quotient = 0 ist, bist du fertig, andernfalls nimm den (ganzzahligen) Quotienten als neue
Zahl und wiederhole ab (1)

Beispiel: 420

```
     420 : 2 = 210  Rest: 0
     210 : 2 = 105  Rest: 0
     105 : 2 =  52  Rest: 1
      52 : 2 =  26  Rest: 0
      26 : 2 =  13  Rest: 0
      13 : 2 =   6  Rest: 1
       6 : 2 =   3  Rest: 0
       3 : 2 =   1  Rest: 1
       1 : 2 =   0  Rest: 1

     Resultat: 110100100
```

### Kenntnis der Logik-Schaltungen (AND, OR, XOR, NOT) und deren Wahrheitstabellen

#### NOT

| A | OUT |
|---|-----|
| 0 | 0   |
| 1 | 0   |

#### NAND

| A | B | OUT |
|---|---|-----|
| 0 | 0 | 1   |
| 0 | 1 | 1   |
| 1 | 0 | 1   |
| 1 | 1 | 0   |

#### NOR

| A | B | OUT |
|---|---|-----|
| 0 | 0 | 1   |
| 0 | 1 | 0   |
| 1 | 0 | 0   |
| 1 | 1 | 0   |

#### AND

| A | B | OUT |
|---|---|-----|
| 0 | 0 | 0   |
| 0 | 1 | 0   |
| 1 | 0 | 0   |
| 1 | 1 | 1   |

#### OR

| A | B | OUT |
|---|---|-----|
| 0 | 0 | 0   |
| 0 | 1 | 1   |
| 1 | 0 | 1   |
| 1 | 1 | 1   |