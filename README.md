# bad-apple
 Bad Apple printed out on the console with Python!

![Bad apple!!](bad_apple_gif.gif)

# Preface
A word of disclaimer, while the final code is somewhat original, this project is an amalgamation of different code snippets that I found online. As the main YouTube Video begins to gain traction, I feel the need to inform the audience that this code is NOT ENTIRELY ORIGINAL. 

The concept of playing Bad Apple!! on a Command Line Interface (CLI) is not a novel idea and I am definitely not the first. 

There are many iterations and versions around YouTube and I wanted to give it a shot. The intent of posting the video on YouTube was to show a few friends of a simple weekend project that I whipped up in Python. 

My own video can be found [here](https://www.youtube.com).

# Running this code/Pre-requisites

You can either `git clone` or download a ZIP of this repository. 

`git clone https://github.com/vikasbairagi786/bad-apple`

Then, ensure that you set your terminal to the directory of this repository. 

`cd bad-apple`

Install the necessary dependencies and packages by using:

`pip install -r requirements.txt`

And to run the code:

`python touhou_bad_apple_v4.0.py`

And just follow the on-screen prompts. 




# Functions
The main functions will be listed here. 

## play_video()
Reads the files from the previously generated ASCII .txt files and prints it out onto the console. 

## play_audio()
Plays the bad apple audio track. 

## progress_bar(current, total, barLength=25)
A simple progress bar function that generates the status of both frame extraction and ASCII frame generation. 
This code was taken from a [StackOverflow thread](https://stackoverflow.com/questions/6169217/replace-console-output-in-python).

`current` is the current value/progress of the process. 

`total` is the desired/intended end value of the process.

`barLength=25` sets the length of the progress bar. (Default is 25 characters)

## ASCII Frame generation
Not a particular function, but a group of functions.

```
resize_image()

greyscale()

pixels_to_ascii()
```
These functions are called in the `ascii_generator()` function to convert image files to ASCII format and stores them into .txt files. 

Note that the ASCII conversion code is not original, and was taken from somewhere.


# Contributing ✨

Pull requests are welcome. If you have any idea or suggestions or issues please open an issue first to discuss.

Thank you :)

 

