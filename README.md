**Raspberry Pi PicoW as a Bluetooth LE adapter**

This project turns your Raspberry Pi PicoW into an external
Bluetooth LE adapter for your PC.

Using the Serial Bluetooth mobile app, you can input text which is wirelessly 
transmitted over Bluetooth to the PicoW connected to your PC via a USB cable. 
The received data is then saved to a CSV file on your PC using Python.

Specs:
- PC running Windows 10 OS
- Python3 Language 

- Raspberry Pi PicoW running MicroPython
- Mico USB cable

- Mobile phone running Android OS
- Serial Bluetooth App.


Instructions

- Save all the codes in the "PocoW code" folder inside the PicoW.
- Save the code inside the "PC code" folder on your PC.
- Connect your PicoW to your PC via USB cable, the main.py on your Pico will automatically start running and the onboard LED will start blinking.
- Connect your phone to the PicoW using the "Serial Bluetooth app" and the LED should stop blinking and remain still.
- Run the "pc_python_code.py" code on your PC, send a text from your phone and it should display on your python IDE terminal.
- The Python code on your PC should also create a new CSV file each time you restart the Python code on your PC to save the texts sent from your phone.
