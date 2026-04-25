- Original AC driver board 3.0 uses PCF8574 (8-channel) IO expander with PNP transistor per channel to drive triac.

- AC driver 3.1 (i.e. revision 1) uses a PCA9555 (16-channel) IO expander.

- AC driver 3.2 (i.e. revision 2) matches master version 3.2 with support for wired Ethernet module.

- AC driver 3.2-updated (revision 3) adds a diode drop on PCA9555's VIN pin for more reliable interface with ESP8266's 3.3V logic.
