ML-based Fitness Tracker
Overview
This project aims to classify barbell exercises and count repetitions using machine learning, based on data from accelerometer and gyroscope sensors. The process involves extensive data preprocessing (ETL), feature extraction, and model training to achieve accurate exercise classification.

Project Features
Data Collection: Merged over 180 Excel files containing accelerometer and gyroscope data into a unified dataset for analysis.
ETL Process: Performed noise filtering, outlier removal, and data normalization to clean and prepare the data for model training.
Machine Learning Model: Used Scikit-learn to train a classification model for exercise recognition and repetition counting.
Data Visualization: Visualized time-series patterns to enhance model accuracy and training effectiveness.

Dataset
[Link For The Dataset](https://tinyurl.com/datasetofexercises)
Original dataset consisted of 180+ Excel files, each with 150 rows and 6 columns.
After merging and preprocessing, the final dataset consists of:
9,009 rows × 10 columns.
Reduced to 3,868 rows × 121 columns after ETL, removing redundancies and outliers.
Requirements
Python 3.x
pandas
numpy
scikit-learn
matplotlib
seaborn
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Anup-Ojha/ML-based-Fitness-Tracker.git
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Preprocess data:

Run the ETL script to clean and merge the raw data.
The preprocessing script removes noise and outliers, preparing the data for machine learning.
Train model:

Use train_model.py to train the exercise classification and repetition counting model.
Visualize data:

The visualize_data.py script allows you to see time-series patterns in the sensor data for better understanding and model tuning.
Files Overview
data_processing.py: Contains data merging and ETL procedures.
model_training.py: Script for training and evaluating the machine learning model.
visualize_data.py: Data visualization scripts to visualize patterns in accelerometer/gyroscope data.
README.md: Project documentation.
Contributing
Feel free to fork this repository, submit issues, or create pull requests. Contributions to improve the model or data processing are welcome!

License
This project is licensed under the MIT License.

