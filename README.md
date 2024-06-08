<h1 align="center">Gesturesflow (Virtual Mouse)</h1>

## :bookmark_tabs:Table of contents
* [Project info](#Project-info)
* [Features](#Features)
* [Tools and Technologies](#Tools-and-Technologies)
* [Setup](#setup)

## Project info

The Gesturesflow (Virtual Mouse) is designed to enable users to control their computer's mouse pointer through hand gestures. This system uses a camera to capture the user's hand movements and translates the coordinates of the fingertip to the full-screen computer window, allowing for an intuitive and touch-free interaction with the computer.

## Features
---
 **_click on dropdown for demo photo_** <br>

<details>
<summary>Neutral Gesture(Palm)</summary>
 <figure>
  <img src="Media/minor FINAL.pdf-image-033.jpg" alt="Move Cursor" width="452" height="390"><br>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>
 

<details>
<summary>Move Cursor(Peace Sign)</summary>
  <img src="Media/minor FINAL.pdf-image-034.jpg" alt="Move Cursor" width="452" height="390"><br>
  <figcaption>Cursor is assigned to the midpoint of index and middle fingertips. This gesture moves the cursor to the desired location. Speed of the cursor movement is proportional to the speed of hand.</figcaption>
</details>

<details>
<summary>Left Click(Index Finger)</summary>
<img src="Media/minor FINAL.pdf-image-035.jpg" alt="Move Cursor" width="452" height="390"><br>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click(Middle Finger)</summary>
<img src="Media/minor FINAL.pdf-image-039.jpg" alt="Move Cursor" width="452" height="390"><br>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click(Index and Middle)</summary>
<img src="Media/minor FINAL.pdf-image-037.jpg" alt="Move Cursor" width="452" height="390"><br>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Drag and Drop(Fist)</summary>
<img src="Media/minor FINAL.pdf-image-038.jpg" alt="Move Cursor" width="452" height="390"><br>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

----

## Tools and Technologies
Python: Version (3.6 - 3.8.5)
Python Libraries:
 - OpenCV
 - mediapipe
 - pyautogui
 - Numpy
 - Anaconda


---
**click on dropdown for photo**
<details>
<summary>**Co-ordinates or landmarks in the hand using Mediapipe**</summary>
  <img src="Media/minor FINAL.pdf-image-021.png"  width="800" height="372"><br>
</details>
<details>
<summary>**Architecture Design**</summary>
  <img src="Media/minor FINAL.pdf-image-027.png"  width="773" height="719">
</details>


----

## Pre-requisites
Python: (3.6 - 3.8.5)
Anaconda Distribution:

## Setup

  Step 0:
  ```bash
  https://github.com/aadeshpall/Hand-Gesture-Mouse-Controller.git
  ```

  Step 1: 
  ```bash
  conda create --name gest python=3.8.5
  ```
Go to Anaconda and create **python=3.8.5** virtual environment
OR put this above command in Anaconda Prompt(CLI)
  
  Step 2:
  ```bash
  conda activate gest
  ```
After making environment activate it by above command

Step 3:
  ```bash
  pip install -r requirements.txt
  ```
  
  Step 4:
  ```bash 
  conda install PyAudio
  ```

  ```bash 
  conda install pywin32
  ```
  
  Step 5:
  ``` 
  cd to the GitHub Repo till src folder
  ```
  Now go to projects **src** file

  Step 6:
  Now run this .py file **python Gesture_Controller.py**

## Contact

- Email: aadeshvinodpal@gmail.com
- Linkedin: https://www.linkedin.com/in/niranjanpal/
