# Forget the readme, if you have python3 setup properly with virtualenv etc....

# barcode_scanner

Barcode and QRcode scanner

## Getting Started

Designed for linuxOS in mind (Ubuntu and Raspbian), might containerise later...

### Prerequisites

Laptop running ubuntu or RaspberryPi

A webcam

Python3, will be on any linux OS (Raspbian OS included on as linux)

github, should already be on  linuxOS

### Installing

1.open terminal, press together on the keyboard "ctrl+alt+t"

the rest of the instructions involve typing inside the terminal(command line, console ...)

2. sudo apt-get install libzbar0

3. git clone https://github.com/jcrich1469/barcode_scanner

4. cd barcode_scanner

5. sudo pip3 install virtualenv

6. virtualenv venv

7. source venv/bin/activate

8. pip3 install -r requirements.txt

9. python3 barcode_scanner_video.py
... wait for the camera to display

9.1. get a barcode, it works best when it is flat and close to the camera, with a dark background.
should see a red rectangle and some numbers that match the numbers on the barcode.

10.press "q" on the keyboard to quit and end the program.






