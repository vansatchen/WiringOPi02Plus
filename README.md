# wiringOP README

This is a modified WiringPi for OrangePi. We call it WiringOP.
Test fo Orangepi Zero 2 Plus

## Download
### For Orangepi Pi
    git clone https://github.com/vansatchen/WiringOPi02Plus.git
## Installation
    cd WiringOP
    sudo ./build

```    
orangepi@orangepi:~$ gpio readall
 +-----+-----+----------+------+---+-Orange Pi+---+---+------+---------+-----+--+
 | BCM | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | BCM |
 +-----+-----+----------+------+---+----++----+---+------+----------+-----+-----+
 |     |     |     3.3v |      |   |  1 || 2  |   |      | 5v       |     |     |
 |  12 |   8 |    SDA.0 | ALT5 | 0 |  3 || 4  |   |      | 5V       |     |     |
 |  11 |   9 |    SCL.0 | ALT5 | 0 |  5 || 6  |   |      | 0v       |     |     |
 |   6 |   7 |   GPIO.7 | ALT3 | 0 |  7 || 8  | 0 | ALT3 | TxD3     | 15  | 13  |
 |     |     |       0v |      |   |  9 || 10 | 0 | ALT3 | RxD3     | 16  | 14  |
 |   1 |   0 |     RxD2 | ALT3 | 0 | 11 || 12 | 0 | IN   | GPIO.1   | 1   | 110 |
 |   0 |   2 |     TxD2 | ALT3 | 0 | 13 || 14 |   |      | 0v       |     |     |
 |   3 |   3 |     CTS2 | ALT3 | 0 | 15 || 16 | 0 | ALT3 | GPIO.4   | 4   | 68  |
 |     |     |     3.3v |      |   | 17 || 18 | 0 | ALT3 | GPIO.5   | 5   | 71  |
 |  64 |  12 |     MOSI | ALT3 | 0 | 19 || 20 |   |      | 0v       |     |     |
 |  65 |  13 |     MISO | ALT3 | 0 | 21 || 22 | 0 | ALT3 | RTS2     | 6   | 2   |
 |  66 |  14 |     SCLK | ALT3 | 0 | 23 || 24 | 0 | ALT3 | CE0      | 10  | 67  |
 |     |     |       0v |      |   | 25 || 26 | 0 | ALT3 | GPIO.11  | 11  | 21  |
 |  19 |  30 |    SDA.1 | ALT4 | 0 | 27 || 28 | 0 | ALT4 | SCL.1    | 31  | 18  |
 |   7 |  21 |  GPIO.21 | ALT3 | 0 | 29 || 30 |   |      | 0v       |     |     |
 |   8 |  22 |  GPIO.22 | ALT3 | 0 | 31 || 32 | 0 | ALT5 | RTS1     | 26  | 200 |
 |   9 |  23 |  GPIO.23 |  OUT | 1 | 33 || 34 |   |      | 0v       |     |     |
 |  10 |  24 |  GPIO.24 | ALT3 | 0 | 35 || 36 | 0 | ALT5 | CTS1     | 27  | 201 |
 |  20 |  25 |  GPIO.25 | ALT3 | 0 | 37 || 38 | 0 | ALT5 | TxD1     | 28  | 198 |
 |     |     |       0v |      |   | 39 || 40 | 0 | ALT5 | RxD1     | 29  | 199 |
 +-----+-----+----------+------+---+----++----+---+------+----------+-----+-----+
 | BCM | wPi |   Name   | Mode | V | Physical | V | Mode | Name     | wPi | BCM |
 +-----+-----+----------+------+---+-Orange Pi+---+------+----------+-----+-----+
```    
Thanks!
