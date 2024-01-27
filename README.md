The FaceLog Attendance System is a personnel-attendance system which provides an interface for user attendance based on their face-id.
The machine learning based computer vision library used for this project is from the repository 'face_recognition' by ageitgey(ref:https://github.com/ageitgey/face_reco... ) which was proven to show a high degree of robustness and accuracy. Using this library the system was able to detect registered users with a high accuracy measure thereby logging their attendance details into a file. System has four main features- login , logout, and register.

![Screenshot (36)](https://github.com/Navneeth7/FaceLog-Attendance-System/assets/89082421/811fc49b-fc2e-4ee0-9331-f1906d236dd5)


The user, if new to the system, first has to register by entering their name which is then stored in the database.  

![Screenshot (35).png](..%2F..%2FPictures%2FScreenshots%2FScreenshot%20%2835%29.png)

When this user tries to login the system with the help an external webcam(of the device of the user), detects the face in the camera and the face recognition software runs the detected image with the image in the database. If a match has been observed the user is logged in and his/her name and login date and time are entered into a csv file in the system.

![Screenshot (37).png](..%2F..%2FPictures%2FScreenshots%2FScreenshot%20%2837%29.png)

The logout button allows the user to logout from the system and marks his/her signing out from the system which works in a similar fashion to the login operation.

![Screenshot (38).png](..%2F..%2FPictures%2FScreenshots%2FScreenshot%20%2838%29.png)

![Screenshot 2024-01-27 224112.png](..%2F..%2FPictures%2FScreenshots%2FScreenshot%202024-01-27%20224112.png)

The interface and front-end has been made using Tkinter GUI. 



