# AtumFlight V1

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/Atum.svg/1200px-Atum.svg.png" width="250">

## About
This project will be used to create and program an STM32 chip in conjunction with various sensors to create a working flight computer. The goal of this project is to create an accurate flight computer for as cheap as possible, using commercially available parts. Along with the flight computer we want to create software to accompany the flight computer to allow for tracking and visualization like other commerical software. The name Atum comes from the Egyptian God of the universe, his name also means to complete or finish.

## Details
Flight software will be written in C/C++ through the STM32CubeIDE software. The schematic and PCB will be designed using KiCAD due to it's easy accessibility for all being free and open-source. 

This flight computer will be running at 120MHz with communication protocols like SPI, I2C, and Serial Wire Debug. We will have an IMU for gyro and under 16G accelerometer data, a 100G accelerometer for high G flights and a barometer for barometric pressure reading. 

For communication and GPS we are using a UBLOX GPS system and a TI CC1200 transciever for communication for flight data through a Yagi antenna on the 70cm frequency band. 

Our flight computer will have 3 pyrotechnic channels to allow for dual deploy and two stage rocket designs. It will also contain an extra I2C and SPI output for further upgrades in the future.

## References
Stay tuned for the website being built for the project!!

Dylan Gore 7/1/22
