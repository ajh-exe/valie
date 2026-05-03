# A Voice-Controlled, Air-Gapped, and Localized IoT Ecosystem (VALIE)

## Description

_An Internet of Things (IoT) ecosystem designed to be run inside a college dorm with regulations against having a Wireless Access Point (WAP or AP)_

## Key Skills Used
1. Networking
2. Python
3. API calls
4. Web development
5. Web design

_**Note**: Some of this is going to be learned while working on this project_

## Physical Hardware Needed
1. Router with an AP (preferably one with a smaller footprint)
2. IoT devices that operate with _**local**_ internet (preferably ones with API access available)
3. Computer with enough computing power to run speech-to-text models locally
4. A microphone of some kind

## Project Breakdown
As stated in the project description and title, this project is for a voice-controlled, air-gapped, and localized IoT Ecosystem (VALIE). VALIE (pronounced VAL-ee) will be designed with locality in mind; no fancy cloud or internet needed. The goal: A smart, compact, and reliable IoT solution that will work efficiently and effectively, without any internet access. Using fast and reliable speech-to-text software, VALIE will take in user input to control specific smart devices connected to its Local Access Network (LAN) via its integrated WAP. 

User input, in the form of speech-to-text, will then be parsed to determine what smart device is being controlled and what to do with said device. For user friendliness, there will be a web portal that the user can connect to add new devices (as doing so over speech-to-text is not very efficient). This web-based user interface will allow the user to fill in information for each device (i.e., API call formatting, allowed commands, device name, etc.).
