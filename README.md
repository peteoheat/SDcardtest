# SDcardtest

This is a simple command line script to test the suitability of an SD card for running Raspbian on the Raspberry Pi. There is a GUI based speed test available called agnostics. But but installing it requires the desktop to be installed. This project is a command line version meant for those that have a running version of Raspbian OS lite (without the desktop) who don't want to install agnostics and pull in all of the desktop dependencies.

# Dependencies
You first need to install fio which can be done as follows

sudo apt install fio

# How to install.
1. sudo apt-get install fio
2. Clone this repository into /home/pi/sdcardtest
3. chmod 755 /home/pi/sdcardtest/sdtest.sh

# To execute
/home/pi/sdcardtest/sdtest.sh
