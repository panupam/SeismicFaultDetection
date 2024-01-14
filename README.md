# Seismic-Fault-Detection
Detecting Seismic Faults using Deep Learning
# Instructions
1. Create a new python environment with python version = 3.9.6 and activate it by source "directory_of_new_env"/bin/activate
2. Install all the packages from requirements.txt file by pip install requirements.txt
3. Download the data from https://drive.google.com/drive/folders/1I6zSvWOxFPT9SjruxyvJngOGh--g1Bpf?usp=share_link
4. Create a new folder named = "fault" in the root directory 
5. Put the downloaded data inside the created folder ("fault") directory 
6. pre_processing.ipynb is for the preprocessing of the data, it has various options as to how many pixel of images you want and other flexibility, run from top to bottom without skipping to know how this file works
7. model_implementation_and_training.ipynb is for the U-Net implementation with training and predicting using Keras, run cell by cell to know it.
8. post_processing.ipynb just enhances the predicted results using LSD and line matching algorithm.
9. Majority of the code can be understood by fidding around, the code is written with flexibility and has all the freeedom to manipulate the data and models
10. Saved models can be found here: https://drive.google.com/drive/folders/1PY2ZeFL7Vd6o4y3oaFxw8u8FmyhjaM-e?usp=sharing

