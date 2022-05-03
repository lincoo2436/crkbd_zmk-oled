CRKBD ZMK firmware with working RGB and OLEDs for Nice Nano V2 controllers.

Shield: Corne 
Board: Nice!Nano V2
Keymap: Qwerty - 4 layer: default, raise, lower, adjust
OLED: Yes
RGB:  Yes
Bluetooth: Yes
USB: Yes 

NiceNanos are soldered face down (showing black silk screen up and led under)

SDA  - 17
SCC  - 20
ROW0 - 22
ROW1 - 24
ROW2 - 32 // (p01.00) = p(01)*32 + 00
ROW3 - 11


MOSI - 06
trrsDATA? - 08
COL1 - 31
COL2 - 29
COL3 - 2
COL4 - 47
COL5 - 45
COL6 - 43

BLED - 15

corne.conf - basic config settings - name, led, oled
corne.keymap - keylayout
nice_nano_v2.overlay - define spi for rgb underglow
oled.dtsi - define OLED display

updated West.yaml to point to 
petejohanson:core/peripheral-behavior-invocation

-- this allows left and right to sync across bluetooth. 

Note:

I am not presently running this on battery as I am still waiting on LIPO Batteries to arrive via post. 