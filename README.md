# -HERE-I-HAVE-CREATED-REAL-TIME-FACE-DETECTION-WEB-APP-USING-PYTHON-OpenCV
This project is a real-time face detection web application developed using Python, OpenCV, and Flask. The application captures live video from a webcam, processes each frame using computer vision techniques, and detects human faces in real time. The detected faces are highlighted with bounding boxes and displayed directly in a web browser.

The main objective of this project is to demonstrate how machine learning–based face detection can be integrated into a web application. Instead of showing the output in a traditional desktop window, the video stream is served over HTTP and rendered inside a browser, making the system more interactive and closer to real-world applications.

Face detection is implemented using the Haar Cascade Classifier, a classical machine learning approach provided by OpenCV. Each video frame is first converted to grayscale to improve performance and accuracy. The classifier then scans the frame to locate faces and returns their coordinates, which are used to draw rectangles around detected faces.

The backend of the application is built using Flask, which handles video streaming and routing. A generator function continuously captures frames from the webcam, applies face detection, and streams the processed frames to the frontend using the multipart response technique. The frontend is a simple HTML interface that displays the live video feed in real time.

This project serves as a strong foundation for more advanced computer vision systems. It can be easily extended to include face recognition, attendance management, mask detection, or emotion analysis. The system is suitable for learning purposes as well as for building AI-powered applications related to security, surveillance, and human–computer interaction.

🛠️ Technologies Used

Python

OpenCV

Machine Learning (Haar Cascade Classifier)

Flask

HTML & CSS

📌 Applications
