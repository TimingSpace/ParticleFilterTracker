# ParticleFilterTracker
OpenCV based particle tracker

## based  on the method introduced by http://blog.csdn.net/jinshengtao/article/details/30970733

1. I change the method with a openCV c++ interface which make it easy to use Mat and so on
2. I define a class which include all function(method), you can use the tracker just by including the .h file


## based OpenCV

## compile 
g++ testpf.cpp -o pfTracker `pkg-config --libs opencv --cflags`

## run
./ pfTracker to track something in camera

## usage
1. press 'i' to initial with dray mouse
2. press any key to track
3. press 'q' to quit

