# Assistive Technology Wearable Vest for Persons with Hearing Disability

This repository contains the details of the project titled "Design of an Assistive Technology Wearable Vest for Persons with Hearing Disability." This project was presented at the 10th RSI International Conference on Robotics and Mechatronics (ICRoM 2022) held from Nov. 15-18, 2022, in Tehran, Iran.

## Authors

- Tariq Anwaar [tariq.nitt@gmail.com](mailto:tariq.nitt@gmail.com)
- Arun Srinivasan V K [arunsrinivasan1210@gmail.com](mailto:arunsrinivasan1210@gmail.com)
- Nandha Kizor V [nandhakizorv@gmail.com](mailto:nandhakizorv@gmail.com)
- Navneeth Rajiv [navneethrajiv824@gmail.com](mailto:navneethrajiv824@gmail.com)

## Abstract

People with hearing disabilities face numerous challenges in maintaining independence and personal safety, particularly in outdoor environments where traditional hearing aids may be insufficient or impractical. This project proposes an innovative, cost-effective wearable vest designed to assist individuals with hearing disabilities by detecting potential sources of danger in crowded outdoor settings and alerting the user through vibrations.

## Introduction

Individuals with hearing disabilities often encounter significant barriers in communication and safety. Traditional methods like hearing aids are often expensive and have limitations, especially in noisy or crowded outdoor environments. This wearable vest aims to bridge this gap by providing real-time alerts to users about potential hazards outside their line of vision, thereby enhancing their safety and independence.

## Objectives

The primary objective of this project is to design a system that alerts individuals with hearing disabilities to potential dangers in outdoor environments. Examples include car horns, people calling out to them, or fast-approaching objects. The vest uses a combination of camera and LiDAR sensors to detect these dangers and alerts the user via strategically placed vibration motors.

## Technical Solution and Design

### Detection System

The vest incorporates both camera and LiDAR sensors to detect potential dangers. The data from these sensors are fused to provide a reliable detection system. The camera captures high-resolution images, while the LiDAR provides accurate depth values, overcoming the limitations of using a single sensor type.

### Alert Mechanism

Once a potential danger is detected, the system alerts the user through vibration motors placed around the waist. The intensity and location of the vibrations inform the user about the direction and proximity of the danger, allowing them to take appropriate action.

### System Components

- **LiDAR System:** The RP-LiDAR is used for 3D point cloud generation and detecting objects outside the user's line of vision.
- **Camera Module:** Images captured by the camera are processed using a YOLOv4 object detection model to identify various sources of danger.
- **Vibration Motors:** Strategically placed around the waist, these motors vary in intensity to convey the urgency and direction of the detected danger.

## Results

The proposed design has been tested in various outdoor settings, demonstrating its effectiveness in detecting and alerting users to potential dangers. The use of data fusion between camera and LiDAR sensors has significantly improved the reliability and accuracy of the system.

## Future Work

Future enhancements could include miniaturizing the components for better wearability, improving the battery life, and integrating additional sensors for even more robust detection capabilities.

## Citation

```bibtex
@INPROCEEDINGS{10025278,
  author={Anwaar, Tariq and V K, Arun Srinivasan and V, Nandha Kizor and Rajiv, Navneeth},
  booktitle={2022 10th RSI International Conference on Robotics and Mechatronics (ICRoM)}, 
  title={Design of an Assistive Technology Wearable Vest for persons with Hearing Disability}, 
  year={2022},
  volume={},
  number={},
  pages={347-352},
  keywords={Mechatronics;Wearable computers;Auditory system;Assistive technologies;Hearing aids;Robots;Faces;Wearable devices;Hearing disability;Assistive technology device;Outdoor environments},
  doi={10.1109/ICRoM57054.2022.10025278}}


