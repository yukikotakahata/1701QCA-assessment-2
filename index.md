# 1701QCA Making Interaction - Assessment 2 workbook


**# Playng a sound Gym ball  #**

## Related projects ##



### 1.Bop it ###

![Image](bopit1.png)
![Image](bopit3.png)
![Image](bopit2.png)
</br>
[How to play Bop it] *https://youtu.be/ayBmsWKqdnc*
*This project is related to mine because my project is "musical instrument which react to physical movement". "Bop it" is a classic interactive party toy. All new Bop It calls out commands, the player reacts fast.  It is a game in which sound and body movements linked closely. 
ex;
"Bop It!" becomes the sound of a bass drum.
"Spin It!" becomes the sound of a wobbling wheel.
"Flick It!" becomes a "Boing!" sound.
"Pull It!" becomes the sound of a slide-whistle.
"Twist It!" becomes a cranking sound.
"Shout It!" becomes a DJ's scratching sound.*
</br>
### 2.Gym ball cover sewing project ###

![Image](ballcover1.png)
![Image](ballcover2.png)
*This project is related to mine because this gave me the idea of fabrication. Initially, it seemed impossible to attach the microbit device on the gym ball. After this finding, it became  worth giving it a try with a project.*
[How to make yoga ball cover]  https://www.newlittlelife.com/2016/03/12/diy-birth-ball-cover/
</br>
### 3.Failylight ballon ###

![Image](failylight.png)
  This project is related to mine because lighten up the ball is another feature. This product is a general consumer product and, pretty popular.
</br>
### 4.LED bouncie  ###
![Image](bouncie.png)
  This project is related to mine because, if the light turns on accordant with the ball's movement is perfect.</br>
[how to make bouncy ball] *https://www.instructables.com/id/LED-Bouncie/*
</br>

### 5.Shader-based Physical Modelling Synthesis ###

 [link to the artickle]*http://www.nime.org/proceedings/2017/nime2017_paper0028.pdf*</br>
 ![Image](pms.png)
   *This project is very similar to my conceptual design1. However, it is very structured and developed with modern technologies.*
</br> 
### 6.Device orchestra ###
</br> 
 [divice orchestra]*https://youtu.be/8jDROj236R4*</br>
 ![Image](do1.png)
 ![Image](do2.png)
  *This project achieved fun of interactive technologies and music. It is amusing to watch.*

</br>
## Conceptual progress ##
</br>
### Design intent ###
*Include your design intent here. It should be about a 10 word phrase/sentence.*
</br>
### Design concept 1 /Experiment with the relations of SOUNDS & MATERIAL ###
</br>
Experiment on how humans react when abnormally occurs in the relations between senses of touching , hearing and sight.
Embark the sense of wonder which we normally don't care.</br>

When you touch gravel> it sounds you knock the  wood.
When you touch the sand> it sounds you mix the gravels. etc.. </br>

 ![Image](p1.png)
</br>

### Design concept 2 /Musical Gym ball ###</br>

Gym ball plays music and rhythm which synthesize with your movement!</br>

 ![Image](p2.png)</br>
 
 ### Design concept 3/ Chasing car ###</br>
people wearing the microbit on his foot. The microbit car is chasing him, and the music changes in dramatic way depend on the distance between them.</br>

 ![Image](p3.png)</br>
</br></br>
### Final design concept/ Playng a sound Gym ball ###</br></br>

I wonder if everybody has a gym-ball that he bought for exercise and was left alone. As a "sometimes used chair" in one corner of the room...
This is a tool that transforms such a gym-ball into a ball for fun. This ball plays a music scale, according to the movement of the body.
In order not to limit the movement itself, the aim was to make the loading as simple as possible. Moreover, I would like to make full use of the aesthetic humor of the large gym ball itself—the material of the cover something special that stimulates the texture.</br>
</br>
### Interaction flowchart ###
The music is made by mainly using the setting of the accelerator sensor of Microbit. Acceleration x (horizontal movement) senses the scale, acceleration y (vertical movement) senses BPM, that is, the speed of sound.</br>

![Image](flow.png)</br> 
![Image](pitch.png)</br>
![Image](noteconcept2.png)</br>
![Image](noteconcept1.png)</br>


