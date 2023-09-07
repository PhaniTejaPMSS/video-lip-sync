# video-lip-sync
A deep learning model that syncs the lip movements of the speaker in a video with the input audio given


# Description
Used wav2lip model for this project which is one of the best models for lip sync of videos for the given audio input given.


# Prerequisites
Python 3.6
ffmpeg: sudo apt-get install ffmpeg
Install necessary packages using pip install -r requirements.txt. Alternatively, instructions for using a docker image is provided here. Have a look at this comment and comment on the gist if you encounter any issues.
Face detection pre-trained model should be downloaded to face_detection/detection/sfd/s3fd.pth. Alternative link if the above does not work.


# Steps to run the model 
Clone or download this repository in your system or in google colab.
Save the model checkpoint given in the repo at an appropriate location and change the location of it while running the model.

