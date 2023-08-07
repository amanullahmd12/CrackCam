# CrackCam: Surface Crack Detection Web Application 📸🔍

Welcome to the GitHub repository of CrackCam, a deep-learning-based web application designed to detect cracks in surfaces by processing images of those surfaces. CrackCam is an efficient implementation of a crack detection system, providing a valuable tool for identifying surface defects and potential structural issues.

## Description

CrackCam is a cutting-edge web application that utilizes deep learning algorithms to detect cracks in various surfaces. By processing input images, it identifies and highlights areas with cracks, allowing for swift and accurate assessment of surface integrity. Whether you're a civil engineer inspecting infrastructure or a maintenance professional ensuring safety, CrackCam is here to streamline your crack detection process.

## Dataset

The dataset used for training and evaluating CrackCam contains two classes: "Positive" and "Negative." Images labeled as "Positive" contain surface cracks, while images labeled as "Negative" represent crack-free surfaces. The dataset can be accessed from the following link: [CrackCam Dataset](https://data.mendeley.com/datasets/5y9wdsg2zt/2).

## Algorithms Implemented

CrackCam implements the following machine learning models for crack detection:
- **CNN (Convolutional Neural Network):** CNNs are employed to learn spatial patterns and features from images, enabling accurate crack detection.
- **LSTM (Long Short-Term Memory):** LSTM models are utilized for sequence-to-sequence learning, useful in certain crack detection scenarios.

## Key Features

- **Web-Based Interface:** CrackCam boasts a user-friendly web interface that allows users to upload images and receive real-time crack detection results.
- **Efficient Crack Detection:** The deep learning models implemented in CrackCam ensure efficient and reliable detection of cracks in surfaces.
- **Versatile Use Cases:** CrackCam can be applied to various surfaces, including concrete, metal, wood, and more, making it suitable for diverse industries.
- **Real-Time Analysis:** Users receive crack detection results instantly, facilitating prompt decision-making and proactive maintenance.

## Technologies Used

CrackCam harnesses the following technologies for its functionality:
- **Python:** The core programming language used for developing the deep learning models and backend logic.
- **Flask Framework:** Flask is utilized to create the web application and handle server-side functionalities.
- **Convolutional Neural Networks (CNN):** CNNs form the backbone of CrackCam's crack detection algorithm.
- **Long Short-Term Memory (LSTM):** LSTM models are employed for specific crack detection scenarios requiring sequence-to-sequence learning.


## Installation and Usage
Feel free to explore the code, fork the project, and submit pull requests to make CrackCam an even more powerful tool for surface crack detection.


- The following python modules must be installed to run the Application.
  - ```flask```
  - ```TensorFlow```
  - ```Keras```
  - ```OpenCV```


## Instructions
1. Run ``` app.py``` to start the web application.
 ```bash
 python app.py
 ```
2. Open the browser and went to the started server.
3. Now upload the image and see the result.
4.


## Interface


<img width="1440" alt="Screenshot 2023-07-11 at 3 03 14 PM" src="https://github.com/amanullahmd12/CrackCam/assets/92320933/da2be66c-6f92-447f-87db-2774d47bce62">

<img width="1440" alt="Screenshot 2023-07-11 at 3 04 34 PM" src="https://github.com/amanullahmd12/CrackCam/assets/92320933/da401839-acef-4b5b-b056-627eb4cbb3ff">

<img width="1440" alt="Screenshot 2023-07-11 at 3 04 55 PM" src="https://github.com/amanullahmd12/CrackCam/assets/92320933/caa00d5d-f952-400a-8ae4-efbe5773faef">



## Thank You

Thank you for exploring CrackCam - the Surface Crack Detection Web Application. We aim to revolutionize crack detection processes and contribute to improved infrastructure maintenance and safety. Together, let's detect cracks and protect our built environment! 📸🔍


