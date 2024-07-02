# Image Processing and Computer Vision 👁️

This repository contains all of the code and other resources related to the Image Processing and Computer Vision module (CS3042) conducted by Dr. Kaneeka Vidanage of the Faculty of Computing, General Sir John Kotelawala Defence University in 2024.

# Prerequisite
First, download and install the anaconda navigator (python and Jupiter) and set up the virtual environment.
Because the construction of the virtual environment is for the purpose of overcoming the version conflict when installing python packages therefore the recommended practice is constructing the separate virtual environment and separate kernel for a specific type of machine learning language that you plan to create.

## Setting up the virtual environment
•	First, create a folder where you want to save. Then open the anaconda PowerShell prompt and type this command to navigate the project directory.

` cd ‘path to your project file’ `

•	Next type this command 
` Python -m venv env `

•	Activate the respective virtual environment that has been created that following the steps below.
 ` . \env\Scripts\activate `

•	After the activate the relevant environment next required kernel has to be created kernel will link the customized packages assembly Jupiter as relevant environment.

•	Execute the below command to activate the kernel installation. 
` pip install ipykernel `

•	once the kernel is installed executed the command for kernel link in development environment
` python -m ipykernel install –name env `

•	Set up your project with the necessary packages and libraries. After activating the virtual environment, enter the following command.

•	After this installation, open the ANACONDA NAVIGATOR software and open the Jupiter Notebook.


•	Then type these codes in the Jupiter notebook.

` pip install opencv-contrib-python `   and click the RUN button.
` pip install opencv-python `  and click the RUN button.
` pip install matplotlib ` and click the RUN button.

•	Then import these codes,
` import cv2 `
` import numpy as np `
` import matplotlib.pyplot as plt `


