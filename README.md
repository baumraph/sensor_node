# sensor_node
## Warning: This board has not been tested yet.

The sensor node is a board for low power wireless sensor networks.
It contains three circuits:

  1. ATMEGA328P-AU (similar circuit to an Arduino Pro Mini)
  2. NCP1402 for stepping up the voltage, which makes it possible to use only one battery.
  3. NRF24L01+ 2.4 GHz RF with external antenna
  
It is also possible to measure the voltage of the battery using pin A0.

Since the board has a similar layout as an Arduino Pro Mini, the Arduino IDE can be used to program the board.
A common library (e.g. RF24NETWORK) can be used for the software side.
