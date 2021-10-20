AIR CANVAS 

‘Air Canvas’ is a program that will help us to achieve a hands free drawing program using open CV by detecting a user's pointer finger. Colourful lines or words or any shape can be drawn wherever the user desires to and wishes on the canvas. It is truly drawing in the air. 

To run the code attached with this readme.txt file you need to install pycharm in your device, you can download the community version of pycharm from: https://www.jetbrains.com/pycharm/download/#section=windows site.

Then once you have installed it you will need to install some libraries. The process for the same is:
File < Settings < Project: (Project Name in this case Air Canvas) < Python Interpreter < Select the appropriate interpreter and add the following libraries: opencv-python and mediapipe < Click on Okay 

The header photos are in the file attached with this one named 'Header'.

There are two code files attached too, one of them is 'HandTrackingModule.py' and other one is 'VirtualPainter.py', the 'HandTrackingModule.py' will help us track our hand movement and fetch the necessary points on our hands to perfectly track it and let us draw whereas the 'VirtualPainter.py' will help us draw with one finger and select different colours with 2 fingers.