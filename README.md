# Trippy-Vid 😵‍💫 
Program to turn video into a 3 dimensional volume of images. Using slice maps to create trippy effects

🧨 THIS APPLICATION ISN'T YET IN A WORKING STATE 🧨

Inspired by ["video is 3D. not 3D"](https://www.youtube.com/watch?v=NZFxQXe7LMM)

This commmand line utility aims to create a tool that can easily produce the effect in the video.
Originally this project started as an easy artwork creator for my collection of urban videos but eventually supporting more features than just easy video conversion.


### 📈 Current status
Currently the main feature being worked on is "video splitting - frame by frame"

### 📭 Installation
To install this app you can either download from the [Releases](https://rubennijhuis.com) or install and compile manually. ‼️(This process assumes you have CMake installed)‼️
```bash
  Cloning:
  $ git clone https://github.com/rubennijhuis/trippy-vid

  Compiling:
  $ git clone https://github.com/rubennijhuis/trippy-vid
```
### 🛠 Usage
```bash
  Creating a Trippy-Vid™️:
  $ ./trippy_vid path_to_video path_to_depth_map
```
### 🎉 Features
Using a depth map of the same size as the video the desired effect can be created.

### 📝 Notes
I don't know much about ffmpeg video codecs and C++ so take this codebase as a way of not coding.
Happy coding :)