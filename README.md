# Diffeomorphic Temporal Alignment Nets
Repository for our upcoming code for our NeurIPS 2019 paper, Diffeomorphic Temporal Alignment Nets. We are now working on updating the code to TensorFlow 2.0.

## Author of this software
Ron Shapira Weber (email: ronsha@post.bgu.ac.il)

## Requirements
- Standard Python(3.6) packages: numpy, matplotlib, scipy
- tensorflow==1.11 (keras should be included)
- tslean==0.1.19 (requires for DTW based methods - SoftDTW, DBA and NCC)
- libcpab==1.4
- For Nvidia GPU iimplementation: CUDA==9.0 + appropriate cuDNN as well as tensorflow-gpu. You can follow the instructions [here](https://www.tensorflow.org/install).

Operation system: we currenly only support Linux oprating system.

## Installation
Install [libcpab](https://github.com/SkafteNicki/libcpab):
```
git clone https://github.com/SkafteNicki/libcpab
```
Add libcpab to your python path:
```
export PYTHONPATH=$PYTHONPATH:$YOUR_FOLDER_PATH/libcpab
```
Clone the repository:
```
git clone https://github.com/BGU-CS-VIL/dtan.git
```
Add DTAN to your python path:
```
export PYTHONPATH=$PYTHONPATH:$YOUR_FOLDER_PATH/dtan
```
