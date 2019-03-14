# barcode_scanner

Barcode and QRcode scanner

## Getting Started

Designed for linuxOS in mind (Ubuntu and Raspbian), might containerise later...

### Prerequisites

Laptop running ubuntu or RaspberryPi

A webcam

Python3, will be on any linux OS

github, on  linux OS

### Installing

1.open terminal, press together on the keyboard "ctrl+alt+t"

the rest of the instructions involve typing inside the terminal(command line, console ...)

2.git clone https://github.com/jcrich1469/barcode_scanner

3.cd barcode_scanner

4.virtualenv venv

5.source venv/bin/activate

6.pip3 install -r requirements.txt

7.python3 barcode_scanner_video.py
... wait for the camera to display

7.1. get a barcode, it works best when it is flat and close to the camera, with a dark background.
should see a red rectangle and some numbers that match the numbers on the barcode.

8.press "q" on the keyboard to quit and end the program.






