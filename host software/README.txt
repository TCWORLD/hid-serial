You need com0com installed and a virtual serial port pair set up to use this.

Once com0com is installed, run this utility and it will connect to a device 
running the HID-Serial software. You can then select one end of the com0com 
port pair in the serial port list, and select the other end in your favourite
serial terminal or other software.



For HIDSerialBridgeTrace.exe:

The window will show you data flowing each way. The top is data coming from 
the serial port, and the bottom is data from the HID-Serial device.

You can use the folliwing keys to perform functions:

'c' = Clear both traces
'p' = Pause displaying of data (will not stop data being transferred)
'q' = Quit the program

If an error is encountered with the device, the program will disconnect from
it and then attempt to reconnect in 2 seconds or so.

There is ~0.5 second lag between data being recieved from the serial port and
being sent to the device as it attempts to group data into blocks of 8.



For HIDSerialBridge.exe:

This is slightly simpler. Enter your COM port name into the text box and click ok.

The indicator on the right shows the status:
RED: COM Port either not found or couldn't be opened
YELLOW: COM Port open, but HID-Serial Device not found or reporting error
GREEN: Both ends of the link are open, data can be transferred.

The keyboard performs the following:

'q' = Quit the program

If an error is encountered with the device, the program will disconnect from
it and then attempt to reconnect in 2 seconds or so.

There is ~0.5 second lag between data being recieved from the serial port and
being sent to the device as it attempts to group data into blocks of 8.