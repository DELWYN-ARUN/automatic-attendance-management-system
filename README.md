In the project directory, create a folder named TrainingImage where all the photos that will be used to train the model will be kept. This is the first stage.
Open the main Python script, AMS_Run.py, which contains the project's code.
Modify the paths in the AMS_Run.py file to correspond to the path where the project is located on your machine.
Run AMS_Run.py: Execute AMS_Run.py after making the necessary route changes.
Data collection on faces is the following action. Click "Take Images" after entering your name and ID in the appropriate fields. 200 pictures of your face will be gathered in total, and they'll be saved in the TrainingImage folder.
Educate the model: After gathering the face data, click the "Train Image" button to begin training the model. For ten people, this will take five to ten minutes.
Automatic attendance: After the model has been trained, select the "Automatic Attendance" button to automatically fill out the attendance form. The model will be saved in the TrainingImageLabel folder, and an attendance CSV file will be generated based on the time and topic.

Change the DB name in the AMS_Run.py file and install WampServer if you want to save the attendance data in a database.

