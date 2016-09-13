# Raspberry Pi
This is just a collection of tips and tricks coming handy when working with the Raspberry Pi 3.

###Getting started  
http://blog.jongallant.com/2016/09/raspberry-pi-nodejs-base-image.html
https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/quick-start/   
https://paulstamatiou.com/getting-started-raspberry-pi/   

###Reading sensor values
https://www.raspberrypi.org/forums/viewtopic.php?t=95017&p=662870

###Watson
Connect a Raspberry Pi to IBM Watson IoT Platform  
https://developer.ibm.com/recipes/tutorials/raspberry-pi-4/
Build an IoT Bluemix app in Node.js with sensors on Raspberry Pi  
https://developer.ibm.com/recipes/tutorials/build-an-iot-bluemix-app-in-node-js-with-sensors-on-raspberry-pi/

###Remote control
ngrok   
https://kodyvajjha.wordpress.com/2015/06/24/ssh-ing-into-the-raspberry-pi-over-the-internet/

###OpenCv
Install guide: Raspberry Pi 3 + Raspbian Jessie + OpenCV 3
http://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/

###Tensorflow
For Python 2.7
$ sudo apt-get install python-pip python-dev

For Python 3.3+
$ sudo apt-get install python3-pip python3-dev

For Python 2.7
$ wget https://github.com/samjabrahams/tensorflow-on-raspberry-pi/raw/master/bin/tensorflow-0.9.0-cp27-none-linux_armv7l.whl
$ sudo pip install tensorflow-0.9.0-cp27-none-linux_armv7l.whl

For Python 3.3+
$ wget https://github.com/samjabrahams/tensorflow-on-raspberry-pi/raw/master/bin/tensorflow-0.9.0-py3-none-any.whl
$ sudo pip install tensorflow-0.9.0-py3-none-any.whl


TensorFlow-Examples   
https://www.tensorflow.org/versions/r0.7/tutorials/mnist/beginners/index.html   
https://github.com/aymericdamien/TensorFlow-Examples   
https://github.com/aymericdamien/TensorFlow-Examples/blob/master/notebooks/0_Prerequisite/ml_introduction.ipynb

Div PDF's  
https://cs224d.stanford.edu/lectures/CS224d-Lecture7.pdf  

Learning Tensorflow   
http://www.learningtensorflow.com

###Docker
While we’ve noticed people using Docker on Raspberry Pi for a while now, the latest release officially includes Raspbian Jessie installation support. You can now install the Docker client on your Raspberry Pi with just one terminal command:

curl -sSL get.docker.com | sh

From there, you can create your own container or download pre-made starter containers for your projects. The documentation is thorough and easy to follow. You can also follow this Pi-focused guide by Docker captain Alex Ellis.

https://docs.docker.com/engine/understanding-docker/
http://blog.alexellis.io/getting-started-with-docker-on-raspberry-pi/

### Raspberry Pi, Camera and Node.js – Live Streaming with Websockets IoT  
http://thejackalofjavascript.com/rpi-live-streaming/

### Chrome  
    wget -qO - http://bintray.com/user/downloadSubjectPublicKey?username=bintray | sudo apt-key add -
    echo "deb http://dl.bintray.com/kusti8/chromium-rpi jessie main" | sudo tee -a /etc/apt/sources.list
    sudo apt-get update
    sudo apt-get install chromium-browser rpi-youtube -y
    
### The Pi Camera   
[Link to page] (http://www.rs-online.com/designspark/electronics/eng/knowledge-item/raspberry-pi-camera-setup?/designspark/electronics/knowledge-item/raspberry-pi-camera-setup=)   
On Windows:   
[Path to nc.exe]\nc.exe -L -p 5001 | [Path to mplayer.exe]\mplayer.exe -fps 31 -cache 1024 -

On Pi:   
pi@raspberrypi:~ $ sudo raspivid -t 999999 -o -| nc 192.168.10.146 5001

### Alexa
https://github.com/amzn/alexa-avs-raspberry-pi

### GTX 1080
http://textminingonline.com/dive-into-tensorflow-part-iii-gtx-1080-ubuntu16-04-cuda8-0-cudnn5-0-tensorflow


