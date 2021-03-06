# Temperature sensor operation

The temperature value how to converted to hex as the follow:

1. if the temperature value MSByte bit `D11 = 0`, then
   <br>The temperature is positive and value (&#8451;) = `+(temperature value) / 16`

2. if the temperature value MSByte bit `D11 = 1`, then
   <br>The temperature is negative and value (&#8451;) = `~(2's complement of temperature value) / 16`

| 12 bit binary    | value |  value |   &#8451; |
| ---------------- | ----: | -----: | --------: |
| `0111 1111 0000` | `7F0` | `2032` | `127.000` |
| `0111 1110 1110` | `7FE` | `2030` | `126.875` |
| `0111 1110 0010` | `7F2` | `2018` | `126.125` |
| `0111 1101 0000` | `7D0` | `2000` | `125.000` |
| `0001 1001 0000` | `190` |  `400` |  `25.000` |
| `0000 0000 0010` | `002` |    `2` |   `0.125` |
| `0000 0000 0000` | `000` |    `0` |   `0.000` |
| `1111 1111 1110` | `FFE` |   `-2` |  `-0.125` |
| `1110 1111 0000` | `E72` | `-400` | `-25.000` |
| `1100 1001 0010` | `C92` | `-878` | `-54.875` |
| `1100 1001 0000` | `C90` | `-880` | `-55.000` |

from `GDEH0213B1` (page 10 of 29)
