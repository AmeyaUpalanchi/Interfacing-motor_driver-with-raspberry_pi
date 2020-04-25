  <h3 align="center">Best-README-Template</h3>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
 * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [License](#license)


<!-- ABOUT THE PROJECT -->
## About The Project

Interfacing L298N Motor Driver Module with Raspberry Pi will allow us to control a DC Motor (in fact, you can control two DC Motors).

When I say control a DC Motor, I mean you can start a motor, stop it, make it rotate in forward direction, backward directions, increase the speed of rotation and also decrease the speed.

For this, I’ll be using the L298N Motor Driver Module

### Prerequisites

1. Raspberry pi with raspbian os installed
2. Motor driver(LM298 or L293D Module & not the IC)
3. Power supply(usually 12v)
4. Female-Female jumper cables

### Installation

1. Make connections as shown in diagram in image
2. Connect the negative wire to raspberry pi zero GND pin
3. Connect the motors to the driver (No polarity you can connect any how...functionality may vary according to the connection)
4. Make a new file in raspberry pi
```sh
sudo nano filename.py
```
5. Paste the code
6. Execute by typing
```sh
python3 filename.py
```
<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

