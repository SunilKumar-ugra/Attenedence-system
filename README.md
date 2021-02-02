# :clap: Hello developers  :clap:

Code on Attendance system using Computer vision.

##### Functionality of  Code {<>}
This code takes following as a input.

- Image from the live camera .


Using these as inputs for the code, the framework puts the participation if the individual is available or not.


##### About Code {<>}
This code is written with following language.

- UI designs are done using python tinker.
- Training and testing of data are done using Python.


##### File Details {<>}
Following are the details about the file inside phishApp/PhishingSiteDetection

|    File Name   | Description                                                                                            |
|:--------------:|--------------------------------------------------------------------------------------------------------|
| data_capture.py  | code that is used to capture image for the dataset         |
| training_dataSet.py | Code that is used to train the model (Updated the path based on your system) |
| recognizer.py  | Code that is used to test the model (Updated the path based on your system)                           |
| index.py  | Used to create python gui                                                       |
| train.yml | This file is trained model file which will update once you run the  training_dataSet.py   
|xlwrite.py     | code that is used to keep take of the Attendance excel file






## Run code {<>}

Run 
```
pip install -r requirements.txt
python3 index.py.py 
```

##### Note {<>}

- Start this project from index.py
- Create dataset by clicking create dataset button.
- Train this by clicking dataset button
- Click on recognize + attendance button to start recognizing and marking attendance.
- Click on Attendance Sheet to view current date attendance sheet.










