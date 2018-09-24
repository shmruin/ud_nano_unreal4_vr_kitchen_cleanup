# ud_nano_unreal4_vr_kitchen_cleanup

![Alt text](screenshots/main1.jpg?raw=true "main1")
![Alt text](screenshots/main2.jpg?raw=true "main2")
![Alt text](screenshots/end.jpg?raw=true "end")

# Introduction
Part of udacity nanodegree project, unreal4 virtual reality.
Cleanup the kitchen! Dishes are randomly created. So why not grab them, and throw them to the sink?
Whenver the sink is flushed within the time set, you get the score by the number of dishes in it.

# Version & Environment
 - Unreal4 version 4.15.3
 - HTC Vive, Room scale

# 3rd party features
 -  Oculus Audio Plugin
 -  No other 3rd party features (basic udacity contents)

# User controls
 - Left motion controller trigger : Nothing
 - Right motion controller trigger : Grab/Drop the dish, select the action when end widget is shown.
 - Big red button : reset the game level

# Features
 - Set Global timer and score
 - Interaction with two motion controllers
 - Actions (Grab, Drop, Select, Push)
 - Widgets in VR environment
 - Sound Cues
 - Events (like trigger box)

# Timer
![Alt text](screenshots/timer.PNG?raw=true "timer")
 - in `Assets/player/KCPlayerController`
 - spawn dish timer runs every tick of KCPlayerController
 - Calculate the variable `spawnLeft, and when it comes to zero then reset to `spawnDelay` variable
 - global timer is seperately exist to calculate the global game time left

# License
[MIT](License.md) © [shmruin](https://github.com/shmruin/)

    