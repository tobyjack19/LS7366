# LS7366
An Arduino library to interface to the LS7366 quadrature encoder counter or Mikroe Counter Click board.

4 Pins to connect for the chip / board:

    Chip Select (CS) - Defined in .ino file (See example (D10 used))

    SPI Clock SCK - Will be a specific pin for the given board, for Arduino Uno / Nano this is D13

    SPI Data Out (MISO (Master In Slave Out)) - Will be a specific pin for the given board, for Arduino Uno / Nano this is D12

    SPI Data In (MOSI (Master Out Slave In)) - Will be a specific pin for the given board, for Arduino Uno / Nano this is D11


To install this library via arduino IDE:

    Sketch > Include Library > Add .ZIP Library... > (Locate and select Zip folder)
