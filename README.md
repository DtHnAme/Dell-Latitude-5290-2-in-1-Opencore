#  Dell Latitude 5290 2-in-1

## Specifics

```
- CPU : Intel® Core™ i5-8350U Processor (6M Cache, up to 3.60 GHz)
- Graphics : Intel® UHD Graphics 620
- Sound : Realtek ALC3253 (ALC225)
- Display : 12.3 Inch 1920 X 1280 (WUXGA+) 3:2 10 Points Multi Touch
- Memory : LPDDR3 16GB 2133MHZ (8GB * 2 Dual Channel)
- SSD : Intel 7600p 512GB 
- Wireless : AC8265
- WWAN : dw5811e
- Battery : 42WHr
- OpenCore Version : 0.8.1
```

## UEFI Variables

| Variable              | Offset | Default value  | Desired value   | Comment                                                    |
|-----------------------|--------|----------------|-----------------|------------------------------------------------------------|
| CFG Lock              | 0x52d  | 0x01 (Enabled) | 0x00 (Disabled) | Disable CFG Lock to prevent MSR 0x02 errors on boot        |

## HiDPI
For a fhd display, use [one-key-hidpi](https://github.com/xzhih/one-key-hidpi)

## What's working

* USB/C Hot-plug
* Mic, speakers and headphones
* CPU Power Management
* HiDPI
* Bluetooth and Wifi
* Touchscreen
* Battery readouts
* I2C touch screen Up to 5 points Gesture action (recognized as Magic Trackpad 2)
* PS2 Keyboard (Dell Latitude 2-in-1 Travel Keyboard) with Backlight
* Touchpad (Travel Keyboard, recognized as mouse)
* Volume button, window button(Option Key), power button(Sleep/Power Key)

## Issues

- Thunderbolt 3 not working

- MicroSD slot not working properly  

- I2C front and rear camera (AVStream2500, OV5670, OV8858) not recognized
