# Building your First IoT Application with Flask and MicroPython

> Workshop at Pycon Colombia 2021

Main features of this repository are a flask server and micropython scripts to send data over http requests.

![](static/demo.JPG)

## Installation

Clone the repo
   ```sh
   git clone https://github.com/OscarSantos98/Building_your_First_IoT_Application_with_Flask_and_MicroPython.git
   ```

## Usage example

First you must run flask server either as ```python app.py``` or ```flask run``` Then, you can start sending data from your microcontroller which must be flashed first if your board does not have the proper firmware to run micropython.

You can check more information about the boards that can run Micropython and how to download it in its [website](https://micropython.org/).

## Development setup

### Packages

*Python*
- Flask
- Flask-sqlalchemy

*MicroPython*
- machine
- network
- urequests
- time

### IDE

- Visual Studio Code

*Extension*
- PyMakr Console

### Tools
- Ampy

## Release History

* 1.1.0
    * New database feature.

## Follow me at

Twitter: [@OscarSantosMu](https://twitter.com/OscarSantosMu)  
Instagram: [oscarsantosmu](https://instagram.com/oscarsantosmu)


