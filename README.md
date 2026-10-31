

# VR-Based Yoga Posture Detection, Classification and Correction

A computer vision and virtual reality project developed to identify yoga postures and provide feedback on body alignment.

## About the Project

Practicing yoga without an instructor can make it difficult to determine whether a posture is being performed correctly. This project explores the use of computer vision and virtual reality to make yoga practice more interactive and provide guidance on posture alignment.

The system uses image capture and computer vision techniques to detect body landmarks, analyze joint angles, and classify selected yoga poses. Based on the detected posture, voice feedback is provided to help users understand and correct their alignment. A virtual reality environment is also used to visualize yoga poses and support an interactive practice experience.

The project combines embedded hardware, image processing, posture analysis, and VR technologies as part of an academic project in Mechatronics Engineering.

## Objectives

- Detect and classify selected yoga postures using computer vision.
- Identify body landmarks and calculate relevant joint angles.
- Provide voice feedback to guide posture correction.
- Integrate camera-based image capture with the posture detection system.
- Explore VR-based visualization for interactive yoga practice.

## Yoga Poses

The project focuses on the following yoga postures:

- Bridge Pose
- Mountain Pose
- Downward Dog
- Warrior II

## Technologies Used

| Component | Technology |
|---|---|
| Image capture | ESP32-CAM |
| Hardware interface | Arduino |
| Programming language | Python |
| Image processing | OpenCV |
| Pose estimation | MediaPipe |
| Posture assessment | Joint-angle calculations |
| VR visualization | Unity |
| IoT integration | Blynk |
| User feedback | Voice instructions |

## System Workflow

1. **Image capture:** The ESP32-CAM captures images of the user performing a yoga pose.
2. **Pose estimation:** Python, OpenCV, and MediaPipe are used to identify body landmarks.
3. **Posture analysis:** Joint angles are calculated and used to assess the detected posture.
4. **Classification:** The posture is classified based on the defined conditions.
5. **Feedback:** Voice instructions guide the user toward improved alignment.
6. **VR visualization:** Yoga poses are displayed in a Unity-based virtual environment.

## Repository Structure

This repository contains the complete project code in a single Python file.

```text
VR-Based-Yoga-Posture-Detection/
├── README.md
├── Yoga_Pose_detection_and_Classification.py
└── Research Paper
```

The Python file contains the main implementation for the project. The `results/` folder can be used to store sample input images, output images, and demonstration screenshots.

## Getting Started

### Requirements

- Python 3
- Required Python libraries used by the project
- A webcam or the project's camera hardware, depending on the code configuration
- ESP32-CAM and Arduino hardware for the camera-based setup
- Unity and a compatible VR setup for the VR component

### Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/VR-Based-Yoga-Posture-Detection.git
cd VR-Based-Yoga-Posture-Detection
```
### Running the Code

Run the main Python file:

```bash
python yoga_posture_detection.py
```

Replace `yoga_posture_detection.py` with the actual filename if it is different. Camera and hardware settings may need to be configured based on your setup.

## Results

The `results/` folder can contain sample images and screenshots showing the posture detection and feedback process.

The results demonstrate the project implementation and should be understood as a posture-guidance prototype rather than a replacement for professional yoga instruction.

## Research Publication

The project was presented in the research paper:

**“VR-Based Yoga Posture Detection, Classification and Correction”**

Published in *ICTACT Journal on Data Science and Machine Learning*, Volume 6, Issue 3, June 2025, pages 829–834.

- **Authors:** G. Manisha, N.A. Meenakshi, S. Srinithi, Rajalakshmi Murugesan, and S.A.R. Sheikh Mastan
- **DOI:** 10.21917/ijdsml.2025.0166
- **Published paper:** [Read the paper (PDF)](https://ictactjournals.in/paper/IJDSML_Vol_6_Iss_3_Paper_5_829_834.pdf)

## Limitations

- Detection performance depends on camera placement and visibility of body landmarks.
- Joint-angle thresholds may not account for differences in individual flexibility and body structure.
- The system is intended for posture guidance and demonstration.
- Further testing is required to evaluate performance across different users and environments.

## Authors

- G. Manisha
- N.A. Meenakshi
- S. Srinithi


