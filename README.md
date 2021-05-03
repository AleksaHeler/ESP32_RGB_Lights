# ESP32 RGB light strip

Using WS2801 addressable LED light strip with ESP32 microcontroller and Over The Air (OTA) update to create a portable battery-powered and versatile light bar.

## Usage

Create a new file called ``` credentials.h ```.

In that file copy this code and replace variables:
``` c
const char* ssid = "your_SSID";
const char* password = "your_password";
const char* esp32_password = "your_esp32_OTA_password";
```

Then use Arduino IDE to upload to ESP32.