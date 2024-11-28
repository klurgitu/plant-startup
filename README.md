## Welcome

begining of the plant start up
we really need a name guys


to flash ESP32-WROOM

plug it in via USB

clone this repo

`cp -r ./esp-idf/examples/getting-started/hello-world/ ./`

`cd hello-world`

`. ../esp-idf/export.sh`

`idf.py set-target esp32`

`idf.py menuconfig` <-- buildroot menuconfig for freeRTOS, can set config options like wifi ssid and stuff in there

`idf.py build` 

`idf.py -p /dev/ttyUSB0 flash` -p == PORT

`idf.py -p /dev/ttyUSB0 monitor` basically minicom`

tada you flashed it
