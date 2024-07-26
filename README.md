#Data Retrieval and Analysis with NodeMCU and Python
#Overview
This project involves retrieving data over WiFi using NodeMCU, saving it to a file, and then processing and analyzing the data using Python. The data processing includes extracting specific values, detecting peaks, and calculating metrics like RMSSD (Root Mean Square of Successive Differences) and ln(RMSSD) which indicated using RR intervals.

#Requirements
NodeMCU (ESP8266/ESP32): For data retrieval over WiFi.
Python 3.x: For running the data processing and analysis scripts.
Python Packages: requests, pandas, matplotlib, scipy, numpy. Install these via pip.

#Setup

#NodeMCU Configuration
Configure your microcontroller NodeMCU with MAX30102 sensor to send data to a specified URL. Ensure it sends data in the expected format.

#Python Environment
Install the required packages
pip install requests pandas matplotlib scipy numpy

