# GTA Vice City Object Detection using TensorFlow

It is assumed that you already have following things installed on your machine.
- Grand Theft Auto: Vice City game.
- Python 3.x
- TensorFlow 2.x
- OpenCV
- NumPy

If not already, kindly install these first before you move ahead.

To run the object detection inferences on the game, follow the steps below:

## Steps:
 
1. Clone the repository on your local machine.

2. Install the **MSS** library using ```pip install mss```.

3. Install the **TensorFlow Object Detection API** using ```pip install tensorflow-object-detection-api```.

4. Open the ```label_map_util.py``` file and Edit **Line 132** by replacing ```with tf.gfile.GFile(path, 'r') as fid:``` with ```with tf.io.gfile.GFile(path, 'r') as fid:```. 
You will find this file in the following path: ```C:\Users\<your-username>\AppData\Local\Programs\Python\Python37\Lib\site-packages\object_detection\utils```

5. Open the **GTA: Vice City** game. In the display settings of the game, change the screen to windowed mode and preferrably set the resolution to 1024x768.
 
6. Open command prompt and run ```vice_city_detection.py``` and enjoy playing GTA: Vice City with real-time object detection.


## Demo Output:

![GitHub Logo](Output.gif)
