# Biometric-Palmprint-Authentication
This is an authentication technique using hand palm images

### Sample collection methods
Here is a sample image given for the reference . Sample images are not provided for security purpose 
The images must be captured in this format with a dark background and hand orientation must be straight so that the middle finger appears to be the longest in the hand
This will help to get best result of the algorithm

### Sample image name format
Images must be names in the following format user_X_Y.jpg where X signifies the user number and Y signifies the sample number.
user_4_5.jpg signifies 4th user and 5th sample. 
All the imgaes of all users should be stored into Hand_images folder. 
50 images of each user was used as real and 50 images of other user were used as fake for training. More fake images can be used to get better accuracy
prefix c_90 means clockwise rotation by 90 degree
prefix cc_90 means counter-clockwise rotation by 90 degree
prefix _180 means 180 degree rotation
images of a user is stored into 3 folders inside the user_X folder . Positive for real images , Negative for fake images , Anchor for reference input images


