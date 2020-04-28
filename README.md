# Face-Recognition
Face Recognition System that can be trained to recognize and verify faces efficiently with only 2-4 pictures of person. 
Used One Shot learning to implement the system.


## Steps to use:

### For Setup, run following commands on terminal:

- git clone https://github.com/anuragjoshi3519/Face-Recognition.git
- cd Face-Recognition
- pip install virtualenv
- virtualenv -p /usr/bin/python3 env
- source env/bin/activate
- pip install -r requirements.txt

### Functions to call:

- **$ python face_collect_data.py** : To save your face image in database
- **$ python recognize_me.py** : To let the system recognize you.
