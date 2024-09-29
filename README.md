# HumanActivity-Recognition

Human Activity Recognition (HAR) is a complex time series classification problem that utilizes smartphone sensors like accelerometers and gyroscopes to detect and classify human activities such as walking, sitting, standing, and climbing stairs. In this project, a deep learning approach is taken to accurately recognize these activities using an LSTM (Long Short-Term Memory) model, a type of Recurrent Neural Network (RNN) that is well-suited for learning patterns in sequential data.

The accelerometer and gyroscope data from the smartphone sensors generate 3D signals over time (X, Y, and Z axes), which are then pre-processed and passed through noise filters. After pre-processing, the data is divided into fixed-width windows of 128 readings and split into training and test datasets, with 80% of the data used for training and 20% for testing.

The project is implemented using Google Colaboratory, leveraging Python's deep learning libraries. The final model is exported for use in Android Studio, allowing integration into smartphone applications for real-time activity detection.

# Tech Stack:

1/ Programming Language: Python
2/ Deep Learning Framework: TensorFlow
3/ Model: LSTM (Long Short-Term Memory)
4/ Platform: Google Colaboratory
5/ Sensors Used: Accelerometer, Gyroscope
6/ Libraries: Numpy, Pandas, Matplotlib, Scikit-learn


# Conclusion:
This project demonstrates the power of LSTM models in recognizing human activities based on smartphone sensor data. By applying deep learning techniques to time series data, the project achieves high accuracy in classifying activities like walking, sitting, and climbing stairs. The integration of the model into Android Studio provides practical use for activity recognition in mobile applications, offering real-time activity tracking for health monitoring and fitness applications.
