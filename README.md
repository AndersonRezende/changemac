ChangeMac
==============
Simple Shell Script to change mac address from linux based systems

### Information
Leave some frequently used mac addresses saved or enter a new mac address

### Installation

1. Clone this project with `git clone https://github.com/AndersonRezende/changemac.git`
2. Open terminal and install `$ sudo apt-get install macchanger`
3. Identifying Your Network Card running `$ sudo ifconfig` <br>
It will be something like: <img src="https://user-images.githubusercontent.com/22622758/62907792-581cf380-bd4b-11e9-9cc3-2a6593537fab.png">
4. Change cardname on line 3 to your Network Card name
5. <strong>(This is an optional step)</strong> Change or add frequently used Mac addresses in the `changemac.sh` file in the case structure
5. Copy the `changemac.sh` file to the folder `/usr/bin`

### Running

1. Open terminal
2. Run the script using the command: `$ sudo changemac.sh`
