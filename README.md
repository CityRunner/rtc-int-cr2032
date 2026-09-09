# CR2032 SSOP MOT version of Necroware's nwX287 RTC module

![pcb](./images/pcb.png)

This is a modified version of Necroware's nwX287 RTC module with the following features:
- It uses a common through-hole CR2032 battery holder instead of a CR1225
- It works with an BQ3285 SSOP-24 RTC IC
- It is locked in Intel mode

For detailed information about the project, please refer to Necroware's original page: https://github.com/necroware/nwX287

## Videos
- Necroware's original video: https://www.youtube.com/watch?v=svPNxILeQEw

## Bill of Materials

Gerber files are published in the releases: https://github.com/scrapcomputing/nwX287.cr2032.ssop.mot/releases

Part | # | Description
-----|---|-----------------------------------------
U1   | 1 | Real-Time Clock BQ3285S SSOP-24
Y1   | 1 | Crystal oscillator 32.768kHz 6pF
BT1  | 1 | CR2032 through-hole battery holder

