# Web-Application-Enumeration-Script
Forked from the original project I developed in conjunction with Mr-Whiskers. 
The original Python script contains most of the basic features and the interface, but got evolved since I wanted to add many more features to the original idea.


### Descrpiton 
This tool is a script that eases the process of running automated testing and enumeration on web applications using my own custom commands and tools. If you wanna modify any of these, please feel free to tweak these to your demands and taste. 

The end goal is to remove instances of manually running and logging some of these, since early web application pentesting involves lots of banner grabbing, configuration analysis and auditing, etc.


### Tools that need to be installed for this script to work.
* nslookup
* DNSrecon
* Nmap
* WhatWeb
* Curl
* Gobuster (Dirbuster can be used as an alternative)
* Nikto
* TLS Scan

### Running the tool

* Download the Web-Application-Enumeration.py file to your local machine
* chmod +x the file
* run - python3 Web-Application-Enumeration.py
* You can send the target URL as parameters. If not, you'll be prompted for the target URL or IP address.
* Use the options if you wanna audit specific ports, use custom output files or switch protocols.

#### Up coming changes I wish to make

* Add a feature to grab java script libaries from web application for further investigation.
* Add virtual hosting enumeration options.
* Add multiple hosts to scan.
