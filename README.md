The FaceLog Attendance System is a personnel-attendance system which provides an interface for user attendance based on their face-id.
The machine learning based computer vision library used for this project is from the repository 'face_recognition' by ageitgey(ref:https://github.com/ageitgey/face_reco... ) which was proven to show a high degree of robustness and accuracy. Using this library the system was able to detect registered users with a high accuracy measure thereby logging their attendance details into a file. System has four main features- login , logout, and register.

![Screenshot (36)](https://github.com/Navneeth7/FaceLog-Attendance-System/assets/89082421/811fc49b-fc2e-4ee0-9331-f1906d236dd5)


The user, if new to the system, first has to register by entering their name which is then stored in the database.  

![Screenshot (35)](https://github.com/Navneeth7/FaceLog-Attendance-System/assets/89082421/c5cfc3e1-6f33-433b-a1d6-5643926049b9)


When this user tries to login the system with the help an external webcam(of the device of the user), detects the face in the camera and the face recognition software runs the detected image with the image in the database. If a match has been observed the user is logged in and his/her name and login date and time are entered into a csv file in the system.

![Screenshot (37)](https://github.com/Navneeth7/FaceLog-Attendance-System/assets/89082421/3d8afeec-f557-488e-a2ee-9107e17f3b07)


The logout button allows the user to logout from the system and marks his/her signing out from the system which works in a similar fashion to the login operation.

![Screenshot (38)](https://github.com/Navneeth7/FaceLog-Attendance-System/assets/89082421/e7791a05-5516-4d09-8419-ce6017ec7fb9)


![Screenshot 2024-01-27 224112](https://github.com/Navneeth7/FaceLog-Attendance-System/assets/89082421/e6b1d862-e06e-4121-bfb3-4a08bb9826aa)

The interface and front-end has been made using Tkinter GUI. 



