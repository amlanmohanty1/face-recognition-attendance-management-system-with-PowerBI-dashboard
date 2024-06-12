<<<<<<< HEAD
## Face Recognition based Attendance Management System (FRAMS)
Face Recognition based Attendance Management System with a Flask web application and Power BI attendance dashboard.

### Technologies Used
- **Programming Languages:** Python
- **Libraries:** OpenCV, dlib, face-recognition
- **Database:** SQLite
- **Web Application:** Flask, HTML, CSS, JavaScript
- **Data Visualization:** Power BI

### Methodology
- **Environment Setup:** Created a conda environment and installed necessary dependencies including OpenCV, dlib, face-recognition, and Flask.
- **Face Detection:** Converted images to black and white, then used HOG to detect faces by comparing image gradients.
- **Face Embedding:** Used 128-dimensional vectors and the triplet loss function for distinguishing between faces.
- **Face Recognition:** Utilized Euclidean distance with a threshold of 0.5 to compare the generated face encodings with the actual encodings of the training images to recognize the faces.
- **Database Connection:** Stored attendance data in a SQLite database and exported it to CSV for Power BI integration.
- **Web Application:** Developed a Flask-based web app for real-time attendance capturing and management.
- **Power BI Dashboard:** Connected the attendance data to Power BI to create dashboards. Embedded Power BI reports into the web app for real-time insights.


### Figure Appendix
- Fig.1: Home page of FRAMS
  
  ![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/b5f28977-3781-4091-bd69-e2bdd392a548)

- Fig.2: Attendance Punching using FRAMS
  
  ![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/2ef80327-c75e-4c5e-810d-b5b6387b6dd2)

- Fig.3: Face is detected in low light conditions

  ![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/3578757a-a775-4f43-9d99-48e085af486c)

- Fig.4: Face is detected from different angles

  <img src = "https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/60365317-d9ea-467a-95b5-b213818739ae" width="700" height="500">

- Fig.5: Administrator Login Page

  ![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/9c60132b-0b56-4a1b-8cea-b7b87b43ea28)

- Fig.6: Page showing the current day’s attendance

  ![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/3bcb178d-b336-4c02-a8ee-9a11cd9dbd25)

- Fig.7: Attendance Dashboard in Power BI

  ![image](https://github.com/amlanmohanty1/face-recognition-attendance-management-system-with-PowerBI-dashboard/assets/72063042/532a47ce-fd9b-4b6a-9ef8-effd19b22dc2)




