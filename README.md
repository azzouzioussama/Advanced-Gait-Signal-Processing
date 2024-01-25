# Advanced-Gait-Signal-Processing

## Introduction
This repository contains Python code for gait analysis and signal processing, specifically designed for biomechanical applications. The code includes functionalities for:

- **Importing Data:** Linking Google Drive and importing necessary libraries for data analysis.
- **Data Preprocessing:** Importing and organizing sensor data from a text file, including quaternion data and various sensor measurements.
- **Joint Angle Calculation:** Extracting joint angles from quaternion data and performing calculations based on rotation matrices.
- **Swing/Stance Detection (FSR and IMU):** Implementing threshold-based algorithms for swing/stance detection using Force Sensing Resistors (FSR) and Inertial Measurement Units (IMU).
- **EMG Data Processing:** Filtering electromyography (EMG) data to remove noise and rectifying it for further analysis.
- **Gait Statistic Evaluation:** Extracting gait parameters, such as stride time, swing time, stance duration, cadence, stride length, and gait velocity.

## Usage
1. **Link Drive and Import Libraries:** Use the provided code to link Google Drive and import necessary libraries.
2. **Import Data:** Load sensor data from a text file and preprocess it for further analysis.
3. **Joint Angle Calculation:** Calculate joint angles from quaternion data using the provided functions.
4. **Swing/Stance Detection (FSR and IMU):** Implement threshold-based algorithms for swing/stance detection using FSR and IMU data.
5. **EMG Data Processing:** Apply high-pass and low-pass filters to EMG data, rectify it, and store the processed data.
6. **Gait Statistic Evaluation:** Analyze gait parameters based on processed sensor data.

## Dependencies
- Google Colab
- NumPy
- pandas
- Matplotlib
- SciPy

## How to Run
1. Open the provided Jupyter notebook or Python script in a compatible environment.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run each code section sequentially, following the instructions and comments.

## License
This project is licensed under the MIT License.

## Acknowledgments :
- Samer Mohammed

Please feel free to contribute, report issues, or suggest any improvements. Happy coding!
