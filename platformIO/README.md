
# ESP32-S3 Display(Platformio)

This project is used to program the custom UI for the Esp32-s3 Display using Platformio IDE in VS-Code.


## Installation

Follow the below Installation Steps using VS-Code IDE.
Download the VS-Code using below Link
https://code.visualstudio.com/download

```bash
  1. Clone the Project repo into your Local machine using below command
 
        git clone https://github.com/rgvkulkarni/ESP32-S3.git.

  2. Open the "LVGL-RGB" project folder in the VS-Code IDE

  3. In VS-code IDE go to the Extentions section and install the search for the "Python", "PLATFORMIO IDE" package and click on install

  4. Go to PLATFORMIO section in the VS-Code and click on the "Open Project" and Open the PLATFORMIO project folder which we have cloned earlier

  5. Wait untill the libraries mentioned in the "platform.ini" file gets installed, the installation will be automatically started

  6. Here the "Lvgl" and "LovyanGFX" libraries will be installed

```
    
## Usage

```bash
1. After the installation compile the code using the "Build" button on the left bottom side in the VS-Code IDE.

2. After the successfull compilation the .bin file will be created and it is ready to be flashed into the Esp32-s3.

3. Connect the Esp32-s3 display to the com port of your computer and put the device into the boot mode by pressing the BOOT and RESET button respectively.

4. Not press the Upload button which will be at the next to the Build button.

5. After successfull flashing the bin file press the RESET and BOOT button of Esp32-s3 display respectively which will turn the display on and you can see the interacting UI.


```


## Related

Here are some related links

[PlatformIO Guide](https://www.elecrow.com/wiki/index.php?title=ESP_Terminal_3.5-inch_Display_PlatformIO_Tutorial)

