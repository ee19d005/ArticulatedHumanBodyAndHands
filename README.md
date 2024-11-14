# Introduction 

In this workshop, we will develop a basic understanding on using body models using SMPLX and hand models using MANO

# Pre-requisites

Please ensure the following before attending the workshop

## Google Colab Set up

1) Log in to drive.google.com
2) Create a folder titled "YourPreferredFolderName" and copy the .ipynb files into this location
3) Double click the ipynb file in the google drive to open in Google Colab

## Models

### SMPLX model
1) Create an account at "https://smpl.is.tue.mpg.de/" and agree to license conditions
2) Download version 1.1.0 for Python 2.7 (female/male/neutral, 300 shape PCs) under Downloads section
3) Copy /SMPL_python_v.1.1.0/SMPL_python_v.1.1.0/smpl/models/basicmodel_neutral_lbs_10_207_0_v1.1.0 into "YourPreferredFolderName"
4) Change the name of the model file if needed

### MANO model
1) Create an account at https://mano.is.tue.mpg.de/ and agree to the license
2) Download the model from the "Models & Code" link under downloads
3) Copy MANO_LEFT.pkl and MANO_RIGHT.pkl into "YourPreferredFolderName"

# Simple Hand Mesh Demo

We use mediapipe and optimization techniques to fit a mano model to generate 3d hand mesh from a given image. Check out HandMeshBasic.ipynb for this
