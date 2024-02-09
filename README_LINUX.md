# Welcome Arduino7 Linux 

_Arduino7 Windows_ is a package to start Trace 32 with arduino Portenta H7 in Linux. There are three different ways to debug : GBD, JTAG and Simulator. 


## Fisrt install

After download .zip, you can extract file to **HOME**.


## Start 

Open terminal and use `cd Arduino7` to go in file. 
Use `./Arduino_linux.sh` to open Trace32 Arduino7 in linux.

Now, you can start Simulator and JTAG mode. If you want to use GDB mode, please refer to the next part "Start GBD mode". 

__Warning__ : If you want to debug in JTAG mode, you need probe and licence. Please, refere to [Lauterbach website](https://www.lauterbach.com/).

## Start GDB mode

To debug in GDB mode, you need to procure arduino licence for Trace 32. It's a free license and will be valid for one year. 

To get one, follow these steps : 

1. Please install ArduinoIDE : [install ArduinoIDE](https://www.arduino.cc/en/software).

2. Connect the board and select "Arduino Portenta H7 (M7 core)" "COM** Serial Port (USB)" 

3. In Arduino IDE, select "Tools -> Board : -> Board Manager " and install "Arduino Mbed Os Portenta Board by Arduino" version 4.0.4

4. In Arduino IDE, select "Tools -> GET Board Info" and raise a serial number (SN). 

5. Go to Lauterbach registration page : [Lauterbach.com](https://repo.lauterbach.com/register_arduino.php)
6. Complete the form to get your new license 

7. After you receve your licence keys, open Arduino7 and write `License.state` in command line
8. Clic to button `Save`

**Now, you can use Arduino7 in a GDB mode.** 


## Documentation 
For beging to debug, please refer to file _pdf_ in the folder _Arduino7\TRACE32_.

## Help 

File names should not contain spaces, otherwise the software may not start. 

If you need to install drivers, please open terminal and use`cd Arduino7` to go in file. Then use `./driver_linux.sh` to install drivers.

For more information, please conatact support_fr@lautebabach.com
