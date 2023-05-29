# Cypto Coprocessor

There are two projects.
1. BPCryptoPIO is based on the https://github.com/PBearson/Provision-ECC608 repository
2. NEWCryptoPIO is based on changes that were required to make the device work with the [PCB version](https://github.com/xinwenfu/SaTC-PCB)

Both should work with PlatformIO without modifications, as the necessary Libraries are located in the **components** folder, and the **.pio/esp32dev** folders.
> Note that **~./platformio/framework/esp-idf** (---------NOT PATH REF Screenshot and provide) was changed as described in the [main readme](./../README.md)

## NOTICE
If the **SaTC-PCB** Version 2 board is being used, the **NEWCryptoPIO** project should be used.