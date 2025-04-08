## Hardware 

 - Nucleo-L073RZ
 - 3-digit LCD display (AliExpress: "10PIN TN Positive 3-Digits Segment LCD Panel 3.0V Digital Tube Display")

## How to connect

| Display | Nucleo-PIN | STM32 GPIO | STM32-AF |
|---------|------------|------------|----------|
| 1       | CN7:30     | PA1        | SEG0     |
| 2       | CN10:35    | PA2        | SEG1     |
| 3       | CN10:37    | PA3        | SEG2     |
| 4       | CN10:13    | PA6        | SEG3     |
| 5       | CN10:15    | PA7        | SEG4     |
| 6       | CN7:34     | PB0        | SEG5     |
| 7       | CN10:5     | PB9        | COM3     |
| 8       | CN10:33    | PA10       | COM2     |
| 9       | CN10:21    | PA9        | COM1     |
| 10      | CN10:23    | PA8        | COM0     |

## Hardware modifications required on the Nucleo

Open (i.e. remove resistors) from SB45 and SB14
Close (i.e. short pads) from SB62 and SB63
