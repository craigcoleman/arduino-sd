# arduino-sd
Arduino SD study.
<pre>
http://arduino.cc/en/Reference/SD

Examples

Datalogger: Log data from three analog sensors to a SD card using the SD library
DumpFile: Read a file from a SD card using the SD library and send it over the serial port
Files: Create and destroy a file on a SD card
ReadWrite: Read and write data to and from a file on a SD card
CardInfo: Get information about a SD car

cc notes:  SD.h and SPI.h are part of the defualt arduino libraries.
<a href ="http://arduino.cc/en/Tutorial/Datalogger" target ="_blank" >http://arduino.cc/en/Tutorial/Datalogger</a>

location of SDh and SPI.h in Linux
[root@vita /]# find -name "SD.h"

find: ‘./run/user/1000/gvfs’: Permission denied
./opt/arduino/libraries/SD/src/SD.h
[root@vita /]# find -name "SPI.h"

./opt/arduino/hardware/arduino/sam/libraries/SPI/SPI.h
./opt/arduino/hardware/arduino/avr/libraries/SPI/SPI.h


</pre>
