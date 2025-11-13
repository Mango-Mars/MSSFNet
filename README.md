
# Deep Learning for Radargrammetric DSM Generation: A StereoSAR Dataset and Multi-Scale Fusion Network
<img width="1544" height="538" alt="flow_chart" src="https://github.com/user-attachments/assets/e17091e2-d18a-4cec-837d-52f911b1a1ac" />

This is an official implementation of MSSFNet framework in our paper "Deep Learning for Radargrammetric DSM Generation: A StereoSAR Dataset and Multi-Scale Fusion Network".

We hope that the MSSFNet framework can serve as a stronger and clearer baseline for radargrammetric DSM generation research.
# Getting Started

### Create a virtual environment and activate it
* conda create -n MSSFNet python=3.7.16
* conda activate MSSFNet

### Requirements:
* python == 3.7.16
* tensorflow == 2.5.0
* cudatoolkit == 11.2
* cudnn == 8.1.1
* Pillow == 9.5.0
* scipy == 1.4.1

## Train 
```
python3 Train.py
```

## Test 
```
python3 test.py
```
