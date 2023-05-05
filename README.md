# C2HO
Creative Computing Competition 2023, Audio-visual artwork, Brain activity

Code for creating audio-visual artwork submitted to the Creative Computing Competition 2023, Oslo, Norway.

#### The script generates audio-visual artwork by sonifying and visualizing brain activity recorded in the cortex of an awake/unconscious mouse. 

#### The input data represent the timing of electrical impulses recorded simultaneously across superficial and deep layers of the mouse cortex. 

#### The location and electrical activity of each recording position is visualized by plotting  a series of vertically arranged circles, which vary in color and size depending on the rate of electrical impulses (superficial layers correspond to circles at the top, deep layers to circles on the bottom). Plots are converted to a mp4 video file. 

#### For sonification, data are mapped to MIDI notes and converted to a .wav file. Finally, audio and video files are merged (mp4).
