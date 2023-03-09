# TchiBot.Epd4in2b_V2
E-Paper library for the [TchiBot](https://github.com/Alex-451/TchiBot) project

## Waveshare
This is a copy of the [Waveshare library](https://github.com/waveshare/e-Paper/tree/master/Arduino) with a few minor edits for the [4.2inch e-Paper Module](https://www.waveshare.com/product/displays/e-paper/epaper-2/4.2inch-e-paper-module-b.htm) and only exists so I can easily import the library using PlatformIO

## ESP8266
The pin definitions in `include/epdif.h` have been updated so the library works with my [ESP8266:](https://www.az-delivery.de/en/collections/esp8266/products/nodemcu-lolin-v3-modul-mit-esp8266)
```C++
#define RST_PIN         4   // D2
#define DC_PIN          5   // D1
#define CS_PIN          15  // D8
#define BUSY_PIN        2   // D4
```

