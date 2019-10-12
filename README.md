# face-capture

Data collection and data preprocessing takes about 90% of effort in machine learning projects. This project aims to provide a tool for creating a dataset of faces. 

## Project Structure
```
-src
  -main.py
  -face_detect.py
-media
  -images
    -- *
```

* Install Python 3.x from [Python.org](https://www.python.org/). 
* Learn Python if you already don't know it. The best place to start is often the [official documentaion](https://docs.python.org/3/tutorial/index.html) of the language.
* **\[RECOMMENDED\]** Install a text editor to view the code and manage projects in a better way. [VSCode](https://code.visualstudio.com/download) and [Atom](https://atom.io/) are good choices.
* Fork this repository.
* Clone your copy of the repository using ```git clone https://github.com/GITHUB_USERNAME/face-capture.git``` in your workspace on your computer. It's strongly advised to get comfortable with using [CLI Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) tools. All the steps mentioned hence further will also be assuming you use the CLI.
* Create the above project sturcture and the files.
* Install OpenCV with: ```pip install opencv-python```.
* Refer to face-detction repository for face detection. [reference](https://github.com/RNS-CVG/face-detection)
* Create all functions in **face_capture.py** and then later import the function into **main.py** after testing.
  * To read and display images in CV, refer to [this](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_image_display/py_image_display.html).
  * To read and display videos in CV, refer to [this](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_gui/py_video_display/py_video_display.html).
  * To perform face-detection and draw bounding boxes, refer to [this](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_objdetect/py_face_detection/py_face_detection.html).
  * To load and save images, refer to [this](https://docs.opencv.org/2.4/doc/tutorials/introduction/load_save_image/load_save_image.html)
* Edit out the following section in the README.md.
* Create a PR back to main repo. The code that gets merged will be based on the following criteria:
  - Syntax
  - Semantics
  - Efficiency
  - Readibilty
  - Comments and explanations
  - Extra features with documentation
* It is advised to work in incremental efforts while maintaining neat commits and keeping your code open-source. If you feel you can contribute to someone else's code in the group, fork their progress and continue off from there, and so on.
## Objectives
  * Prompt the user to enter the his/her name
  * Create a folder with the name of the user to store the images
  * Start a video feed and capture the face for about 3-4 seconds
    * prompt the user to turn the head about 15°-20° in up, down, left and right direcions
  * Capture 25-30 images of every user numbered in sequence.
## Getting Started

### Prerequisites
What things you need to install the software and how to install them:
```
1.Download Anaconda Navigator with Anaconda prompt
2.Open Anaconda Prompt
3.Install python 3.6 using command conda install python=3.6
4.Install OpenCV library using command pip install opencv-python
5.Install VScode editor using the Anaconda GUI interface.
6.Create a .py file to run the python program.
7.Debug and Run the program.
```
### Running the Code
What commands and how are they used to run the code.
```
python main.py
```
