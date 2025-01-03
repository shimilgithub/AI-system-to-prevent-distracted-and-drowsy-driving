# AI System to Prevent Distracted and Drowsy Driving

## Project Overview

This project describes the development and execution of an AI-powered system aimed at improving
road safety by recognising distracted and fatigued drivers. The research tackles a key issue in
transportation safety by using cutting-edge machine learning techniques, specifically Convolutional
Neural Networks (CNNs), to monitor and analyse driver behaviour in real time. The goal is to develop
a holistic system that not only detects unsafe behaviours but also avoids accidents by sending timely
alerts. The study describes the technologies, methodologies, and experimental results that demonstrate
the system's efficacy in reducing road risks.

Data was gathered from two major sources: the [nthuddd2 dataset](https://www.kaggle.com/datasets/banudeep/nthuddd2) with 66,500 images labelled for drowsiness and the [State Farm dataset](https://www.kaggle.com/competitions/state-farm-distracted-driverdetection/data) containing 22,000 images across 10 driver
behaviours. These datasets provided a comprehensive base for training and testing the
model. Datasets include the nthuddd2 and State Farm Distracted Driver Detection datasets,
comprising over 88,500 labelled images depicting driver behaviours.


## Technologies Used:
- Python
- TensorFlow (Keras API): For deep learning model building, training, and optimization.
- OpenCV (cv2): For advanced image processing tasks.
- scikit-learn: For data splitting, cross-validation, and performance evaluation metrics.
- Pandas: For managing and analyzing structured data efficiently.
- NumPy: For numerical operations and efficient data handling.
- Matplotlib: For creating plots and visualizing data insights.
- Seaborn: For advanced statistical graphics and visually appealing plots.
- tqdm: For progress bar tracking in iterative processes.



## Resources

Here are the relevant links for the project:

- **[Presentation Slides](Presentation_Slides.pdf)**: Slides used during the presentation summarizing the project work and key findings.
- **[Project Report](Project_Report.pdf)**: A detailed report describing the technical aspects of the project, the methods employed, and results obtained.

## Repository Structure

* **distracted_driver_detection.ipynb**
    * Contains jupyter notebook code for the distracted driver detection.
* **drowsiness_detection.ipynb**
    * Contains jupyter notebook code for the driver drowsiness detection.
