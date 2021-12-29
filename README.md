
# Play T-Rex Dinosaur Game using Hand Gestures

I did this project about 4 years back during my bachelor's . I forgot to push it on github that time so doing it now ;)

## About the Project

Consider this, you’re in the middle of your work, and then suddenly due to some reason the internet stops working due to some router issue you’re informed that it will be fixed in a few hours.

So now you have a couple of hours to kill! .. What would you do?

Like most people you might find yourself playing infamous Chrome’s Dino game that appears on chrome when the internet is not working. 

#### In this project we will see how we can use hand gestures to play the game.

We are going to recognize hand gestures from a video sequence. To recognize these gestures from a live video sequence, 
we first need to take out the hand region alone removing all the unwanted portions in the video sequence. 
After segmenting the hand region, we then count the fingers shown in the video sequence to instruct a robot based on the finger count. 
Thus, the entire problem could be solved using 2 simple step:

    1.	Find and segment the hand region from the video sequence.
    2.	Count the number of fingers from the segmented hand region in the video sequence.


#### Here we are writing a code that will enable us to play the game using hand gestures (code will automatically press the SPACE button when we close our fist and release it when we open the fist)

## Requirements

- Python

        Python is the platform on this complete project is made. The version of this platform must be 2.7 or above.
- OpenCv 

        This is the basis library used in almost every program used in this project. Its version should be either 2.x or 3.x.
- Numpy library

        Used for type conversions, NumPy is a library for the Python programming language, adding support for large, 
        multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.  
## Screenshots

#### Now as we run the code along the Google Chrome’s T-Rex game, the dinosaur will jump if we close our wrist and run (i.e. no input) if we release our hand.

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

