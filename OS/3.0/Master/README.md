- Original OS 3.0 design uses a PCF8574 (8-channel) IO expander on the main controller and a separate PCF8574 on the driver board.

- OS 3.1 (i.e. revision 1) improved the design by combining the two into a single PCA9555 (16-channel) IO expander. It has also moved the current sensing circuitry to the driver board, to avoid routing it onto the main controller board.

- OS 3.2 (i.e. revision 2) supports wired Ethernet module by adding a 2x5 connector to be linked to a ENC28J60 module, and it changed GPIO pin assignments in order to free up SPI pins for the Ethernet module.
