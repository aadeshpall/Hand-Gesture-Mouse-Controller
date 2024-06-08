<h1 align="center">Gesturesflow (Virtual Mouse)</h1>

## :bookmark_tabs:Table of contents
* [Project info](#Project-info)
* [Features](#Features)
* [Tools and Technologies](#Tools-and-Technologies)
* [Setup](#setup)

## Project info

The Gesturesflow (Virtual Mouse) is designed to enable users to control their computer's mouse pointer through hand gestures. This system uses a camera to capture the user's hand movements and translates the coordinates of the fingertip to the full-screen computer window, allowing for an intuitive and touch-free interaction with the computer.

## Features
 **_click on dropdown to know more_** <br>

<details>
<summary>Neutral Gesture(Palm)</summary>
 <figure>
  <img src="Media/minor FINAL.pdf-image-033.jpg" alt="Move Cursor" width="652" height="590"><br>
  <figcaption>Neutral Gesture. Used to halt/stop execution of current gesture.</figcaption>
</figure>
</details>
 

<details>
<summary>Move Cursor(Peace Sign)</summary>
  <img src="https://github.com/xenon-19/Gesture_Controller/blob/e20edfb1f368ffa600d96bd91031942ec97cb2ab/demo_media/move%20mouse.gif" alt="Move Cursor" width="711" height="400"><br>
  <figcaption>Cursor is assigned to the midpoint of index and middle fingertips. This gesture moves the cursor to the desired location. Speed of the cursor movement is proportional to the speed of hand.</figcaption>
</details>

<details>
<summary>Left Click(Index Finger)</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/left%20click.gif" alt="Left Click" width="711" height="400"><br>
 <figcaption>Gesture for single left click</figcaption>
</details>

<details>
<summary>Right Click(Middle Finger)</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/right%20click.gif" alt="Right Click" width="711" height="400"><br>
 <figcaption>Gesture for single right click</figcaption>
</details>

<details>
<summary>Double Click(Index and Middle)</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/double%20click.gif" alt="Double Click" width="711" height="400"><br>
 <figcaption>Gesture for double click</figcaption>
</details>

<details>
<summary>Drag and Drop(Fist)</summary>
<img src="https://github.com/xenon-19/Gesture_Controller/blob/9be82cfc75aa4c04fff0e12dd4de853f9d83a101/demo_media/drag%20and%20drop.gif" alt="Drag and Drop" width="711" height="400"><br>
 <figcaption>Gesture for drag and drop functionality. Can be used to move/tranfer files from one directory to other.</figcaption>
</details>

## Tools and Technologies
Python: Version (3.6 - 3.8.5)
Python Libraries:
	- OpenCV
	- mediapipe
	- pyautogui
	- Numpy
 - Anaconda

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
