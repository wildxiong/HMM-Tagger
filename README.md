# Introduction
In this notebook, 使用 Pomegranate 库构建隐马尔可夫模型，可用于语音识别和语音生成、机器翻译、生物信息学基因识别和计算机视觉人类手势识别，等等。

# Setup

This project requires GPU acceleration to run efficiently. Support is available to use either of the following two methods for accessing GPU-enabled cloud computing resources.

##  Workspaces (Recommended)

 Workspaces provide remote connection to GPU-enabled instances right from the classroom. Refer to the classroom lesson for this project to find an overview of navigating & using Jupyter notebook Workspaces.

Please refer to the Udacity instructions for setting up a GPU instance for this project, and refer to the project instructions in the classroom for setup. The recommended AMI should include compatible versions of all required software and libraries to complete the project. [link for AIND students](https://classroom.udacity.com/nanodegrees/nd889/parts/16cf5df5-73f0-4afa-93a9-de5974257236/modules/53b2a19e-4e29-4ae7-aaf2-33d195dbdeba/lessons/2df3b94c-4f09-476a-8397-e8841b147f84/project)

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

# Submission
When you are ready to submit your project, do the following steps:
1. Ensure you pass all points on the [rubric](https://review.udacity.com/#!/rubrics/1004/view).
2. Submit the following in a zip file:
  - `helper.py`
  - `machine_translation.ipynb`
  - `machine_translation.html`

## Converting to HTML

There are several ways to generate an HTML copy of the notebook:

 - Running the last cell of the notebook will export an HTML copy

 - Navigating to **File -> Download as -> HTML (.html)** within the notebook

 - Using `nbconvert` from the command line

    $ pip install nbconvert
    $ nbconvert machine_translation.ipynb
# -HMM-Tagger
