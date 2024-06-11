## Face Recognition based Attendance Management System (FRAMS)
Face Recognition based Attendance Management System with an attendance dashboard in Power BI

### 1. Setting up the Environment
- Created and activated a conda environment.
- Installed necessary dependencies including OpenCV, dlib, face-recognition, sqlite, and Flask.

### 2. Face Detection
- Utilized the Histogram of Oriented Gradients (HOG) method to detect faces in images and video streams.
- Implemented face detection using the dlib library.

### 3. Facial Image Processing
- Warped facial images to ensure eyes and lips were centered.
- Located 68 facial landmarks to align the face.

### 4. Face Embedding
- Generated 128-dimensional feature vectors to uniquely represent faces using the face_recognition library.
- Trained the model using the triplet loss function to distinguish between similar and dissimilar faces.

### 5. Face Recognition
- Utilized Euclidean distance with a threshold of 0.5 to compare the generated face encodings with the actual encodings of the training images to recognize the faces.

### 6. Database Integration
- Used the sqlite Python module to store attendance data.
- Exported data to CSV for integration with Power BI.

### 7. Web Application
- Developed a web app using Flask for the backend and HTML, CSS, and JavaScript for the frontend.
- Provided a user-friendly interface for attendance punching and viewing reports.

### 8. Data Visualization
- Connected the attendance data to Power BI to create interactive dashboards.
- Embedded Power BI reports into the web app for real-time insights.

### 9. Figure Appendix
- Fig.1: Home page of FRAMS 
![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/b5f28977-3781-4091-bd69-e2bdd392a548)

- Fig.2: Attendance Punching using FRAMS
![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/2ef80327-c75e-4c5e-810d-b5b6387b6dd2)

- Fig.3: Face is detected in low light conditions
![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/3578757a-a775-4f43-9d99-48e085af486c)

- Fig.4: Face is detected from different angles
![Untitled design](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/60365317-d9ea-467a-95b5-b213818739ae)

- Fig.5: Administrator Login Page
![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/9c60132b-0b56-4a1b-8cea-b7b87b43ea28)

- Fig.6: Page showing the current day’s attendance
![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/3bcb178d-b336-4c02-a8ee-9a11cd9dbd25)

- Fig.7: Attendance Dashboard in Power BI
![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/532a47ce-fd9b-4b6a-9ef8-effd19b22dc2)



