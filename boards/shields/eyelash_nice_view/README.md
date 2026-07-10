# eyelash nice!view

This is a local copy of the ZMK `nice_view` shield for the Eyelash Corne right half.
It keeps the stock nice!view status widgets and replaces the peripheral-side art with
a small original 1-bit campfire animation.

This shield requires that an `&nice_view_spi` labeled SPI bus is provided with _at least_ MOSI, SCK, and CS pins defined.

The visible art is designed upright at 68x140, then rotated clockwise into a 140x68
LVGL image because the nice!view panel is mounted vertically on the keyboard.
