# Automated Parking System using Machine Learning

An image-based parking management project that detects vehicle license plates and assists in assigning a parking slot based on the detected vehicle.

The project demonstrates a basic computer-vision workflow for processing vehicle images, isolating the license-plate region, and producing detected license-plate results for parking management.

## Overview

The project follows an image-processing workflow to identify a vehicle's license plate and use the detected vehicle information as part of an automated parking system.

The repository contains examples of:

- Vehicle image input
- Image preprocessing
- License-plate region detection
- Processing of multiple vehicle images
- Detected license-plate output
- Parking-system management

## Workflow

```text
Vehicle Image
      |
      v
Image Processing
      |
      v
License Plate Detection
      |
      v
Detected Plate Information
      |
      v
Parking Slot Allocation / Management
```

## Project Demonstration

### Working Code

The following examples show the processing stages used by the project, including the original vehicle image and intermediate image-processing results.

![Working Example 1](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/4aa90b0b-c3a7-4be9-a27a-4190189da4ab)

![Working Example 2](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/6fa6f6cc-f56b-454d-8d5b-5fc7270065d7)

![Working Example 3](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/298c36b3-8ab3-431c-a443-3d054990311c)

![Working Example 4](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/4b8aa77a-aafb-4018-91dc-b2b18d186269)

## License Plate Detection Examples

The project was tested on multiple vehicle images with different license-plate formats.

![Detected Plate 1](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/8d1e37aa-5981-463b-91f5-29429f07f053)

![Detected Plate 2](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/024d020d-4732-4254-8347-2f8794c6fa8e)

![Detected Plate 3](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/ed443e1f-9441-4248-8e6e-097548045e75)

![Detected Plate 4](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/13cf2e5f-d4da-4f9c-bca7-769dc679c4d4)

![Detected Plate 5](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/1ed75a58-509c-488b-996b-9ae5d5e14ca2)

## Parking System Management

The detected vehicle information is used as part of the parking-management workflow.

![Parking System Management](https://github.com/samsaxas/Automated-Parking-System-using-Machine-Learning/assets/120178597/98774135-5602-4a3b-8169-e1673cec193e)

## Technologies

Based on the implementation shown in the project, the main areas involved are:

- Python
- Image processing
- Computer vision
- License-plate detection
- Machine-learning-based parking-system workflow

## How It Works

1. A vehicle image is provided as input.
2. The image is processed to make the license-plate region easier to identify.
3. The license-plate region is detected.
4. The detected plate is highlighted in the output.
5. The detected vehicle information is used in the parking-management process.

## Sample Output

The project produces outputs in which the detected license plate is highlighted on the vehicle image. Several examples are included in this README to demonstrate the results on different vehicles and plate formats.

## Project Purpose

The goal of this project is to explore how image processing and machine learning can be applied to automate part of a parking-management system, particularly vehicle identification through license-plate detection.

## Future Improvements

Possible improvements include:

- More robust detection for different lighting and viewing angles
- Improved handling of blurred or partially occluded license plates
- Support for video or live-camera input
- Automatic parking-slot availability detection
- Database integration for vehicle entry and exit records
- Improved accuracy evaluation using a larger labelled dataset







