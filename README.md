We have created a mouse controller using Python and OpenCV with real time camera that detects hand landmarks , track gesture patterns instead of physical mouse. 
We will first detect the hand landmarks and then track and click based on these points.
For cursor movement we will use our index finger
For performing click we will take index and middle finger together.
We will also apply smoothing techniques to make it more usable. 

Steps to be followed:-

Step 1: We will very first find the hand landmarks and finger tips.

Step 2: We will find the tip of the index and middle fingers.

Step 3: We will check which fingers are up.

Step 4: We will check whether our virtual mouse is currently in moving mode or clicking mode

Step 5: If only index finger is up then our virtual mouse is in moving mode and we can move our mouse with our index finger tip with the help of autopy.

Step 6: If both index finger and middle fingers are up then our virtual mouse is in clicking mode.

Step 7: For clicking we will move our index and middle fingers closer to each other.


Libraries we have used:-

OpenCV:-  OpenCV is used for  image processing and drawing.

Autopy:- For controlling the mouse movements and for  performing clicks. Autopy have several function which will control the mouse movements.

Numpy :- Numpy is used to perform certain mathematical calculations and for working with arrays. 

Time:- Used to calculate FPS (Frames per Second).



