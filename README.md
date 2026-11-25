# Control LED Button

## Deskripsi

Project Arduino Uno untuk mengontrol
dua LED menggunakan dua push button.
Setiap push button mengontrol satu LED secara independen.

## Hardware

- Arduino Uno
- 2 LED (merah dan hijau)
- 2 Push Button
- 2 Resistor 220 Ohm
- Breadboard
- Jumper Wire

## Pin Configuration

| Komponen | Pin  |
|----------|------|
| LED 1    | D8   |
| LED 2    | D9   |
| Button 1 | D2   |
| Button 2 | D3   |

Kedua push button menggunakan mode `INPUT_PULLUP`,
sehingga satu kaki tombol dihubungkan ke pin digital
dan kaki lainnya ke GND.

## Cara Kerja

- Ketika Button 1 ditekan, LED 1 menyala.
  Ketika dilepas, LED 1 mati.
- Ketika Button 2 ditekan, LED 2 menyala.
  Ketika dilepas, LED 2 mati.
- Kedua tombol dapat ditekan bersamaan,
  sehingga kedua LED menyala bersamaan.

## Simulasi

https://wokwi.com/projects/481659647632291841

## Software

- Arduino IDE
- Wokwi Simulator
- Git
- GitHub

## Developer

hilmyfaiz12