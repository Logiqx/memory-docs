### WIP

| System   | # <br/> Words | Cards / <br/> Letter | Letters / <br/> Image | Cards / <br/> Image | # <br/> Loci |
|:--------:|:-------:|:--------------:|:---------------:|:-------------:|:------:|
| Tutorial | 8  | 3 | 1 | 3 | 9 |
| 4-bit    | 16 | 2 | 2 | 4 | 5 |
| 6-bit    | 64 | 3 | 2 | 6 | 4.5 |
| 8-bit    | 256 | 4 | 2 | 8 | 3 |


### Colours

| System | Format | # Images | # Loci | Flipping |
|:------:|:-------|:--------:|:------:|:--------:|
|  4-bit | (2+2 + 2+2) * 6 + (2+2) | 13 | 6.5 | Alternate |
|  5-bit | (3+2+1 + 3+2+1) + (3+2 + 3+2) * 4| 10 | 5.0 | Alternate-ish |
|  6-bit | (3+3+1 + 3+3) x 4 | 8 | 4.0 | Dependant |
|  7-bit | (4+3+1 + 4+3) x 3 + (4+3) | 7 | 3.5 | Dependant |
|  8-bit | (4+4 + 4+4) x 3 + (4+0) | 7 | 3.5 | Alternate |

All of the above are for 52 cards, 2 images per locus.

### Ranks

| Ranks | System | # Cards | # Images | # Loci |
|:------:|:-----:|:-------:|:--------:|:------:|
| 1 - 7 | 6-bit | 28 | 14 | 7 |
| 1 - 10 | Decimal | 40 | 20 | 10 |
| 1 - King | Tridecimal | 52 | 26 | 13 |

All of the above are for 2 images per locus.

### Cards

System | # Cards | # Images | # Loci |
|:-----:|:-------:|:--------:|:------:|
Hexadecimal | 51 | 34 | 17 |

The above is for 2 images per locus.

### Simple System

TODO - link to article on artofmemory


### 4-Bit System

This is only an introductory system requiring only 16 words / images.

Each image represents 4 cards and 13 images are required for the entire pack.

e.g. B B + R B = S + N = SuN

| Binary <br/> Digits | Card <br/> Colours | Consonant <br/> Sound(s) |
|:-:|:-:|:-:|
| 00 | B B | s, soft-c, z  |
| 01 | B R | t |
| 10 | R B | n |
| 11 | R R | m |


### Probabilities

Copied from scrap of paper from Cornwall.

| System | Mnemonics | Type | Images | p2 | p3 |
|:------:|:---------:|:----:|:------:|---:|---:|
| 4-bit |  32 | Colours | 13 |  94.14 |  20.95 |
| 4-bit |  32 | Suits   | 26 | 100.00 |  85.05 |
| 4-bit |  32 | Cards   | 78 | 100.00 | 100.00 |
| 6-bit | 128 | Colours |  8 |  20.00 |   0.33 |
| 6-bit | 128 | Suits   | 18 |  71.46 |   4.50 |
| 6-bit | 128 | Cards   | 52 | * 0.00 | * 0.00 |
| 7-bit | 256 | Colours |  7 |   7.94 |   0.05 |
| 7-bit | 256 | Suits   | 13 |  26.64 |   0.42 |
| 7-bit | 256 | Cards   | 39 |  95.27 |  11.94 |

All systems use alternative images so double the number of mnemonics.

* p2 = Probability of 2 or more images being the same
* p3 = Probability of 3 or more images being the same

6-bit cards can never clash because the cards are all unique

Computed using [WolframAlpha](https://www.wolframalpha.com/input/?i=birthday+paradox,+13+people,+32+possible+birthdays)


### Early Ideas

Progression for binary / colours:

* 4-bit
* 5-bit / Psuedo 6-bit
* 6-bit
* 7-bit / Pseudo 8-bit
* 8-bit

**Progression for binary + decimal:**

| System | Mnemonics | Breakdown | Extra |
|:------:|:---------:|:---------:|:-----:|
| 4-bit       |  16 | 4 * 4           |     - |
| 6-bit       |  64 | 8 * 8           |   +48 |
| Decimal     | 100 | 10 * 10         |   +36 |
| Decimal +   | 148 | 10 * 10 + 8 * 6 |   +48 |
| Hexadecimal | 256 | 16 * 16         |  +108 |

Note: 108 = 36 * 3

**Progression for card ranks:**

| System | Mnemonics | Breakdown | Extra |
|:------:|:---------:|:---------:|:-----:|
| 4-bit       |  16 | 4 * 4      |     - |
| 6-bit       |  64 | 8 * 8      |   +48 |
| Decimal     | 100 | 10 * 10    |   +36 |
| Tridecimal  | 169 | 13 * 13    |   +69 |
| Hexadecimal | 256 | 16 * 16    |   +87 |
