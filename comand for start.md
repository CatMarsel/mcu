export PICO_SDK_PATH=~/Repositories/pico/pico-sdk
cmake -G "Unix Makefiles" ..

make

wmem D0000014 2000000 - включить LED (SET бит 25)
wmem D0000018 2000000 - выключить LED (CLR бит 25)

screen /dev/tty.usbmodem14201

