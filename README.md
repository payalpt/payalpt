## Hi, I'm Payal Patel!

## About Me 
I'm a graduate student in Artificial Intelligence with a background in Cognitive Science, focused on building end-to-end machine learning systems grounded in strong statistical reasoning. 

My work centers on:

- Production ready ML systems
- Deep learning & time-series forecasting
- MLOps pipelines & real-time inference
- Model evaluation and performance benchmarking
- Applied AI in energy systems, speech intelligence, and robotics

I'm particularly interested in predictive modeling, decision-support systems, and scalable ML workflows.

## 🎓 Education
- Master of Science in Applied Artificial Intelligence (University of San Diego) - Anticipated Apr,2026
- Bachelors in Cognitive Science, Concentrating in Biological Foundations of Cognition (BCogSc), Minoring in Neuroscience and Mental Health (Carleton University)

## 🧠 Featured Projects
### 🗣️ VoiceSync AI - Emotion Detection ML System 
Designed and deployed a production ready emotion classification system using AWS SageMaker.
#### Problem:
Multi-class emotion prediction from short speech audio segments (7 classses).
#### System Highlights:
- Engineered 23 acoustic features using Librosa (MFCCs, spectral, pitch features)
- Built supervised classification pipeline (Logistic Regression baseline vs. XGBoost)
- Improved macro F1 from 0.40 -> 0.64 (+57.8%)
- Deployed real-time SageMaker endpoint (<20ms latency)
- Implemented monitoring (CloudWatch), feature drift detection, and CI/CD accuracy gates (≥60%)
#### Tech Stack:
Python • AWS SageMaker • Athena • S3 • XGBoost • scikit-learn • Librosa

[Link to Repo](https://github.com/payalpt/aai-540-group-7)

### 🏘️ Smart Home Energy Anomaly Detection & Forecasting 
Developed a deep learning system for anomaly detection and energy forecasting using smart meter data.
#### Objective:
Detect irregular energy usage patterns and forecasting future consumption.
#### Approach:
- Autoencoder for anomaly detection
- LSTM network for time-series forecasting
- Standardized data preprocessing pipeline
- Integrated weather variables into modeling
#### Results
- Achieved 99.84% predictive accuracy across 7-day forecasting trends
- Identified anomalous energy consumption events for visualization in Tableau
#### Tech Stack:
Python • TensorFlow/Keras • LSTM • Autoencoders • pandas • NumPy

[Link to Repo](https://github.com/mojodean/aai-530-final-project)

### 🗺️ SLAM-Lite: Visual Mapping & Path Estimation 
Built a lightweight monocular SLAM pipeline for UAV navigation using GrapeSLAM vineyard dataset.
#### Objective:
Reconstruct 3D structure and estimate drone trajectory from monocular video.
#### Methodology:
- ORB feature detection + BRIEF descriptors
- Essential matrix estimation & pose recovery
- RANSAC filtering & Lowe's Ratio Test
- GPS-based scale correction
- 2D & 3D Procrustes alignment for drift reduction
#### Results (Post-Alignment 2D):
- RMSE reduced from 8.885m -> 0.445m
- Drift per 100m reduced from 157.1m -> 2.08m
- Achieved sub-meter trajectory precision
#### Tech Stack:
Python • OpenCV • NumPy • GPS coordinate transformations

[Link to Repo](https://github.com/wushuchris/aai-521-group-7)

### 📈 Financial Market Trend Prediction 
Built an end-to-end time-series forecasting pipeline for financial market direction prediction.
#### Highlights:
- Retrieved historical market data via API integration
- Engineered technical indicators
- Implemented supervised models for directional classification
- Benchmarked model performance using train/test validation
#### Focus Areas:
Time-series modeling • Feature engineering • Predictive analytics
#### Tech Stack:
Python • pandas • NumPy • scikit-learn • matplotlib

## 👩‍💻 Technical Skills
### Programing & Tools
Python • Git • GitHub • Jupyter Notebook • Google Colab
### Machine Learning
Supervised Learning • XGBoost • Logistic Regression
Deep Learning (LSTM, Autoencoders)
Time-Series Forecasting
Model Evaluation (ROC, AUC, Macro F1, RMSE)
### MLOps & Infrastructure
AWS SageMaker • S3 • Athena
Feature Store (online/offline)
Model Monitoring & Drift Detection
CI/CD Pipelines
### Data & Vision
Feature Engineering • Audio Signal Processing (MFCCs)
Visual Odometry • ORB Features • Procrustes Alignment

## 🔗 Let's Connect
[LinkedIn](https://www.linkedin.com/in/payalpatel2525/)

[Email](mailto:payalpat2002@gmail.com)




