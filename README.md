# Control LED Button

## Deskripsi

Project Arduino Uno untuk mengontrol
tiga LED menggunakan tiga push button.
Setiap push button mengontrol satu LED secara independen.

## Hardware

- Arduino Uno
- 3 LED (merah, hijau, dan biru)
- 3 Push Button
- 3 Resistor 220 Ohm
- Breadboard
- Jumper Wire

## Pin Configuration

| Komponen | Pin  |
|----------|------|
| LED 1    | D8   |
| LED 2    | D9   |
| LED 3    | D10  |
| Button 1 | D2   |
| Button 2 | D3   |
| Button 3 | D4   |

Ketiga push button menggunakan mode `INPUT_PULLUP`,
sehingga satu kaki tombol dihubungkan ke pin digital
dan kaki lainnya ke GND.

## Cara Kerja

- Ketika Button 1 ditekan, LED 1 menyala.
  Ketika dilepas, LED 1 mati.
- Ketika Button 2 ditekan, LED 2 menyala.
  Ketika dilepas, LED 2 mati.
- Ketika Button 3 ditekan, LED 3 menyala.
  Ketika dilepas, LED 3 mati.
- Tombol dapat ditekan bersamaan,
  sehingga beberapa LED dapat menyala bersamaan.

## Simulasi

https://wokwi.com/projects/481660578709293057

## Software

- Arduino IDE
- Wokwi Simulator
- Git
- GitHub

## Developer

hilmyfaiz12