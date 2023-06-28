# License Plate Detector

Using TensorFlow Lite and Pytesseract to identify the license plate text from a microcontroller camera.

## Table of Contents
- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Screenshots](#screenshots)
- [Usage](#usage)
- [Project Status](#project-status)
- [Room for Improvement](#room-for-improvement)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## General Information

I trained a TensorFlow Lite model to detect and place a bounding box on license plates. Then applied Pytesseract in order to get the text from the image.

## Technologies Used

- Tensorflow Lite
- Pytesseract

## Features

- Detect and apply bounding box on license plate
- Somewhat get text from image

## Screenshots

![licenseplate](https://github.com/24GUNV/LicensePlateDetector/assets/38719890/4a6a9d7c-f067-40d3-b5d8-87701b8eb841)
![licenseplate](https://github.com/24GUNV/LicensePlateDetector/assets/38719890/b5a26af9-468d-4fae-a474-d2f729950ad9)
![licenseplate](https://github.com/24GUNV/LicensePlateDetector/assets/38719890/aa564a0b-8f5e-4b01-ab21-22d4be32ed74)

## Usage

Run through the notebook (for now).

## Project Status

Project is: _in progress_

## Room for Improvement

Include areas you believe need improvement / could be improved. Also add TODOs for future development.

Room for improvement:
- OCR more efficient
- Cleaning of the image be better for the OCR

To do:
- Get deployment on microcontroller
- Convert notebook to file format
- Update setup, usage, screenshot section to README

## Acknowledgements

- Dataset of license plate images from [here](https://www.kaggle.com/datasets/andrewmvd/car-plate-detection?resource=download)

## Contact

Created by [@24GUNV](https://github.com/24GUNV) - feel free to contact me!
