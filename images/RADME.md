BeagleBone Black
On the BeagleBone Black execute the following commands in a terminal/SSH session on the device:
Download: file
Copy Code

    sudo apt-get update
    sudo apt-get install build-essential python-dev python-smbus python-pip git
    sudo pip install Adafruit_BBIO

You can ignore any warnings about dependencies already being installed.
Installation
Once the dependencies above have been installed you can install the character LCD module by executing the following commands on the device:
Download: file
Copy Code

    cd ~
    git clone https://github.com/adafruit/Adafruit_Python_CharLCD.git
    cd Adafruit_Python_CharLCD
    sudo python setup.py install

These commands will clone the GitHub repository with the library source and then execute the setup.py script to install the library.