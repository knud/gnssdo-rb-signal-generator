## 10 MHz ref
* use LTC6957 to buffer and clean up FE-5680A signal
## Clock Functions
* Reference output enable/disable - LMK  `1G` pin 2

## FE-5680A Notes
See if the amateur analysis is correct, and if so then

|Pin|Description|
|:--:|--|
|1|+15V - +18V supply voltage
|2|Chassis Ground|
|3|Ttl input. (Control of ttl output)|
|4|+5v supply voltage|
|5|Ground|
|6|TTL output (1PPS)|
|7|10 MHz RF output|
|8|RS232 Rx|
|9|RS232 Tx|

Do we have an AD9832 or AD9830?

## SI5338
* enable/disable outputs independently via UI
* 