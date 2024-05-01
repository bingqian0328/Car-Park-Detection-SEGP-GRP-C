# Car-Park-Detection-SEGP-GRP-C
This is a demonstration code of a camera-based car park detection system developed to analyse video footage to detect the occupancy status of parking spots in a parking lot. Then, the real time data will be uploaded and updated on our front-end application.

To run this system, the backend software will first need to be launched and run for the API to be uploaded onto our applicatiod, followed by the front-end application.

# Steps to run backend code
1) Ensure you have a Python IDE installed. eg. Pycharm
2) Install all the libraries needed to run the code.
   - Opencv
   - cvzone
   - numpy
   - requests
   - pickle
3) Download and open the backend folder on your IDE
4) Run main.py to execute program

## Spaceplotter.py
- This is a file made to mark the parking spots as regions of interest (ROIs) from an image (A screenshot taken from your CCTV parking area footage), left click adds a parking spot and right click deletes a parking spot. Please wait for awhile after adding, it will take some time for it to be saved and created.
- You can modify the parking spots shape by changing the values to suit your parking area's spots. Other types of shape of your choice can also be implemented to fit your parking spots.
- If you need to make changes to a certain spot, take note of the spot_id and change the spot_id_counter variable to the spot id of your choice, then run the code to remark the spot so the spot_id will be in order.

## main.py
- This file executes the program

## Support
This is just a demonstration code of how our backend works, if you need more examples from different carparks or you have problems running the backend code, please feel free to contact hfybl3@nottingham.edu.my (Bing Qian). 

# ParkDetect App Installation and Testing Guide

## Support

For any issues or further assistance, please contact hfyjl22@nottingham.edu.my

## App Testing on Android

1. **Download the ParkDetect APK:**
   - Ensure that you download the ParkDetect APK file to your Android phone.

2. **File Scanning:**
   - If prompted, proceed with scanning the APK file for security.

3. **Launch the Application:**
   - Open the ParkDetect app on your device to begin using it.

## Code Testing with Visual Studio Code and Android Studio

### Setup

1. **Install Necessary Software:**
   - Download and install [Visual Studio Code](https://code.visualstudio.com/).
   - Download and install [Android Studio](https://developer.android.com/studio). Ensure to select the Android Virtual Device component during installation.

2. **Install Extensions in Visual Studio Code:**
   - Install the Flutter and Dart extensions in Visual Studio Code.

### Running the Simulator

1. **Launch Android Studio Virtual Device:**
   - Open the Android Studio and go to the Virtual Device Manager.
   - Launch the virtual device of your choice.

2. **Set Up Project in Visual Studio Code:**
   - Open the `park_detect` folder in Visual Studio Code.
   - If you encounter the 'SDK Not Found' error, follow the Flutter installation guide [here](https://docs.flutter.dev/get-started/install).

3. **Run the Application:**
   - Open the terminal in Visual Studio Code.
   - Execute the command `flutter run` to start the application on the virtual device.

## Support

For any issues or further assistance, please contact hfyjl22@nottingham.edu.my
