# ESP32_GifPlayer

Play Gifs from SD card on a ST7735 display with an esp32 microcontroller

## Wiring:

### [SD-Card holder:](https://de.aliexpress.com/item/1005006005013220.html?spm=a2g0o.order_list.order_list_main.26.21ef5c5fhjewSS&gatewayAdapt=glo2deu)

| SD    | ESP32    |
| ----- | -------- |
| GND   | GND      |
| 3.3V  | 3.3V     |
| 5V    | Not used |
| SD_CS | D5       |
| MOSI  | D23      |
| SCK   | D18      |
| MISO  | D19      |
| GND   | GND      |


### [TFT Display:](https://de.aliexpress.com/item/1005003797803015.html?spm=a2g0o.order_list.order_list_main.75.21ef5c5fhjewSS&gatewayAdapt=glo2deu)

| ST7735 | ESP32 |
| ------ | ----- |
| GND    | GND   |
| VCC    | 3.3V  |
| SCL    | D18   |
| SDA    | D23   |
| RES    | D4    |
| DC     | D2    |
| CS     | D17   |
| BLK    | 3.3V  |
