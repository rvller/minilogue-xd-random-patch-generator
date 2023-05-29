# This is a repo for a random patch generator for Korg Minilogue XD
It's built using the PureData app (tested on 0.51-4 version on MacOS). 
This code is licences under Apache License Version 2.0 - so you can use it accordingly.

### How to run
* Download the PureData app from https://puredata.info/downloads
* Download the minilogue-xd-random-patch-generator.pd from the Git repo
* Open the minilogue-xd-random-patch-generator.pd file in PureData
* Connect the Korg Minilogue XD to your computer via USB cable
* Configure the Midi channel on Minilogue XD (Channel 5 is used by default)
  * You can change the Midi channel in the minilogue-xd-random-patch-generator.pd file in the "Midi channel element" (by pressing cmd+e to edit PD file)
* Configure Midi output device in Puredata - Media -> Midi settings... -> Output devices -> "minilogue XD SOUND"
* Press **TAB** button to generate the random value for the Minilogue XD's patch
* Have a fun!

### What is there
* It can generate random values for almost all Minilogue XD's parameters
* You can switch on/off the randomization for specific parts ti your taste:
  * "sync/ring/cross mod rand"
  * "enable lfo rand"
  * "enable multiengine rand"  

### Feedback

Feel free to drop your suggestions at rvller@gmail.com

### Useful links

* Screenshots with help - https://github.com/rvller/minilogue-xd-random-patch-generator/wiki

* Korg Minologue XD Owner's guide (with Midi implementation chart) - https://cdn.korg.com/us/support/download/files/1362ee55daa0ec780da684b9ad9ad99b.pdf
