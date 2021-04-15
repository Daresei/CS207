# The Arduino Fightstick
##### For CS 207 at The University of Regina

## Fightsticks for PC


- Inspiration for Project:
There are multiple quality fight sticks out there, from Etokki, Razer, Hori, and MadCatz, each one of these brands will run a person around $250 CAD. Which seems like an expense that could be avoided on an arcade fightstick you may not feel comfortable on. That's why I thought it would be best to create my own fight stick, one made just for me, by me.
It may seem like creating a whole arcade stick on your own is an impossible task, though through these resources, it was made relatively easy for myself, and possibly, for you!

  1. [NewEgg](https://www.newegg.com/insider/so-you-want-to-build-an-arcade-stick/) Has a beginner's guide to building an arcade stick!
  2. [Instructables](https://www.instructables.com/Arduino-FightStick/) Has a project by author JamesT107, which I found very useful.
  3. [DIY Youtube Tutorial](https://www.youtube.com/watch?v=L9NYNwv0HYk) I found this project helpful in creating a sturdy wooden box that would last.



## STEPS
#### Step 1: Dependencies
- You are able to set up this device on any working computer that can run the Arduino program and has a USB port to connect to the Arduino itself.

#### Step 2: Materials
- For this project I wanted an eight button and one arcade stick. I purchased my buttons and joystick from [ParadiseArcadeStick](https://paradisearcadeshop.com/)
- For wood, I was lucky enough to have my own spare wood from previous projects to work from.
- Solder and a Soldering Irons can be purchased from your local tech shops, or can be purchased from [Amazon](https://www.amazon.ca/)
- The Arduino Uno which we used in class, can also be purchased [here!](https://store.arduino.cc/usa/)
- To connect the arduino to your computer you may need an extension cord such as this one [here!](https://www.newegg.com/black-startech-1-ft-usb-2-0/p/N82E16812200477)

#### Step 3: Designing
- For button layouts and designs I found this very interesting site called [SlagCoin](http://slagcoin.com/joystick/layout.html).
  I chose a layout and flipped it, as I use my left hand to control the buttons, which is reverse of a standard arcade stick    layout.

There is a really good blog post by Terntek. found [Here!](http://terntek.com/blog/blog/2017/08/01/how-to-build-an-arcade-stick-for-pc-or-retropie/)

#### Step 4: Assembly
- This part came second nature to me, but I realize that that is not the case for all people.
- There are many different tools needed to make a box which is similar to the one I have created. These tools include:
* Drill
* 30 mm forstner drill
* Table saw
* Wood glue
* Wood stain
* Screws
- While assembling this project, I noticed how absolutely heavy the box was. This can be a plus if you do not plan on moving the box much, which in my case was quite a positive. Though, using light weight woods make the board slightly less sturdy, the tradeoff for transportability may be worth it.


## Programming the Arduino
For this part in the project, I directly searched and used the open source project called [UnoJoy](https://code.google.com/archive/p/unojoy/downloads).

I was able to navigate through the folders and found the example "BasicFightStick". Though it was not fully compatable with the design I wanted. This code is great if you plan on making a 6 button arcade stick, but needs a few extra lines to make it compatable with an 8 button arcade stick.

The necessary files can be downloaded here:
* [UnoJoy](https://github.com/Daresei/CS207/blob/main/UnoJoy.h)
* [FightStickEightButtons](https://github.com/Daresei/CS207/blob/main/FightStickEightButtons.ino)


### Experiences and Issues
  The project, though it was rather slow waiting for the parts to come in, went by rather smoothly. Creating the box was really fun to design and try to perfect it to fit my needs. The coding was a little troubling, as it is the weakest part of my applied skillset. Though, there were many online resources which I used to help me achieve the final product.
  
#### Further Implementation
  If I could have, I would have added a system which monitors my inputs and allows me to view them in real time. (Also adding some cool LED lights to them would have been a nice addition.) Though, all in all, I doubt I will add more to this. It works well and has no (that I can find) issues.

## Summary
- This project was really fun to work on. I would definately recommend it to others as well, for anyone who may want to devle into playing either fighting games, or old retro arcade games.


Video Link
