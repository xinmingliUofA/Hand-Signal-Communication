# Hand Signal Communication Sensor Dataset

This repository contains the sensor dataset used in the study:

**Dynamic Hand-Signal Recognition and Prediction Framework for Crane Operations Using Deep Learning**

## Dataset Description

The dataset contains wearable sensor data collected from instrumented gloves designed for crane hand-signal recognition. Each sample represents a short temporal segment of motion data collected from both hands.

The dataset is divided into one training set and two independent test sets used in the experiments reported in the paper.

## Data Structure

Each row in the dataset corresponds to one sample.

- Columns 1–45: Sensor data from the **left hand**
- Columns 46–90: Sensor data from the **right hand**
- Last column: **Gesture label**

Each hand includes measurements from multiple sensors across several time points, including:

- Accelerometer data
- Gyroscope data
- Flex sensor measurements

These features together represent the dynamic characteristics of hand signals.

## Files

The repository contains the following files:

- **train.csv** – training dataset used for model development  
- **testrandom.csv** – independent test dataset  
- **testsequential.csv** – independent test dataset  
- **labels.txt** – mapping between label indices and gesture classes  

## Gesture Labels

The gesture labels correspond to crane hand signals used in construction operations.  
The full label definitions and index mapping are provided in **labels.txt**.

## Image Dataset

The image datasets used for the computer vision component are hosted on the **Roboflow platform** as two separate projects (Camera1 and Camera2).

Due to ethics requirements related to human subject research, the image datasets are password-protected and are not publicly released.

Researchers interested in accessing the image datasets for academic purposes may contact the corresponding author to request access.

## License

This dataset is provided for academic research purposes only.
