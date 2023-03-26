## Introduction
This code is a Python script that extracts IP addresses from a pcap file, and plots their geo-locations on a KML file. It uses the dpkt module to read the pcap file, the socket module to convert IP addresses to human-readable format, and the pygeoip module to determine the geo-location of the IP addresses.

## Installation
To use this code, you need to have Python installed on your machine, as well as the dpkt, socket, and pygeoip modules.

You can install these modules using pip, by running the following command in your terminal:
```bash
pip install dpkt socket pygeoip
```
## Usage
To use this code, you need to have a pcap file that contains network traffic. You can run the code by running the main() function, which reads the pcap file, extracts the IP addresses, determines their geo-locations, and generates a KML file.

To run the code, simply execute the following command in your terminal:
```bash
python pcap-to-kml.py
```
The code will output the KML file to the console, which you can then save to a file using output redirection, like this:
```bash
python pcap-to-kml.py > output.kml
```
This will save the KML output to a file named output.kml in your current directory.

After that we upload our KML file to [https://www.google.com/maps/d/](https://www.google.com/maps/d/)

![alt text](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*rUy66_DRSEgZZirXW76ZxQ.png)
