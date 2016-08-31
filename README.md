# Raspberry Pi
This is just a collection of tips and tricks coming handy when working with the Raspberry Pi 3.

Remote control
ngrok
https://kodyvajjha.wordpress.com/2015/06/24/ssh-ing-into-the-raspberry-pi-over-the-internet/

##OpenCv
Install guide: Raspberry Pi 3 + Raspbian Jessie + OpenCV 3
http://www.pyimagesearch.com/2016/04/18/install-guide-raspberry-pi-3-raspbian-jessie-opencv-3/


Tensorflow
----------
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

Docker
------
While we’ve noticed people using Docker on Raspberry Pi for a while now, the latest release officially includes Raspbian Jessie installation support. You can now install the Docker client on your Raspberry Pi with just one terminal command:

curl -sSL get.docker.com | sh

From there, you can create your own container or download pre-made starter containers for your projects. The documentation is thorough and easy to follow. You can also follow this Pi-focused guide by Docker captain Alex Ellis.

https://docs.docker.com/engine/understanding-docker/
http://blog.alexellis.io/getting-started-with-docker-on-raspberry-pi/
