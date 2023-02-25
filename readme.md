Forked from https://github.com/adamhochberger/bongocat_mercutio and based off https://github.com/pedker/OLED-BongoCat-Revision

Adds a timer for a longer bong

# FLASHING

This can be flashed using [QMK](https://docs.qmk.fm/#/). 


Replace all of the files in your mercutio QMK directory (`qmk_firmware\keyboards\mechwild\mercutio\`) with the contents of this repo

Then run `qmk flash -kb mechwild/mercutio -km bongocat`

# NOTE

Specifically there are changes to the `mercutio.c` and `config.h` which is why its suggested to copy the entire directory. 