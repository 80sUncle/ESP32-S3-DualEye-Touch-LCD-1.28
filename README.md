[中文版](./README_CN.md)

### Arduino
Use under Arduino IDE software:
- `example`: Store examples (directly compilable).
- `libraries`: Store library files (this folder is only used in the Arduino environment!).
  - **Note**: `esp32 by Espressif Systems` must be version 3.2.0 or above! (The current example is based on V3.2.0 programming.)


#### Arduino Example Tools Configuration:
![Arduino Settings](ESP32-S3-DualEye-Touch-LCD-1.28-Arduino-Setting.png)


### ESP-IDF
Used under VSCode software. The samples stored in this folder can be compiled directly. When selecting the project in VSCode, note that you should not select `ESP-IDF` directly, but instead select the project folder *under* `ESP-IDF` (normally named `Serial number_Program name`).
- **Note**: `ESP-IDF` must be version 5.4.0 or above.


### Firmware
Test firmware (burn using "flash_download_tool_3.9.5" at address `0x00`. Remember to check the corresponding box.)


### Additional Note
If compilation succeeds the first time but fails in subsequent tests, re-decompress the folder and compile the new files.


For more product information, please refer to:  
[https://www.waveshare.net/shop/ESP32-S3-DualEye-LCD-1.28.htm](https://www.waveshare.net/shop/ESP32-S3-DualEye-LCD-1.28.htm)