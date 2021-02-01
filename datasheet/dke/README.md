# DKE

| Product No        | Size | Resolution | Driver IC          |
| ----------------- | ---- | ---------- | ------------------ |
| DEPG0154--S800F25 | 1.54 | 152 x 152  | [SSD1680][ssd1680] |
| DEPG0154--U25DF18 | 1.54 | 152 x 152  | UC8251d            |
| DEPG0213--S75AF1C | 2.13 | 250 x 122  | [SSD1675][ssd1675] |
| DEPG0213--S800F41 | 2.13 | 250 x 122  | [SSD1680][ssd1680] |
| DEPG0213--S800F42 | 2.13 | 250 x 122  | [SSD1680][ssd1680] |
| DEPG0213--U25DF22 | 2.13 | 250 x 122  | UC8251d            |
| DEPG0266--S800F1  | 2.66 | 296 x 152  | [SSD1680][ssd1680] |
| DEPG0266--U25DF15 | 2.66 | 296 x 152  | UC8251d            |
| DEPG0270--S800F0  | 2.7  | 296 x 176  | [SSD1680][ssd1680] |
| DEPG0290--S800F6  | 2.9  | 296 x 128  | [SSD1680][ssd1680] |
| DEPG0290--U510F11 | 2.9  | 296 x 128  | UC8251d            |
| DEPG0310--S800F0  | 3.1  | 296 x 168  | [SSD1680][ssd1680] |
| DEPG0370--U253F4  | 3.7  | 416 x 240  | UC8253             |
| DEPG0420--U276F14 | 4.2  | 300 x 400  | UC8276c            |
| DEPG0583--F86BF6  | 5.83 | 648 x 480  | JD79686B           |
| DEPG0583--U790F5  | 5.83 | 648 x 480  | UC8276c            |
| DEPG0584--F86BF0  | 5.84 | 768 x 256  | JD79686B           |
| DEPG0750--U590F33 | 7.5  | 384 x 640  | [UC8159][uc8159]   |
| DEPG0750--U790F32 | 7.5  | 480 x 800  | UC8179             |

[ssd1675]: ../ic-driver/SSD1675B.pdf
[ssd1680]: ../ic-driver/SSD1680.pdf
[uc8159]: ../ic-driver/UC8159.pdf

from <https://solisdisplay.com/dke-e-paper/>

## Product naming strategy (may be)

```plain
DEPG   <-  Prefix
0310   <-  Screen size
x      <-  Color (B = B/W, R = B/W/R, Y = B/W/Y)
x      <-  unknown
x      <-  IC Driver (S = SSD16xx, U = UC82xx, F = JD796xx)
xx     <-  IC Driver suffix two digits
```
