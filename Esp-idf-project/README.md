
# ESP32-S3(ESP-IDF)

This project is to progam the esp32-s3 display using esp-idf platform




## Installation

Install ESP-IDF using the following link(https://github.com/espressif/idf-installer/releases?page=5)

```bash
  1. After installing espidf copy your espidf project to the following path
  "C:\Espressif\frameworks\esp-idf-v4.4.3\examples\get-started"

  2. Open the project into the espidf terminal by entering the command below
        "cd C:\Espressif\frameworks\esp-idf-v4.4.3\examples\get-started\PROJECT"

  3. Then follow the steps which are in the pdf file to configure the workspace according to esp32-s3 hardware, click on the link below
        (https://github.com/rgvkulkarni/ESP32-S3/blob/main/Esp-idf-project/TerminalRGB%20Use%20a%20tutorial.pdf)
  
```
    
## Usage

```bash
    1. After the compilation process connect the esp32-s3 display to the com port and press the BOOT and RESET button respectively to put it in the download mode
    2. Now open the device manager and check on which COM port the device is connected.
    3. Now flash the .bin file into the esp32-s3 device buy entering the below command
        "idf.py -p (COM PORT) flash"
```

