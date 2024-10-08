# Henry Samuel - Data Science Portfolio

## About
I hold a Bachelor of Science in Mechanical Engineering from the Bandung Institute of Technology (ITB), where I developed a deep interest in the intersection of engineering and technology. With a robust background in mechanical systems, I've transitioned into the realm of data science and artificial intelligence, bringing a unique perspective to complex data challenges. Currently, I am honing my skills as an AI Engineer, backed by my recent certification in the DeepLearning.AI TensorFlow Developer Professional Certificate.

During my career, I've applied my technical skills in developing Python codes for automating data processes. My projects include developing Python codes that leverage data to drive decision-making and innovation and using Tableau to visualize pandemic trends globally—tools that have been essential in my data-driven journey.

My [CV](https://github.com/nrysam/Data-Science-Portfolio/blob/main/Resume%20(Data%20Scientist)%20-%20Henry%20Samuel%20Manurung.pdf) in pdf.


## Table of Contents
- [About](https://github.com/nrysam/Data-Science-Portfolio/blob/main/README.md#about)

- [Portfolio Projects](https://github.com/nrysam/Data-Science-Portfolio/blob/main/README.md#portfolio-projects)

- [Education](https://github.com/nrysam/Data-Science-Portfolio/blob/main/README.md#education)

- [Certification](https://github.com/nrysam/Data-Science-Portfolio/blob/main/README.md#certification)

- [Contact](https://github.com/nrysam/Data-Science-Portfolio/blob/main/README.md#contact)


## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Booking Appointment Agent
**Code** : [Booking Appointment](https://github.com/nrysam/Booking_Appointment_Agent)

**Description**: This project centers around the development of a smart booking appointment agent capable of handling human-like conversations to schedule, check availability, and cancel bookings. The agent uses OpenAI's GPT-4o-mini model to understand and manage user interactions, ensuring a seamless booking experience. The system integrates with Firebase for storing and managing appointment data, with additional features like data backup and booking cancellation. The frontend is built using Flask, providing a user-friendly interface, while the backend processes are managed through robust intent detection and time parsing functionalities.

**Skills**: Natural Language Processing, Chatbot Development, Appointment Management, Database Integration, Web Development, Data Parsing, Intent Detection

**Technology**: Python, Flask, OpenAI GPT-4o-mini, Firebase, Pandas, Tempfile, JSON, Gunicorn

**Result**: The Booking Appointment Agent effectively manages appointments, handles user queries with high accuracy, and provides a responsive and interactive experience. The integration with Firebase ensures reliable data management and backup, while the use of GPT-4o-mini for intent detection allows the agent to accurately understand and respond to user requests. The project highlights advanced integration between conversational AI and appointment management systems, making it a valuable tool for businesses needing automated booking solutions.

### Cryptocurrency Chatbot
**Code** : [Cryptocurrency Chatbot](https://github.com/nrysam/crypto-chatbot)

**Description** : This project involves the development of an interactive chatbot designed to provide users with real-time information about cryptocurrencies. Utilizing Rasa for natural language understanding and dialogue management, the chatbot integrates with Firebase to fetch and store cryptocurrency data. The frontend is built with Flask, offering a user-friendly interface for seamless interaction. The system supports a range of functionalities including answering queries about various cryptocurrencies, their prices, market cap, trading volume, and more.

**Skills** : Natural Language Processing, Chatbot Development, Real-Time Data Fetching, Database Management, Web Development, Data Integration

**Technology** : Python, Flask, Rasa, Firebase, Pandas, scikit-learn

**Result** : The Crypto Chatbot effectively fetches and provides real-time cryptocurrency information to users. It demonstrates the capability to handle user queries with accuracy, leveraging Rasa for understanding and managing conversations. The integration with Firebase ensures that the data is always up-to-date, making the chatbot a reliable source for cryptocurrency information. The project showcases strong integration between various technologies, resulting in a responsive and informative chatbot for crypto enthusiasts.

### Face Recognition Attendance
**Code** : [Face Recognition Attendance](https://github.com/nrysam/Face-Recognition-Attendance)

**Description** : This project implements a sophisticated attendance tracking system using face recognition technology. Leveraging OpenCV for image processing and the Face Recognition library for detecting and encoding facial features, the system integrates with Firebase for real-time database and storage management. The workflow encompasses face registration, encoding, and real-time attendance monitoring, ensuring accurate and efficient attendance logging.

**Skills** : Computer Vision, Face Recognition, Real-Time Processing, Database Management, Image Encoding, Data Integration

**Technology** : Python, Flask, OpenCV, face_recognition, Firebase, cvzone, numpy

**Result** : The system successfully captures and registers faces, encodes them for recognition, and updates attendance records in real-time. It showcases high accuracy in recognizing registered employees and effectively logs attendance with a minimal error rate. The project demonstrates robust integration with Firebase for database management and storage, providing a seamless and automated solution for attendance tracking in organizational settings.

### Face Fatigue / Drowsiness Detection
**Code** : [Face Fatigue Detection](https://github.com/nrysam/Face-Fatigue-Detection/)

**Description** : Face Fatigue Detection is an application that uses a combination of face recognition and fatigue detection models to identify users and determine their fatigue status based on video input from a webcam. The system utilizes YOLOv5 for face detection and a ResNet-based model for fatigue classification.

**Skills** : Face Detection, Database Design, Deep Learning, Fatigue Analysis, Deployment

**Technology** : Python, PyTorch, Face Recognition, NumPy, OpenCV, MySQL, YOLOv5, Docker, Git

**Result** : Real-Time Fatigue / Drowsiness Detection based on video input from a webcam with frame detects the face and give the status of the face, whether it is an active (fit) or fatigue (drowsy/unfit).


### LSTM-based Yelp Review Sentiment Analysis
**Code** : [Sentiment Analysis Yelp Review](https://github.com/nrysam/sentiment_yelp))

**Description** : This project is centered around analyzing Yelp reviews using a deep learning approach to categorize sentiments as positive or negative. Utilizing a dataset of fine-grained sentiment classification from Yelp reviews, the model employs LSTM (Long Short-Term Memory) networks to accurately determine the underlying sentiment. The process is methodically divided into several scripts covering data preparation, model training, sentiment prediction, and evaluation.

**Skills** : Natural Language Processing, LSTM, Sentiment Analysis, Data Preprocessing, Model Optimization

**Technology** : Python, TensorFlow, Keras, Pandas, Matplotlib

**Result** : Achieves detailed sentiment analysis with the capability to identify nuanced expressions in reviews. The project culminates in precise sentiment delineation, represented through accuracy and loss metrics over multiple epochs, complemented by visual graphs that illustrate the model’s performance on both training and validation sets. This facilitates a robust understanding of consumer opinions, beneficial for businesses monitoring customer satisfaction.


### CNN-based Car Part Identifier: A Machine Learning Approach
**Code** : [CNN-based Car Part Identifier: A Machine Learning Approach](https://github.com/nrysam/CNN-Car-Parts)

**Description** : The project develops a CNN-based car part identifier to accurately classify images into 50 different categories of car components. Using a comprehensive dataset of car part images, the model leverages convolutional neural networks to learn distinctive features of each part, enhancing the automation and efficiency in automotive industry tasks such as inventory management and quality control. The model architecture includes several convolutional layers, pooling layers, and dropout layers to mitigate overfitting, culminating in a dense layer for classification. The project is segmented into multiple scripts handling data preprocessing, model training, performance evaluation, and result visualization.

**Skills** : Image Data Preprocessing, Deep Learning Model Design, Convolutional Neural Network, Model Training and Validation, Performance Metrics Evaluation, Data Visualization

**Technology** : Python, TensorFlow, Keras, Numpy, Matplotlib, Seaborn, Scikit-learn

**Result** : The final model achieves a robust classification accuracy, demonstrated through detailed accuracy and loss graphs over training epochs, as well as a confusion matrix illustrating class-wise performance. The evaluation on the test dataset confirms the model's effectiveness, supported by a comprehensive classification report that provides precision, recall, and F1-scores for each car part category. This showcases the model's capability to support real-world applications in the automotive sector by facilitating rapid and accurate car part identification.


### Forming UCL 22/23 XI of the Tournament Analysis
**Code** : [Football Analytics Project: Forming XI of the UCL 22/23](https://github.com/nrysam/UCL22_23)

**Description** : The project focused on analyzing the dataset of football players played in UCL Season 2022/2023. The dataset included statistics from various metrics, such as Goals, Assists, Expected Goals, Key Passes, Total Tackles, Saves and other relevant metrics. It leverages advanced statistical methods and data visualization techniques to evaluate and select the top performers. The analysis is segmented into five Python scripts, each serving a distinct purpose towards the final selection of players.

**Skills** : Data Cleansing, Data Preprocessing, Advanced Data Visualization, Statistical Analysis, Predictive Modeling

**Technology** : Python, Pandas, Numpy, Matplotlib, Bokeh, Scikit-learn

**Result** : Delivers interactive visualizations such as heatmaps, bar plots, radar charts, and violin plots, aiding in the insightful comparison and selection of top performers. The final output includes a dynamically generated "Best XI" team, showcasing the capabilities of data-driven decision-making in sports analytics.


## Education
Bandung Institute of Technology (ITB) : Bachelor of Science

## Certification
The best way to showcase skills is by doing and sharing your job done but sometimes certificates appear to be as an indirect result. Here's a list of the ones I have (in reverse-chronological order, with the date of completion in brackets):
- [DeepLearning.AI TensorFlow Developer](https://www.coursera.org/account/accomplishments/specialization/MB9V3F39KHDV) (April 2024) (Coursera DeepLearning.Ai)
- [Myskill - Business Intelligence](https://drive.google.com/file/d/1gBKZcsQ4FDSdom1Oi_jzhcNTbXFk5Vy2/view) (February 2022) (Myskill.id)
- [Sanbercode Python - Data Science](https://drive.google.com/file/d/1KybHKJjWyMmv62HraneGQdVUSwdMjye2/view) (January 2022) (Sanbercode)

## Contact
- **Linkedin** : [@henrysamuelmanurung](https://www.linkedin.com/in/henry-samuel-manurung)
- **Email** : [henrysmnrg@gmail.com](mailto:henrysmnrg@gmail.com)
