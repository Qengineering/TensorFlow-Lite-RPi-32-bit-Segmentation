# TensorFlow_Lite_RPi_32-bits Segmentation
TensorFlow Lite running at 4.0 FPS on bare Raspberry Pi 4

A fast C++ implementation of TensorFlow Lite Unet on a bare Raspberry Pi 4.
Once overclocked to 1900 MHz, the app runs at 4.0 FPS!

https://arxiv.org/abs/1606.00915 <br/>
Training set: VOC2017 <br/>
Size: 257x257 <br/>
Frame rate Unet Lite : 4.0 FPS (RPi 4 @ 1900 MHz - 32 bits OS) <br/>
Frame rate Unet Lite : 7.2 FPS (RPi 4 @ 1850 MHz - 64 bits OS) <br/>
<br/>
Special made for a bare Raspberry Pi see: https://qengineering.eu/install-tensorflow-2-lite-on-raspberry-pi-4.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/TensorFlow-Lite-RPi-32-bit-Segmentation/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
cat.jpg.mp4 <br/>
deeplabv3_257_mv_gpu.tflite <br/>
TestUnet.cpb <br/>
Unet.cpp<br/>
 <br/>
Run TestUnet.cpb with Code::Blocks. Remember, you also need a working OpenCV 4 on your Raspberry. <br/>

![output image]( https://qengineering.eu/images/Unet_32.jpg )
