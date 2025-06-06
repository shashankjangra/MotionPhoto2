These are the requriements that need to be taken care of but for now they have been taken care of.

brew install exiftool 
exiftool -ver  
python3 --version                                                                           
pip3 install -r requirements.txt   

If it does not get installed directly, what we can do is use the commands that I'm going to mention now.:
# Step 1: Create a virtual environment
python3 -m venv venv

# Step 2: Activate it
source venv/bin/activate

# Step 3: Install lxml inside it
pip install lxml

These commands will create a virtual environment, and this virtual environment will be able to run the task that is required at hand without installing any fancy stuff. 

This is the command to keep the image, video files and generate the live one.

python3 motionphoto2.py --input-directory Sample                                                


Directly run this if you have the same mac.
This not only makes the right thing but also deletes the image and video.

python3 motionphoto2.py --input-directory Sample --overwrite --delete-video