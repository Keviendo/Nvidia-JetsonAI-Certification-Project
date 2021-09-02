# Nvidia-JetsonAI-Certification-Project-For-Kevin-Bishara

# Object detection using Hello AI World and NVIDIA TensorRT 
Hello AI World is used for image classification and object detection all while being transferable onboard the Nano jetson. 
# basic prerequisites


## Jetson Configuration

````
sudo apt-get update
sudo apt-get install git cmake libpython3-dev python3-numpy
````

# Environement Setup Steps 

Clone this repo on your jetson
````
git clone --recursive https://github.com/dusty-nv/jetson-inference
```` 
Switch Directory to jetson-inference 

Make Directory in Build and Configure
```` 
mkdir build
$ cd build
$ cmake ../
$ make
$ sudo make install
$ sudo ldconfig
```` 

## Run This Python Program!
[Screenshot (2)](https://user-images.githubusercontent.com/89232571/131806302-c3fa1595-033a-4551-a703-12f6526f91b1.png)


# Reflection and Improvment
This was my take on using the jetson device. I attempted to track movement of me playing basketball, with a car background. This issue I faced was the camera quality was 1080p so theres too much data and thus the fps drop. Also the basketball movement seemed to fast for the model to handle and thus didn't detect this. For improvement on making this more robust I need to experiment on changing the resolution of each images. I plan on doing more like ML/AI like facial detection however this was a intro on just getting to know embedded linux.
# Youtube Link 
https://www.youtube.com/watch?v=cyRFi8QzfD4
