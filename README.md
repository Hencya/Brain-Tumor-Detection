# Brain-Tumor-Detection
## DATASET
Dataset for train & validation set https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset?resource=download
<br/>
Dataset for test set https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

## Tutorial Prototype
1. Clone this repository
2. Extract prototype from https://telkomuniversityofficial-my.sharepoint.com/:u:/g/personal/faizrofihencya_student_telkomuniversity_ac_id/EW55ZNHaRClKiIUp9nwqWhMBIdrcWdb4BOV0vyl_TZP_bg?e=RshFfU
3. Move to folder Brain Tumor Detection Website
4. Install library (
import os
import tensorflow as tf
import numpy as np
from PIL import Image
import cv2
from keras.models import load_model
from flask import Flask, request, render_template
from werkzeug.utils import secure_filename
import imutils
)
5. Running the program with python3 app.py
