# raspberrypi-shutdown-button

Physical connections

On the circuit you will notice the two leads are labeled "in" and "out."
Using the Pi GPIO header diagram at right, connect the "out" lead to GPIO 23 and "in" lead to GPIO 24. If you prefer to use other pins (e.g. GPIO 5 and 6) simply edit the script as discussed later in the setup. Do not connect to a ground or power GPIO pin. GPIO 0 and 1 can sometimes cause issues as well.

- Connect your original Raspberry Pi power source/micro-USB cable into the micro-USB port on the switch.
- Connect dircuit to Pi.
- Press the power button on the circuit and wait for your OS to boot.

## Script setup

- You can use either keyboard input or SSH to install the script for the switch.
- The Pi must have internet access during installation (but not needed after) for setup.

For RaspBMC/Raspbian/Debian distributions (Xbian as well, omit the word sudo), type the following and hit enter after each line:

1. sudo wget http://files.mausberrycircuits.com/setup.sh

2. sudo bash setup.sh

3. sudo reboot
