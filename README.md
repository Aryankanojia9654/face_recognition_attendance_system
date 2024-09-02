# Face Recognition Based Attendance System

This project is a face recognition-based attendance system developed using OpenCV and Python. It utilizes a camera to capture images of individuals and compares them with images in the database to mark attendance.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Acknowledgements](#acknowledgements)

## Installation

1. **Clone the Repository**

   ```bash
   git@github.com:Aryankanojia9654/face_recognition_attendance_system.git
2.  **Install the Required Packages**
    
    Navigate to the project directory and install the required Python packages:
    
    bash
    
    Copy code
    
    `pip install -r requirements.txt` 
    
3.  **Download and Setup dlib Models**
    
    Download the dlib models from the following link: [dlib Models](https://github.com/davisking/dlib-models)
    
    Place the downloaded data folder inside the project repository.
    

## Usage

1.  **Collect Faces Dataset**
    
    Run the following script to capture images of individuals and create a dataset:
    
    bash
    
    Copy code
    
    `python get_faces_from_camera_tkinter.py` 
    
2.  **Convert Dataset to Python Features**
    
    Convert the collected dataset into features and save them into a CSV file:
    
    bash
    
    Copy code
    
    `python features_extraction_to_csv.py` 
    
3.  **Take Attendance**
    
    Use this script to mark attendance based on the face recognition system:
    
    bash
    
    Copy code
    
    `python attendance_taker.py` 
    
4.  **Check the Database**
    
    View and manage the database with this script:
    
    bash
    
    Copy code
    
    `python app.py` 
    


## Acknowledgements

This project was developed by:

-   Aryan Kanojia (2k22/EC/56)
-   Akshay Tiwari (2k22/EC/26)
-   Anurag Kumar (2k22/EC/46)
-   Anshit Gadi (2k22/EC/46)

**Delhi Technological University, ECE Second Year, EIM Project.**

