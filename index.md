<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="chrome=1">
    <title>Homepage of Shicheng Chen</title>

    <link rel="stylesheet" href="stylesheets/styles.css">
    <link rel="stylesheet" href="stylesheets/pygment_trac.css">
    <meta name="viewport" content="width=device-width">
</head>



# Shicheng Chen

- coder.chen.shi.cheng@gmail.com
- https://github.com/ShichengChen/

# JOB
- Nanyang Technological University
    - Project Officer in the School of Computer Science and Engineering: 2017-now

# EDUCATION
- Tianjin University
    - BS in sofeware engineering
    - 2013-2017
    - GPA: 3.19 / 4.0

# PUBLIC LESSONS
- Stanford University 
    - cs231n Convolutional Neural Networks for Visual Recognition(finish all videos and homework)
    - cs229 Machine Learning (finish all videos and homework)
- Harvard University
    - cs109 Data Science(finish most videos and homework)

# SKILLS
- C/C++
    - Over 30000 lines:
    - familiar with OpenCV and STL
- Python
    - familiar with PyTorch, Pandas, Scikit-learn and NumPy
#RESEARCH INTERESTS
- Machine Learning
- Deep Learning
- Computer Vision

# AWARDS
- Bronze Medal The ACM-ICPC Asia Regional Contest Shanghai Site: 2014
- top 250/7764 The Beauty of Programming, Hosted by Microsoft: 2015
- top 415/7084 Astar Contest, Hosted by Baidu: 2015

# PUBLICATION
- Direct, Near Real Time Animation of a 3D Tongue Model Using Non-Invasive
Ultrasound Images
    - Shicheng Chen, Yifeng Zheng, Chengrui Wu, Guorui Sheng, Pierre Roussel, Bruce Denby
    
    - Presentation in a lecture(oral) session at the ICASSP 2018
    - Implement Snake algorithm to extract the sagittal contour from ultrasound images and Select five points from the contour
    - Use these five points to move a 3D tongue model
    - Extract contour or some other information from the model
    - Use the information from the 3D tongue model to tune the snake algorithm
    
- Predicting Tongue Motion in Unlabeled Ultrasound Video Using 3D Convolutional Neural Networks
    - Chengrui Wu, Shicheng Chen, Guorui Sheng, Pierre Roussel, Bruce Denby
    
    - Presentation in a poster session at the ICASSP 2018.
    - Use the convolutional neural network for several continuous frames to
predict an upcoming tongue image. Make use of both spatial and spatial information.
    - Implement the convolutional neural network to extract the contour from the ultrasound images (semantic segmentation) only by Python and Numpy instead of Deep Learning Libraries.
    - Implement the vectorized convolution layer, deconvolution layer, max
pooling, up pooling, average pooling, batch normalization, RELU.
    - **Challenge**: full vectorized implementation for convolution, pooling, batch
normalization layer.

# Project
- Audio Source Separation
    - Obtain accompaniment and vocals from mix music.
    - Use residual neural network as an encoder to raw audio.
    - Use modified WaveNet as a decoder.
    - The encoding is used to condition a WaveNet decoder.
    - More detail on https://github.com/ShichengChen/Audio-Source-Separation

- Machine Learning to Aid Repairers    
    - Use broken cars symptom; for example, the **engine** has **C type of noise** when the car is **cold**. (engine, C type of noise and cold are three features).
    - The problem with the car is the **spark plug**. (spark plug is the label).
    - Use Random Forest, Xgboost, Adaboost and Decision Tree to predict the answers.
    - Use Bayesian Optimization to tune hyperparameters.
    - Use Stacked Generalization (Ensemble method) to make the result better.
  