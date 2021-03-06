# transceiver

RF transceiver related bookmark

## RF transceiver ICs (baseband I/O)

| device | F<sub>min | F<sub>max | BW<sub>min | BW<sub>max | ADC IQ | DAC IQ | Package | $ | Datasheet | Interface |
|--------|-----------|-----------|------------|------------|--------|--------|---------|---|-----------|-----------|
| AD9361 | 70M | 6G | 200K | 56M | 2x12 | 2x12 | 144CSP | | [analog.com](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9361.pdf) | P |
| AD9363 | 325M | 3.8G | 200K | 20M | 2x12 | 2x12 | 144CSP | [118](https://www.digikey.com/product-detail/en/analog-devices-inc/AD9363ABCZ/AD9363ABCZ-ND/6566180) | [analog.com](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9363.pdf) | P |
| AD9364 | 70M | 6G | 200K | 56M | 1x12 | 1x12 | 144CSP | [175](https://www.digikey.com/product-detail/en/AD9364BBCZ/AD9364BBCZ-ND/4747823) | [analog.com](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9364.pdf) | P |
| AD9371 | 300M | 6G | 8M | 100M | 2x12 | 2x12 | 196CSP | [340](https://www.digikey.com/product-detail/en/analog-devices-inc/AD9371BBCZ/AD9371BBCZ-ND/6163959) | [analog.com](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9371.pdf) | JESD204B |
| AD9375 | 300M | 6G | 8M | 100M | | | 196CSP | 325 | [analog.com](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9375.pdf) | JESD204B |
| LMS6002D | 300M | 3.8G | 1.5M | 28M | 1x12 | 1x12 | 120DQFN | [35](http://www.digikey.com/product-detail/en/lime-microsystems-ltd/LMS6002DFN/1434-1000-1-ND/4177113) |[docs](https://github.com/myriadrf/LMS6002D-docs) | P |
| LMS7002M | 100K | 3.8G | 1.5M | 56M | 2x12 | 2x12 | 261aQFN | [110](https://www.digikey.com/products/en/rf-if-and-rfid/rf-transceiver-ics/879?k=LMS7002M) |[docs](https://github.com/myriadrf/LMS7002M-docs) | JESD207 |

## Full RF transceiver ICs

| device | F<sub>min | F<sub>max | bps<sub>min | bps<sub>max |  Package | $ | Datasheet |
|--------|-----------|-----------|-------------|-------------|----------|---|-----------|
| ADF7030-1 | 169M | 960M | 100 | 360K | 48LQFP | [5](https://www.digikey.com/product-detail/en/analog-devices-inc/ADF7030-1BCPZN/ADF7030-1BCPZN-ND/6163961) | [analog.com](http://www.analog.com/media/en/technical-documentation/data-sheets/ADF7030-1.pdf) |
| cc1125 | 169M | 950M | | | 32VQFN | | [ti](http://www.ti.com/lit/ds/symlink/cc1125.pdf) |
| cc1350 | 300M | 2.4G | | | 48VFQFN | 9 | [ti](http://www.ti.com/lit/ds/symlink/cc1350.pdf) |

## IF ADC/DAC ICs

| device | F<sub>min | F<sub>max | BW<sub>min | BW<sub>max | ADC IQ | DAC IQ | Package | $ | Datasheet |
|--------|-----------|-----------|------------|------------|--------|--------|---------|---|-----------|
| MAX5864 | | | | 10M | 1x8 | 1x10 | 48QFN | [9](http://www.digikey.com/product-detail/en/maxim-integrated/MAX5864ETM%2B/MAX5864ETM%2B-ND/1779247) | [maxim](https://www.maximintegrated.com/en/products/analog/data-converters/analog-front-end-ics/MAX5864.html) |
| MAX1003 | | | | 90M | 2x6 | | TSSOP-36 | [8](https://www.digikey.com/short/q7t351) | [maxim](http://datasheets.maximintegrated.com/en/ds/MAX1003.pdf) |
| ADS4145 | | | |     |     | |          | [62](https://www.digikey.com/short/qtd9qq) | [ti](http://www.ti.com/lit/ds/symlink/ads4145.pdf) |

## ADC

| device   | Fs  | bit  | Interface | Package | $ | Datascheet |
|----------|-----|------|-----------|---------|---|------------|
| ADC1613D | 125 | 2x16 | JESD204A  | HVQFN56 | [20](https://www.digikey.com/short/qq1j1c) | [idt](http://www.idt.com/document/dst/adc1613d-ser-datasheet) |
| ADC16DV160 | 160 | 2x16 | LVDS | VQFN68 | [100](https://www.digikey.com/short/qq1pj9) | [ti](http://www.ti.com/lit/ds/symlink/adc16dv160.pdf) |
| ADC32J44 | 125 | 2x14 | JESD204B | VQFN48 | [50](https://www.digikey.com/short/qq1pn7) | [ti](http://www.ti.com/product/ADC32J44/datasheet) |
| ADS42JBx9  | 250 | 2x16 | JESD204B | VQFN64 | [208](https://www.digikey.com/short/qq1pzv) | [ti](http://www.ti.com/lit/ds/symlink/ads42jb69.pdf) |
| ADS5562 | 80 | 16 | LVDS | VQFN48 | [70](https://www.digikey.com/short/qq1pvz) | [ti](http://www.ti.com/lit/ds/symlink/ads5562.pdf) |
| AD9467  | 250 | 16 | LVDS | LFCSP72 | [175](https://www.digikey.com/short/q83dmz) | [adi](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9467.pdf) |
| AD9655 | 125 | 2x16 | LVDS | LFSCP32 | [210](https://www.digikey.com/short/q830jj) | [adi](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9655.pdf) |
| AD9653 | 125 | 4x16 | LVDS | LFSCP3248 | [344](https://www.digikey.com/short/q830p8) | [adi](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9653.pdf) |
| AD9656 | 125 | 4x16 | JESD204B | LFSCP56 | [355](https://www.digikey.com/short/q8308m) | [adi](http://www.analog.com/media/en/technical-documentation/data-sheets/AD9656.pdf) |
| MCP37D31 | 200 |   16 | P, LVDS   | TFBGA-121 | [100](https://www.digikey.com/short/qq1p31) | [microchip](http://ww1.microchip.com/downloads/en/DeviceDoc/20005322D.pdf) |



## DAC

## bookmarks

https://github.com/gnuradio

http://gqrx.dk/

https://github.com/EttusResearch

https://github.com/myriadrf

http://sdr.osmocom.org

https://github.com/mossmann/hackrf

http://www.analog.com/media/en/technical-documentation/technical-articles/JESD204B-Survival-Guide.pdf

https://www.csun.edu/~skatz/katzpage/sdr_project/sdr/

