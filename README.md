# Arduino Nano RP2040 Connect Sensor Data Logger
This project is a sensor data logger that uses an Arduino Nano RP2040 Connect board to measure temperature and store the data in a Google spreadsheet. The sensor data is collected every 30 seconds and sent over WiFi to the Google spreadsheet for storage.

## Hardware Requirements
To build this project, you will need the following hardware:
* Arduino Nano RP2040 Connect board
* WiFi router

## Software Requirements
To run this project, you will need the following software:
* Arduino IDE
* Google account for Google Sheets API access
* Google Sheets API key
* WiFi network credentials

## Getting Started
To get started with this project, follow these steps:
* Clone the repository to your local machine.
* Open the 'data_logger.ino' file in the Arduino IDE.
* Set up your Google Sheets API key and WiFi network credentials in the secrets.h file.
* Upload the sketch to the Arduino Nano RP2040 Connect board.
* Verify that the sensor data is being collected and stored in the Google spreadsheet.

## Contributing
If you would like to contribute to this project, feel free to submit a pull request or open an issue on the GitHub repository.
