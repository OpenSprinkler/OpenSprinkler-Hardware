- Original OS3.0 design uses a PCF8574 (8-channel) IO expander on the main controller and a separate PCF8574 on the driver board.

- OS3.0 revision 1 improved the design by combining the two into a single PCA9555 (16-channel) IO expander. It has also moved the current sensing circuitry to the driver board, to avoid routing it onto the main controller board.
