# Nvidia-JetsonAI-Certification-Project-For-Kevin-Bishara

# Object Detection Using Hello AI World and NVIDIA TensorRT 
Hello AI World is used for image classification and object detection all while being transferable onboard the Nano jetson. 

## Jetson Input Commands

````
sudo apt-get update
sudo apt-get install git cmake libpython3-dev python3-numpy
````

# Environment Setup Steps 

Clone this repo on your jetson
````
git clone --recursive https://github.com/dusty-nv/jetson-inference
cd jetson-inference
```` 

Create Directory in ~/build and Configure
```` 
mkdir build
$ cd build
$ cmake ../
$ make
$ sudo make install
$ sudo ldconfig
```` 

## Run This Python Program!
![alt text](https://user-images.githubusercontent.com/89232571/131806302-c3fa1595-033a-4551-a703-12f6526f91b1.png)
Choose a resolution that will best fit your needs



# Summary
Using the Nano Jetson I was able to code a python program which allowed me to use TensorflowRT and a webcam (Logitech C270) to perform simple object detection and labeling. Initially I set my resolution to 1080x720 which is what the camera is able to process at 30fps but upon running the program the jetson mysteriously lost hdmi connection and shut off indicating a sort of protective shut off due to possibly the large monitor display and set resolution. Changing the resolution to 800x600 fixed this issue and the program succesfully detected and labeled various objects succesfully.


# Link To Video 
https://www.youtube.com/watch?v=drfO8qz6SaE&ab
