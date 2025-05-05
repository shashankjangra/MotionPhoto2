These are the requriements that need to be taken care of but for now they have been taken care of.

brew install exiftool 
exiftool -ver  
python3 --version                                                                           
pip3 install -r requirements.txt   

This is the command to keep the image, video files and generate the live one.

python3 motionphoto2.py --input-directory Sample                                                


Directly run this if you have the same mac.
This not only makes the right thing but also deletes the image and video.

python3 motionphoto2.py --input-directory Sample --overwrite --delete-video                     