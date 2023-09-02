# Brain-Tumor-Detection
This research produced 2 applications where the application has the .ipynb extension which can be run on Google Colabs and 1 more application which is a website as a prototype which can be extracted at https://telkomuniversityofficial-my.sharepoint.com/:u:/g/personal/faizrofihencya_student_telkomuniversity_ac_id/EW55ZNHaRClKiIUp9nwqWhMBIdrcWdb4BOV0vyl_TZP_bg?e=RshFfU
<br/>
how to run the prototype will be explained below

## DATASET
Dataset for train & validation set https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?resource=downloa 
<br/>
Dataset for test set https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

## Tutorial Prototype
1. Clone this repository
2. Extract prototype from https://telkomuniversityofficial-my.sharepoint.com/:u:/g/personal/faizrofihencya_student_telkomuniversity_ac_id/EW55ZNHaRClKiIUp9nwqWhMBIdrcWdb4BOV0vyl_TZP_bg?e=RshFfU
3. Move to folder Brain Tumor Detection Website
4. Install library
<br/>
(
import os
<br/>
import tensorflow as tf
<br/>
import numpy as np
<br/>
from PIL import Image
<br/>
import cv2
<br/>
from keras.models import load_model
<br/>
from flask import Flask, request, render_template
<br/>
from werkzeug.utils import secure_filename
<br/>
import imutils
)
<br/>
5. Running the program with python3 app.py
