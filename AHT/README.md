# AHT
This is based on the ESP32 [DHT Lab](https://github.com/xinwenfu/tst-dht-lab), with modifications made so the AHT humidity and temperature sensor works. 

There are **two** PlatformIO projects in this folder
1. [AHT_Component](./AHT_Component) utilizes a method of including all components in a **./components** folder as described in the [main readme](../README.md)
2. [AHT_PIO_Packages](./AHT_PIO_Packages/) utilizes a method of including all components in the **~/.platformio/packages/*/components** that is described in the [main readme](../README.md) 
    * If you have pulled this repository, since the [./pio](AHT/AHT_Component/.pio) directory has already been created you will should not need any modifications to the **.platformio** directory or subdirectories
