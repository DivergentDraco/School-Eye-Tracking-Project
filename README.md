# Manual for Eye Tracking

## 2302307 Interactive Science and Social Project (ISSP) AY 2024

[Read about **head** tracking here](https://github.com/DivergentDraco/School-head-tracking-project)

[อ่านฉบับภาษาไทยได้ที่นี่ | You can read the Thai version here](MANUAL_TH.md)

---

# Introduction

Eye tracking technology was taken into development around 100 years ago, though it can be implemented with other users, including those with disabilities. This project has come to the light after we initiated a detailed analysis through observation, interview questions, and surveys throughout the school.

This repository was made specifically for the **Interactive Science and Social Project 
 (ISSP)**, in collaboration with Worcester Polytechnic Institute, USA, that the students studying in Bachelor of Science in Applied Chemistry, Chemistry Department, Faculty of Science, Chulalongkorn University has to accomplish, where Sri Sangwan School is our sponsor. We, students doing this project, are interested in the software called [**Beam Eye Tracker**](https://beam.eyeware.tech/) to utilize it for the gaze bubble to follow with the mouse. 

---

## Members
 * Sean Arackal, *Worcester Polytechnic Institute*
 * Mohamed Adem Djadid, *Worcester Polytechnic Institute*
 * Pawin Harijanwong, *Chulalongkorn University* ([@DivergentDraco](https://github.com/DivergentDraco))
 * Siraphop Homhual, *Chulalongkorn University*
 * Madalyn Nguyen, *Worcester Polytechnic Institute*
 * Marissa Rukachantarakul, *Chulalongkorn University*
 * Bhurinat Sumetchotimaytha, *Chulalongkorn University*
 * Mahit Verma, *Worcester Polytechnic Institute* ([@MaVeryo](https://github.com/MaVeryo))

---

# Project Overview

**Sri Sangwan School** is an institution that provides inclusive education for children with disabilities. Our project mission is to assist them by making insightful research recommendations that will make digital education more accessible. Read more about Sri Sangwan School ([>>here<<](http://www.swn.ac.th/mainpage))

This project focuses on improving the well-being of Sri Sangwan School by providing research recommendations through surveys, interviews, and classroom observations. Later on, we decided to research existing eye-tracking software and modify the existing [**SPK**](https://beam.eyeware.tech/developers/) written by said eye-tracking software developer.

![School Banner](https://github.com/user-attachments/assets/9b123cf6-f919-4abe-b54b-365a5b79b447)

## Our Purpose and Objective
The objective of this project is to try and see methods that can be used within Sri Sangwan School's computer science lab, which houses students that have loss of limb, uncontrollable muscle, or Cerebral Palsy, etc.

## Beam Eye Tracker
Beam Eye Tracker is an eye tracker software that can be used with its existing [SPK](https://beam.eyeware.tech/developers/). Presenting a wide variety of functions, such as gaze tracking, integration with games, etc. The calibration and sensitivity can be controlled within its included UI.

### Coding Language Used
#### To install the program, you will need the programs and files as stated:
##### Required Programs
 - **Beam Eye Tracking** software ([Website](https://beam.eyeware.tech/)) This software is needed to use eye tracking functionalities.
 
 ![Beam Eye Tracker](https://github.com/user-attachments/assets/cd8a1c21-beb4-472f-bc81-7047cefdc76d)
 - Python **3.9.13** ([Website](https://www.python.org/downloads/release/python-3913/))
 - Provided file in the repository

##### Required Equipments
 - **Webcam** is an important equipment for tracking the face. Low quality webcam encouraged with 30 fps laptop webcam is enough.
   Here is the recommendation: Logitech C270 HD which costs around 590 baht.

##### Additional Programs
 - **Optikey** ([Website](https://www.optikey.org/)) This software adds buttons on-screen to help with eye-tracking functionalities. 
(package installer)
![optikeysymbol](https://github.com/user-attachments/assets/2d168696-d3a4-4e59-907e-d575fde42812)

# Demo Video
[Click Here]()

---

# Installation

## Installation video
[Click Here]() 

## Installation Steps
1. Install the following program\
 1.1 Python 3.9.13\
 1.2 Beam Eye Tracker\
 1.3 Code editor (ex. Visual Studio Code)\
2. Install the provided file\
 2.1 Open the file folder, go to the *API* folder, and go to the *Python* folder.\
 2.2 Open **tracker_sample.py**

You should be able to run the code, this should be the following result.

![image](https://github.com/user-attachments/assets/0667cfd6-1fb1-45ea-a366-a7048ac6d0d9)

To establish a connection with the tracker server, you simply need to 

3. Open the **Beam Eye Tracker**\
 3.1 Calibrate your eye tracker by clicking the calibrate button.\
 3.2 Use the alt + z shortcut for calibration to center the cursor.

Your cursor should follow the bubble, from which you are looking.

---

> [!WARNING]
> This particular eye-tracking software costs around 400 baht, which is needed to be able to run the code provided in this GitHub repository.

> [!WARNING]
> This small eye-tracking project is in development progress which does not intend to be implemented due to many factors, such as calibration and sensitivity problems. This project was made to help with recommendation to the school and give other future teams to help with decision-making.



# Encountered Issues
Throughout the project, there are many issues coming up while attempting to use the eye tracking method.

- Eye Fatigue\
 [Issues](https://www.reddit.com/r/MicrosoftFlightSim/comments/1ew95qh/does_anybody_actually_use_eye_tracking/)
Many of eye tracking camera users disabled the eye tracking due to eye fatigue when used, later to use the head tracking function that comes with the software.

- Low Precision\
Experiencing cursor drifts while using the eye tracker

- Head tilt and movement calibration issues\
If the head moves after calibration, the head tracker program may have a hard time centering itself. Students at Sri Sangwan school may have a hard time keeping themselves still.

Should you encounter any problems, please feel free to contact us via Srisangwanissp@gmail.com
