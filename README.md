# Project2
Windows 10 - Anaconda, Jupyter Notebook, Tensorflow, Keras 

# Course Objective:
This project aims to build on the deep learning concepts from ProjectUno. 

# After completing this project you will be able to: 

1. Navigate virtual environments in Anaconda 
2. Enable environments in Jupyter Notebook 
3. Install dependencies for Tensorflow and Keras
4. Execute and Troubleshoot code with Tensorflow and Keras libraries
5. Import Outside Datasets 
6. BONUS: Enable Nvidia GPUs

# Before we begin:
- Uninstall any other versions of Python installed on the Windows Machine
- Download the latest Anaconda Installer from https://www.anaconda.com/download/
  - Be sure to select the proper bit installer (E.g. x64 64-Bit or x86 32-Bit) 
  - I chose to NOT add Anaconda to my PATH environment variable (this gives Python access to our CMD terminal via the Python Command)
  
# Exclaimer: At the making of this tutorial Tensorflow only supports Python 3.6  
(I.e. no need to worry about the Python Version (ex. 3.6) this can be specified within our Virtual Environments)

# Once you have Anaconda Installed: Let's set up our Virtual Environment & Install our Dependencies

To Create Virtual Environments within Anaconda: 
- conda create -n ProjectUno python=3.6
- Proceed ([y]/n)? y - to Update Packages 

To List All Virtual Environments within Anaconda:
- conda env list 

To Enter a Virtual Environment 
- activate ProjectUno

To Check Python Dependency Versions
- python --version 
- jupyter notebook --version

To Install Python Dependencies
- conda install -c conda-forge tensorflow 
- pip install keras 
- pip install matplotlib

To Enable our Virtual Environment within Jupyter Notebook
- pip install ipykernel
- python -m ipykernel install --user --name=ProjectUno

Open Jupyter Notebook
- Jupyter Notebook
- Select New\ProjectUno

Check Tensorflow Version
- import tensorflow as tf
- tf.__ version__ (Ignore space after first __)
  
To Execute code
- Ctrl + Enter 

To Enter New Cell 
- Shift + Enter 

# Congratulations! You have now set up your Deep Learning Environment!
