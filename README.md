# FaceRecognitionAttendance
Face recognition-based smart attendance system with web app using machine learning.

Libraries:
- from sklearn.neighbors import KNeighborsClassifier
- import cv2
- import pickle
- import numpy as np
- import os
- import csv
- import time
- from datetime import datetime
- from win32com.client import Dispatch
- import streamlit as st
- import pandas as pd

1. Run "streamlit run app.py" in terminal in app.py to open attendance sheet
2. Run add_faces.py, input name in terminal and let facecam take 100 pictures (for new users)
3. Run test.py to take attendance
6. Take attendance and refresh attendance sheet for data

Credits: KNOWLEDGE DOCTOR on YouTube
https://www.youtube.com/watch?v=BYCKvM8eZGA&t=260s&ab_channel=KNOWLEDGEDOCTOR
