##20210606_js: initial version 

> Executing task: C:\Users\js\.platformio\penv\Scripts\platformio.exe run <

Processing wemos_d1_mini32 (platform: espressif32; board: wemos_d1_mini32; framework: arduino)
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------Verbose mode can be enabled via `-v, --verbose` option
CONFIGURATION: https://docs.platformio.org/page/boards/espressif32/wemos_d1_mini32.html
PLATFORM: Espressif 32 (3.2.0) > WeMos D1 MINI ESP32
HARDWARE: ESP32 240MHz, 320KB RAM, 4MB Flash
DEBUG: Current (esp-prog) External (esp-prog, iot-bus-jtag, jlink, minimodule, olimex-arm-usb-ocd, olimex-arm-usb-ocd-h, olimex-arm-usb-tiny-h, olimex-jtag-tiny, tumpa)
PACKAGES:
 - framework-arduinoespressif32 3.10006.210326 (1.0.6)
 - tool-esptoolpy 1.30000.201119 (3.0.0)
 - toolchain-xtensa32 2.50200.97 (5.2.0)
LDF: Library Dependency Finder -> http://bit.ly/configure-pio-ldf
LDF Modes: Finder ~ chain, Compatibility ~ soft
Found 49 compatible libraries
Scanning dependencies...
Dependency Graph
|-- <WiFiManager> 2.0.4-beta+sha.a83ac6e
|   |-- <DNSServer> 1.1.0
|   |   |-- <WiFi> 1.0
|   |-- <ESPmDNS> 1.0
|   |   |-- <WiFi> 1.0
|   |-- <Update> 1.0
|   |-- <WebServer> 1.0
|   |   |-- <WiFi> 1.0
|   |   |-- <FS> 1.0
|   |-- <WiFi> 1.0
|-- <bitstore> 1.0.0
|-- <output> 1.0.0
|   |-- <SPI> 1.0
|   |-- <WiFi> 1.0
|-- <signaldecoder> 1.0.0
|   |-- <bitstore> 1.0.0
|   |-- <output> 1.0.0
|   |   |-- <SPI> 1.0
|   |   |-- <WiFi> 1.0
|-- <SimpleFIFO> 1.0.0
|-- <DNSServer> 1.1.0
|   |-- <WiFi> 1.0
|-- <SPI> 1.0
|-- <WiFi> 1.0
|-- <EEPROM> 1.0.3
Building in release mode
Compiling .pio\build\wemos_d1_mini32\src\main.cpp.o
Archiving .pio\build\wemos_d1_mini32\lib656\libWiFi.a
Archiving .pio\build\wemos_d1_mini32\lib123\libDNSServer.a
Compiling .pio\build\wemos_d1_mini32\lib45c\ESPmDNS\ESPmDNS.cpp.o
Compiling .pio\build\wemos_d1_mini32\lib3b1\Update\HttpsOTAUpdate.cpp.o
Compiling .pio\build\wemos_d1_mini32\lib3b1\Update\Updater.cpp.o
Compiling .pio\build\wemos_d1_mini32\liba45\FS\FS.cpp.o
Compiling .pio\build\wemos_d1_mini32\liba45\FS\vfs_api.cpp.o
Compiling .pio\build\wemos_d1_mini32\lib25a\WebServer\Parsing.cpp.o
Compiling .pio\build\wemos_d1_mini32\lib25a\WebServer\WebServer.cpp.o
Compiling .pio\build\wemos_d1_mini32\lib25a\WebServer\detail\mimetable.cpp.o
src\main.cpp: In function 'void loop()':
src\main.cpp:792:7: warning: variable 'state' set but not used [-Wunused-but-set-variable]      
  bool state;
       ^
src\main.cpp: In function 'void send_cmd()':
src\main.cpp:1308:7: warning: variable 'extraDelay' set but not used [-Wunused-but-set-variable]
  bool extraDelay  = false;
       ^
src\main.cpp: In function 'void callGetFunctions()':
src\main.cpp:3023:170: error: 'getFunctions' was not declared in this scope
  getFunctions(&musterDecA.MSenabled, &musterDecA.MUenabled, &musterDecA.MCenabled, &musterDecA.MredEnabled, &musterDecA.MdebEnabled, &LEDenabled, &musterDecA.MSeqEnabled);
                                                                                                                                                                          ^ 
src\main.cpp:3025:11: error: 'getCSvar' was not declared in this scope
  getCSvar();
           ^
Compiling .pio\build\wemos_d1_mini32\libee4\WiFiManager\WiFiManager.cpp.o
*** [.pio\build\wemos_d1_mini32\src\main.cpp.o] Error 1
========================================================================================================================== [FAILED] Took 5.35 seconds ==========================================================================================================================
The terminal process "C:\Users\js\.platformio\penv\Scripts\platformio.exe 'run'" terminated with exit code: 1.

Terminal will be reused by tasks, press any key to close it.
