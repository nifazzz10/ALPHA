# people counter
schedule==0.6.0
numpy==1.19.2
argparse==1.4.0
imutils==0.5.3
dlib==19.18.0
opencv-python==4.2.0.32
scipy==1.4.1
install of the libraries for dlib make sure you have cmake and conda lib
after in stallation run the run.py
and  dont run this on latest version of python run on 3.8 ver
so only dlib can be installed on it.
after installation run the program run.py

To run inference on a test video file, head into the directory/use the command:
and paste this :
python run.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input videos/example_01.mp4


Setup your camera url in 'mylib/config.py':
# Enter the ip camera url (e.g., url = 'http://191.138.0.100:8040/video')
url = ''
