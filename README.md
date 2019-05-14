# LazyLights
My attempt at a simple bluetooth remote light switch using an Android app and Arduino Nano.

## WARNING: I DEAL WITH MAINS POWER IN THIS PROJECT SO IF YOU DON'T KNOW HOW TO USE THE CIRCUIT BREAKERS IN YOUR HOUSE DON'T ATTEMPT THIS

## Part 1: Android App

The main function of this app was just to send the numbers 0 or 1 to the Arduino via blueooth to be read through the Serial port. These numebrs encode the state in which the light should be. The app was originally built to turn on and off the lights with a button but I decided to speed up the process further by activating this function once upon opening the app such that the moment it loads the lights will turn on or off.

I built this using Android Studio so I have only uploaded the main files so just start up a new app to generate the other files and replace the appropriate files.

## Part 2: Arduino Nano

I used an Arduino Nano just for convenience as it is easy to fit near my light switch but pretty much any Arudino can work for this purpose. The only other components needed are a relay to control the AC current of your light switch and a bluetooth module for connecting to your phone
