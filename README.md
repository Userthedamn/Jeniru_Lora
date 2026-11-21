# Jeniru_Lora
This is a code made to test the distance and the speed of lora wireless communication. It sends the message '✅ LoRa TX Ready!' every two seconds, when it is connected to the other lora device. Other wise it will display 'Initializing LoRa Transmitter...' and if it fails it will display '❌ LoRa initialization failed!'. 

* Remember to match the bandwidth of the other device

| lora-module(PINs) | Arduino(PINs) |
| :---------------: | :-----------: |
| SCK | 6 |
| MISO | 4 |
| MOSI | 5 |
| SS | 7 |
| RST | 0 |
| DIO0 | 1 |

* these are the pins