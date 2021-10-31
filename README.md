# BeltDrivenEnder3

<img src="Pictures/BD_V3.jpg" width="400"/> <img src="Pictures/Top_remix.jpeg" width="400"/>

---

## Please read Instructions and BOM for more informations.

Written Intructions will be updated soon! Please use my videos in the meantime.
Feel free to contact me on Discord: kevinakasam#2097

Huge thanks to my mate Deutherius, who helped me over months, tested everything and brought this mod to perfection. Many thanks for the help, the photos and the new heated bed!

Attention!
I'm not an expert and 3D printing is my hobby. So please be careful when you rebuild this printer and don't just go ahead. For my printer the parts fit perfectly.
Everybody bears the risks of a modification himself.
All parts can be modified as you like.

First things first:
My Ender 3 always had problems with the Z-axis, which were caused by a bent and misaligned leadscrew. Therefore I decided to convert the Ender to belts in Z as well.
This mod also solves the problem of a hanging x-axis on the right side. Because of the two belts both sides run synchronously and can also be adjusted very precisely.
So if you have these problems with the z-axis/x-axis, this is a good solution.

Good luck and happy printing!

## Table of contents
1. [Thank you very much!](##thank-you-very-much)
2. [Print Showcase](##print-showcase)
3. [Video Tutorials](##finally-the-video-tutorials-are-finished)
4. [KeyBack](##KeyBack)
5. [FAQ](##FAQ)
6. [Troubleshooting](##troubleshooting)
7. [Changelog](##changelog)


## THANK YOU VERY MUCH!
I want to thank everyone who has helped me over the last months with feedback, support and confidence. Without you this mod would not have become so big! Thanks also to Creality for the Golbal DIY Contest. I am very proud to announce that I could reach the 3rd place with.

<img src="https://github.com/kevinakasam/BeltDrivenEnder3/blob/main/Pictures/Contest.jpg" width="450">

## Print Showcase
<img src="Pictures/Benchy.jpg" width="400"/> <img src="Pictures/Benchy_1.jpg" width="400"/>
<img src="Pictures/Benchy_Blue.png" width="400"/> <img src="Pictures/Benchy_error.jpg" width="400"/>
<img src="Pictures/ABS.JPEG" width="400"/> <img src="Pictures/IMG_3936.JPEG" width="400"/>

## Finally the video tutorials are finished!
[![Video Tutorial](Pictures/thumbnailwheel.jpg)](https://youtu.be/bxTwFCPEIgg)

https://youtu.be/bxTwFCPEIgg

[![Video Tutorial](Pictures/ThumbnailMGN.jpg)](https://www.youtube.com/watch?v=oUdoJUs8Zcg)

https://youtu.be/oUdoJUs8Zcg

## KeyBack
#### Files are currently untested! Please give me feedback when you installed the KeyBack (Discord: kevinakasam#2097)

<img src="Pictures/KeyBack_1.png" width="400"/> <img src="Pictures/KeyBack_2.png" width="400"/>

KeyBack system similar to the Switchwire design.
The files were remixed from the Switchwire CAD file.
For licensing reasons, all KeyBack files are uploaded to GitHub only!
Idea from Voron team, thanks!

Info: Because of the transmission it is not necessary to install a KeyBack system.
The 1:5 ratio increases the holding force of the motor so that it can hold the X axis up even when it is powered off.
A correctly adjusted belt tension is important for this.
If you are using the V-Wheels it is also important that they are installed correctly (See Troubleshooting).
From time to time I hear that users struggle to keep the axis up by using the belt tension only.
Therefore, I have designed the KeyBack system. See BOM for all the parts you need.

What is a KeyBack system and what is it for?
A KeyBack is actually used to secure keys to a wire rope.
Depending on the Keyback, they can support a lot of weight without the cord extending on its own.
The KeyBack used here is strong enough to support the x axis. It takes the load off the motor and shares the weight of the axis with it.
__It is still important to tension the belts properly!
If the belts are not tightened enough, there will be unclean prints later!__
So make sure that the KeyBack doesn't mislead you into not tightening the belts enough.
See my FAQ video on how to properly tension the belts (video coming soon).

You will have to print a new 1_LeftTop_A and a 3_spacer to use the KeyBack.

## FAQ 
### Do I need to change the firmware?
NO! You do not have to change anything in the firmware. This modification works with the stock board and stock firmware.

### Can I use PLA to print the parts?
Yes and no. All parts should work with PLA, except the motor tensioner arm. The motor has to hold more weight now, so the motor could get warm. Since PLA deforms at ~40°C you should keep an eye on your motor (see troubleshooting). Because of that I would recommend PETG. When you're printing inside an enclosure you should use ABS. Try Esun ABS+, super easy to print, and much stronger than PETG.

### Is this mod also compatible with the Ender 3 V2/Pro etc?
YES! You can use this mod with all Ender 3 versions.

### Can use this for my Creality CR printer?
View the makes on Thingiverse. Some of you made a CR build so I thing it should fit. Feel free to give some feedback about that.

### Do I need a hardened steelrod?
NO! A cheap aluminium or "normal" steelrod is just fine. There's also a transmission (rotated and unrotated) that hold a bearing inside, so you have some extra support in the middle of your rod. You also could use your leadscrew to minimize the costs.

### Dual Z? G34?
So you want to use two stepper motors to have an indipendent z axis? Thats possible of course! Just use the tranmission body with the bearing inside and two shorter rods (100mm should fit). This way the two tranmissions support the inner end of each rod and the Top parts the outer end (as normal). You also could mirror one transmission body to have a symmetric setup.

### I have a special question/ I need a custom version but I'm new to CAD. Can you help me?
Yes of course! I'm happy to help, so please contact me via Discord (kevinakasam#2097). I'm sure we will find a solution for your problem :)

## Troubleshooting
### My Z motor moves in the wrong direction!
Thats a quick fix. Just remove all the pins in you motor connector that goes into the mainboard (like I showed you in my video) and insert them in the opposite order (4321 instead of 1234).

### My Z motor gets super hot!
First of all: A warm or slighty hot motor isn't a super bad thing. But you should change that. Try to lower your V-ref/Amps till the motor stays hand warm. But be careful to not reduce the current too much, or your motor will lose steps. The stock Z motor is very small so it's a big job for the tiny motor. Don't worry if your motor gets warm.

### My z axis drops as soon as power off my printer!
Probably the most asked question, but I can promise that your axis does not have to drop! As already mentioned, the z motor is very small. Therefore the magnetic field that exists in the motor even without power isn't very strong. But it's strong enough to keep the axis up.
#### I don't care, my axis is dropping, what can I do?
1. You are using the original V-Rollers? Be sure they are properly set up. Turn the eccentric nut until the rollers are in contact with the profile. Put a little tension on the rollers, but not too much! Do not risk a flat spot of your rollers. The tension is correct when they are tight, and you can't turn them with your finger in the same place, but the axis moves when you turn the rollers.
2. You have no rollers or your axis is still dropping? Tension your long belts a little more. Increase the tension until your axis stops dropping. Be careful not to break something. But the parts can take a lot of tension. Otherwise, check out my FAQ video about how to tension the belts (THE VIDEO HAS STILL TO BE CREATED).
3. Tension the small looped belt a bit more as well. But very carefully! Usually the tension only needs to be high enough to keep the belt from slipping over the printed wheel. But you can increase the tension a little bit. But not too much, otherwise the motor can't turn anymore.
4. That sounds too complicated? Your motor is also too hot? A solution would be a bigger motor, like the one on the X and Y axis. A bigger motor is able to hold the axis up very easily, with less tension and less heat. But as I said, this is not necessary, it also works with the original motor.

---
### Changelog:
31.10.2021: Big Update!
- Moved the extruder to the stock position for the V3.4_Bowden plates (Fits BMG now too). Idea from trohnjavolta, thanks!
- Split the tops into two parts to make them easier to print and more stable (Top_A and Top_B). Idea from sztywniutko (Thing:4911634), thanks!
- Added a KeyBack system similar to the Switchwire design. The files were remixed from the Switchwire CAD file. For licensing reasons, all KeyBack files are uploaded to GitHub only! Idea from Voron team, thanks!

17.08.2021: Made some small tolerance changes to the rotated transmission and the inner M3 parts.

31.07.2021: I made a mistake and uploaded the wrong files for "LeftTop" and RightTop". If you downloaded the files from Thingiverse between 15.06.2021 and 31.07.2021, please download the latest version. I am very sorry! Thanks to mbarryton for the hint!

15.06.2021: **Important!!!** Both Versions (rotated and unrotated) are compatible now. Both versions now have the identical LeftTop and RightTop (the one from the rotated version).

15.06.2021: I have added a version of both transmissions that include a ball bearing. So the rod is supported in the middle by another ball bearing.

15.06.2020:  Updated CAD with all Versions. Many thanks to Regulus who did a great job adding many wonderful details to the CAD file. All parts are now properly aligned, all fasteners are added and named. Seriously many many thanks!

02.06.2021: Added Left and Right V3.3. Changed the design of the lower clamp profile. If youre using the 3.1 or 3.2 that's totally fine;)

02.06.2021: Updated the 80T Gear on GitHub. reduced the outer diameter a bit so theres a bigger gap to the profile. Thanks to Regulus!

06.05.2021: Modified MGN Version fits now for Ender 3 (Pro) and Ender 3 V2. Bowden Version tested. Thanks to Jon!

04.05.2021: Added a Video Tutorial.

02.05.2021: Added Left and Right V3.2. Tensioner were missaligned by ~0.5mm. Thanks to Zardozer for the hint! If youre using the old V3.1 its totally fine. I'm using them as well:D

14.02.2021: Changes for the MGN Version!! LeftV1 added. Please print 1_Left and 1_LeftV1. I would appreciate feedback for Left or LeftV1. I have created the files with the official CAD, but the M4 screws differ in the position by 2mm. Please print both versions and tell me which fits, thanks:)

26.02.2021: Added Bowdenversion.

26.02.2021: Started Changelog.

---

# V-Wheel Version
<img src="https://github.com/kevinakasam/BeltDrivenEnder3/blob/main/Pictures/RollerVersion.png" width="700">

# MGN Rail Version
<img src="https://github.com/kevinakasam/BeltDrivenEnder3/blob/main/Pictures/RailVersion.png" width="700">