## Physical experimentation documentation ##

### Trial one ###
![Image](trial1.png)
[Trial1 movie]*https://youtu.be/eL1vTo0R4Rk*

I tried connecting four speakers, unfortunately ,the overall volume did not change—incorporation with an amplifier is essential.
I research how to attach the amplifier to the microbit. It seemed to do with some soldering work.  It was not realistic for me. So I decided to go with just one stereo speaker.</br>

And, lots of examination about coding here. I caliculated the amount range to set the "pitch".</br>
![Image](noteflow1.png)![Image](noteflow2.png)
![Image](if1.png)![Image](if2.png)</br>
I coded with "if true" first, but it didn't work well. I was struggling with how to set the range of the amount acceleration. Depend on the setting, microbit picked just one range ..(played just one key..)</br>

Finally, I have found the codes; "constrain between A and B" and "while do." These worked quite well. Then I played around with the length of the beat. 
Since It cannot stop the sound once it played, it will pick up the "new/next"data at the point where the sound was cut off. So beat length should be the key to the music.</br>
![Image](code1_2.png)![Image](code1_3".png)
</br>
### Trial 2 ###
![Image](trial2.png)![Image](trial2_2.png)![Image](trial2_3.png)![Image](terminalboard.png)
https://youtu.be/yqaLaYlwkn0
https://youtu.be/TvU-jmjDYY4

This stage was the learning about "the Kitronik Terminal Block Breakout" This is because that,  it must withstand to big and constant movement.All parts of the electrical circuit should be firmly connected.  Aligator clip might not work.. 
I confirm the speaker and battery connection with terminal block. Then I put this element in the roughly-made cardboard box. I came up with the idea of putting this container in a cloth bag. It worked!</br>
![Image](code_y.png)</br>
I tried to set up "acceralation y " as BPM.</br>


### Trial 3 ###
![Image](trial3_7.png)
![Image](trial3_1.png) 
![Image](notedesign1.png)
![Image](notedesign2.png)</br>
This stage is trial for the fabrication. I designed the container which could hold the parts( terminal board, battery, microbit, stereo speakers, and cables) firmly in the box. These were set up nicely in the box( bit busy though), And I  covered up the ball with my old Tshirt, squeezed the container between the Tshirt and the gym ball. ! it worked! However, the problem was that sound was just too small.. it was not fun at all!</br>
https://youtu.be/lQGHr2OlBq8
![Image](trial3_4.png) 
![Image](trial3_5.png) 
![Image](trial3_6.png) 
![Image](trial3_3.png) 
![Image](trial3_2.png) 

### Trial 4 ###

*Sewing
This stage is the brushing up the fablication and coding. 

I saw the cover with sewing machine.</br>
![Image](trial4_1.png) 
![Image](trial4_2.png) 
![Image](trial4_3.png) 
![Image](trial4_4.png) 
![Image](trial4_5.png) </br>

Then, in order to try the LED would work with or not, I tested with fairly light.
It worked well with the direct connection with aligator pin with microbit.</br>
![Image](fl1.png) 
![Image](fl2.png) 
![Image](fl3.png) </br>
However, it did not work with terminal block.. So, for this stage I needed to give up. </br>
![Image](fl4.png) 
![Image](fl5.png) </br>
but I made sure the light could fit into the ball. There is a possibility to put the NEOPIXEL in the ball.</br>
![Image](fl6.png) 
![Image](fl7.png) 
*Coding</br>
![Image](buttonA.png) 
Being struggle with making the switch on/off with code, I asked advice during the class time.  Unfortunately, it did not work. For the next stage, I should look at the solution. </br>

Then the following is the final code for this prototype. </br>
![Image](final1.png) 
![Image](final2.png) 

## Design process discussion ##
*Discuss your process in getting to this point, particularly with reference to aspects of the Double Diamond design methodology or other relevant design process.*

## Next steps ##

*Write a list or provide other information about your plan to move the project forward to be ready to present by video and documentation in week 12 of the course.*
-Explore and Reserch about the how to make "bouncy ball"
-Explore and Reserch about "Neopixel"
-Establish the switch"
-Make Microbit container smaller , thinner and lighter. My goal is the container could tack in the pocket of the cover.
