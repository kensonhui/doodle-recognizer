# doodle-recognizer
ML5 javascript drawing canvas that loads yining1023's doodleNet machine learning model and guesses what the user draws with 345 cateogries

# Instructions
In order to use this, you will have to start a local server within the doodle-recognizer folder. I have found npm http-server to be the most convient but it is up to preference. 

Then go to http://localhost:8080/ or whichever port number you have specified.

The canvas will be in the top left and is 400 by 400 pixels, the doddleNet model runs continuously and produces its 10 highest confidence guesses.
