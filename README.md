# Signal_ESP32
This Version was forked from Ralf9's version @  https://github.com/Ralf9/SIGNALDuino/tree/dev-r420_cc1101 

and ported to VSCode + Platformio.

For a successful compile were to be done some cosmetics and correct other issues. ;-(

## Changes:
* WifiManager, with factory-reset over serial 

## Status:
### 20210606: ###
*Compile: Failed.*
\lib\signalDecoder\src\signalDecoder4.cpp: At global scope:
d1_lib\signalDecoder\src\signalDecoder4.cpp:62:1: error: redefinition of 'SignalDetectorClass::SignalDetectorClass()'
SignalDetectorClass::SignalDetectorClass(): first(buffer), last(NULL), sd_message(4) 




