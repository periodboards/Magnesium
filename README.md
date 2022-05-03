# Magnesium
My crappy 14-key macropad that contains many mistakes in the design


## Errors
### RGB backlighting doesn't work
Somehow in the many days that I had worked on routing the backlighting, I never noticed that I used the wrong LED footprint and so the leds are on the wrong side of the board

### The WS2812 was wired incorrectly
The power and ground were swapped on the WS2812, and therefore if you want to have underglow you need to use a bodge wire to connect data in to what was data out and rotate all of the LEDs accordingly

