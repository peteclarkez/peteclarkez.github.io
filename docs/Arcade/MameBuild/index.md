# Mame Bartop Build

After initially building a control panel to test everything out, i wanted to build a bar top cab so i could play mame games.

[![][victory05]][victory05]
  
## Donor Laptop

A Dell Vostro 1710 laptop provided the internals for the build and the cab was built around that. It provided the core dimensions.
It's a Core 2 Duo with 4 GB of RAM and an Intel Integrated Video Card.

Image below shows some early experiments in order to make sure I could power the laptop on and off from an external button. I had always planned to detach the screen and body, but once I got it open, there wasn't much length to the cable joining the 2 halfs, although the screen itself had some very useful mounting holes which take a 3.5mm bolt. This was how i mounted it to the front panel.

|               |       |
|:-------------:|:-----:|
| [![][laptop01]][laptop01] | [![][laptop02]][laptop02] 
| [![][laptop03]][laptop03] | [![][laptop04]][laptop04] 

In the end it was relatively simple and the board had some nice large contacts I could use to attach the wires for a normal arcade button.

## Cabinet

Once I had a width I looked at the cabinet. I went with a width of 500mm and I built a test Control panel to make sure it was enough for 2 players. (Now painted bright yellow and refitted with some cheap buttons and a an internal raspberry pi)

I got the layout from here << INSERT LINK >>

I used Google sketchup to plan the build and started into it back in 2013.
It was easy to build the unit but once I got to that stage I got stuck on how to mount a monitor to a front panel. (and left this for about 4 years continuely moving this around the garage)

|               |       |
|:-------------:|:-----:|
| [![][sketchup01]][sketchup01] | [![][sketchup02]][sketchup02]
| [![][cabinet01]][cabinet01] | [![][cabinet02]][cabinet02] |
| [![][cabinet03]][cabinet03] | |

Eventually I got a head of steam up to tackle this and spend some time on the software getting the laptop up and running.

I also went for the front panel, using 9mm MDF and routing out the opening using paper templates.

I also worked out a way to mount the laptop within the cabinet keeping it close to the screen. I used 2 cross bars and the insert removed on the 9mm panel to creat an angled shelf to hold the laptop so the cable would reach. I attached velco patches to the laptop and shelf and this is all tha'ts need to keep it in place.

With the plan all done, i got to priming and paint the cabinet.
I went for a gray base primer all over to keep dust down and then applied black glass spray paint up in a number of layers with sanding in between.

I had toyed with tmolding, but my router has an 8mm socket (got it second hand and think it came from aldi) so not easy to find a suitable slot cutter. In hindsight I wish I'd at least routed a bevel on the side panels.

|               |       |
|:-------------:|:-----:|
| [![][cabinet04]][cabinet04] | 
| [![][cabinet05]][cabinet05] | [![][cabinet06]][cabinet06]
| [![][cabinet07]][cabinet07] | [![][cabinet08]][cabinet08]
| [![][cabinet09]][cabinet09] |  | 

At this stage it was easy to start assembling the cabinet.

I sued a 4 gang inside the cabinet to distribute power and also used velco to keep all the components on the floor of the cabinet.

|               |       |
|:-------------:|:-----:|
| [![][cabinet10]][cabinet10] | |
| [![][cabinet11]][cabinet11] | [![][cabinet12]][cabinet12]
| [![][cabinet13]][cabinet13] | [![][cabinet14]][cabinet14]

## Control Panel

|               |       |
|:-------------:|:-----:|
| [![][internal01]][internal01] | | 

## Audio

The Audio parts were all recycled.
I used an old IPod dock as the amp (It takes audio in as well as the old style) and then wired these into some speakers i took from an old hello Kitty cd radio. Worked great and the old thing i had to buy were grills for the outside of the cabinet. THese cover the outlets I drilled in with a hole saw. The speakers are mounted on the inside just using some nail in cable clips.

|               |       |
|:-------------:|:-----:|
| [![][internal02]][internal02] | [![][speakers]][speakers] | |


## Marquee
For the marquee (and Side art) I tried to find something that suited the size of the cabinet. I originally planned space invaders (as per the sketchup) but I found the battlezone side art and marquee stickers pretty cheap on ebay so went wit thtat. I really liked how it turned out. For teh lights I'm using a usb led strip that I cut down to size, and it links nicely with the laptop being powered on.

|               |       |
|:-------------:|:-----:|
| [![][marque01]][marque01] | [![][marque02]][marque02] 

And here is the completed product.

## Finished
|               |       |
|:-------------:|:-----:|
| [![][victory03]][victory03] | [![][victory04]][victory04]

## Software

For software I'm using HyperSpin and RocketLaucher.
I've got Mame and a number of consoles setup with a large number of games (thousands). In reality it's too many so i plan to revist this and bring it back to a managable amount.

It will play mame and 16 bit consoles ok. Struggles to play PSX games, so i don't use it for that. Even in Mame it's stuggling to play things like NeoGeo games for fbaburn works fine.

Another issue I have is that it's very slow for a game to launch. Fine for me, but can be hard to explain to some of the younger family members.

## Future

I'd like to put a better PC inside, so might look at a cheap panel interface and update this at some point.


[laptop01]: images/20130720_01.jpg "Laptop broken up"
[cabinet01]: images/20130826_IMAG0433.jpg "cabinet 1"
[cabinet02]: images/20130826_IMAG0434.jpg "cabinet 2"
[cabinet03]: images/20130826_IMAG0437.jpg "cabinet 3"
[laptop02]: images/20170509_204502.jpg "laptop start button"
[laptop03]: images/20170509_210846.jpg "laptop start button2"
[laptop04]: images/20170509_210926.jpg "laptop start button3"
[cabinet04]: images/20170514_200741.jpg "cabinet screen 1"
[cabinet05]: images/20170514_200804.jpg "cabinet screen 2"
[speakers]: images/20170529_173245.jpg "speaker donation"
[cabinet06]: images/20170530_200323.jpg "cabinet cp drill"
[cabinet07]: images/20170604_151145.jpg "cabinet primer"
[cabinet08]: images/20170611_205841.jpg "cabinet primer2"
[cabinet09]: images/20170613_195111.jpg "cabinet black"
[cabinet10]: images/20170613_211521.jpg "cabinet screen mount"
[cabinet11]: images/20170613_212316.jpg "cabinet screen working"
[marque01]: images/20170618_151431.jpg "cabinet marquee "
[internal01]: images/20170706_175115.jpg "cabinet cp internal"
[internal02]: images/20170707_210844.jpg "cabinet internal"
[marque02]: images/20170712_233923.jpg "cabinet marquee lit"
[cabinet12]: images/20170722_185817.jpg "cabinet internal power"
[cabinet13]: images/20170722_185827.jpg "cabinet internal power2"
[cabinet14]: images/20170722_190232.jpg "cabinet back"
[vistory01]: images/20170722-WA0005.jpg "victory1"
[vistory02]: images/20170722-WA0007.jpg "victory2"
[victory03]: images/20170723_233854.jpg "finished 1"
[victory04]: images/20170723_233858.jpg "finished 2"
[sketchup01]: images/20171028_ArcadeSketchUp.png "ArcadeSketchUp"
[sketchup02]: images/20171028_ArcadeSketchUp2.png "ArcadeSketchUp2"
[victory05]: images/20180723_211354.jpg "finished 3"