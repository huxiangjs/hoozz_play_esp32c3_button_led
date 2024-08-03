# ESP32-C3 BUTTON LED
A low-cost button LED.

This is a sub-repository, and the main repository is located at [Hoozz Play](https://github.com/huxiangjs/hoozz_play)

## Basic environment
MCU:
```
idf.py --version
ESP-IDF v5.2.1-76-gbf17be96b4-dirty
```
Circuit:
```
Altium Designer 18.1.9
```

## Pull source code
```shell
git clone https://github.com/huxiangjs/hoozz_play_esp32c3_button_led.git
cd hoozz_play_esp32c3_button_led
git submodule update --init --recursive
```

## Compile and burn from source code
```shell
cd MCU/
idf.py build && idf.py flash
```

