# keyboard_atreus-Layout
The current layout I'm using on the Keyboardio Atreus 

### Journal

*August 12th, 2021*

I wanted to switch around the order of the layers on my keyboard, but there isn't a quick and easy way to do it with QMK Configurator. So I switched the order of the layers in the c file, then converted it to JSON using the following command, before uploading to QMK Configurator. Saved much time.

`qmk c2json -km chasemthomas -kb keyboardio/atreus keymap.c `