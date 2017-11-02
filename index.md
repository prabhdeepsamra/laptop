## The "janktop"

I hacked together a "laptop" by combining an old desktop computer and the monitor from a broken laptop. It's more of a portable desktop, but the idea is there. Is it practial? Not really, no. Was it fun? Yes. 

This was supposed to be a prototype project, hence why I used an old pre-built system. It was the cheapest way of testing my idea.


## The Computer

Here it is in its full glory
![Image](https://user-images.githubusercontent.com/9144361/32306205-3c900d82-bf37-11e7-9dd4-72bbca573ac3.jpg)


### The parts
LCD Screen - I ripped this from an old, broken laptop - $0

[LCD Controller Board](https://www.ebay.com/itm/Kit-for-LP156WH2-TLQB-LCD-LED-Lvds-Controller-Board-HDMI-DVI-VGA/112415296844?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2060353.m2749.l2649)  - This part let me input to the LCD Screen - $20

Dell OptiPlex 760 - Core2 Duo E8400 (3Gz), 2GB DDR2 RAM, onboard graphics, etc. - $30

Wood - $10

Total ~$60


### The building process
After concieving this nutty idea, I stripped an old laptop of its screen and bought a control board for it. It didn't come with any wiring, so I had to splice together a power adapter and a transformer to get the voltage and the fitting correct. I connected it to my desktop to make sure it worked, which it did. 

Now I had to decide what parts to buy for the laptop. Initially, I was going to build a custom rig, but that proved to be too expensive for something I wasnt completely sure was going to work (both in function and form). I found a cheap old desktop online that I think belonged to a public school or a large firm. The point is that it was old and inexpensive.

The first thing I did when I recieved the desktop in the mail was weight it. It was too heavy, and I decided to build the case out of wood on account of how heavy the metal case was. I opened it up and took it apart to see how much space could be saved. I made the foolish mistake of doing this before even making sure it even worked. I came to my senses and hooked up the cabling to the computer and LCD to make sure everything worked. 

I layed out all of the main components on a piece of wood then cut that to size. The next step is the beginning of the jankiness. The cables that go from the power supply to the motherboard were too short, so I tore apart the side of the PSU with some pliers to get a few extra centimeters. Don't worry, I peeled off the "Void if Seal Broken" sticker so I can return the computer and get my money back.

The wires were still too short so I ended up having to extend them. This is most of the reason why I consider this project jank. 22 wires cut in half and extended = 44 soldering joints. This took a couple hours because of the tight spacing and lack of experience. The $8 Hardware Fright (it's a pun, not a misnonmer) soldering arm came in handy.This took a long time because I had to map each cut back to its original wire. I didn't have the sense to look at the pinout for the cabling, and I didn't want to risk simply matching colors. 

The next issue to resolve was powering the LCD. I needed to pull 12v from somewhere on the board. First I looked at the mini sata power pinout for the cd/dvd drive, but that only relayed 3v. I looked at the pinout for the sata power cable that was powering the 12v, 120 gb stock hard drive. The cable had separate 3, 5, and 12v lines. I cut the 12v line and a ground line to use for the LCD power, and spliced that to a power cable wire. I decided to use the hard drive from my current laptop, since it only required 5v (also because I wouldnt need to configure any software because Linux doesn't really care about any hardware changes).


After the cable extension, everything fit properly on the base. A quick note on the quality of woodwork: The tools I had were a coping saw, circular saw, drill, and jigsaw. I'm bad at it. I held everything down with wood, glue, and screws. To make the structure of the case, I made four "L" shaped beams and glued them to the corners of the base.I glued/screwed the LCD to a piece of wood the same size as the base, and prayed the hinge location and fitting would work. It didn't. To complete the frame, I connected the four L-shaped columns with straight pieces of wood. After these support pieces were in places, I readjusted the LCD attachment (several times) and shadily screwed it onto the main assembly. 

The last steps were to put side panels on the assembly. The front was the easiest because it is just a flat piece of wood. The back panel needed a hole for the power cable, and needed to be shortened several times to allow clearance for the screen to open up. The left side of the case was difficult because it needed a hole for the fan, and the right side was difficult because it was the last bit of construction I had to do and I was lazy. I just glued a couple scrap pieces of wood to it. It looks fine.

The final thing I did was take a handle from a cabinet and screw it onto the face, since it was a bit hard to carry. Unfortunately the laptop came out looking like a drawer. It did, work however. There's a conclusion at the end. 





#pictures

Testing the system. Mind the mess. I'm young, that's an excuse, right?

![Image](https://user-images.githubusercontent.com/9144361/32307217-97cb004e-bf3c-11e7-9139-d9c99315a78e.jpg)

Jank power supply modification
![Image](https://user-images.githubusercontent.com/9144361/32307098-088a21c6-bf3c-11e7-911e-481c778be29b.jpg)


The soldering setup.  Sorry about the blur and the orientation. Click on the images for the correct orientation. Still new to this. 
![Image](https://user-images.githubusercontent.com/9144361/32307347-500d56f2-bf3d-11e7-8851-a53f784cca1c.jpg)

Soldering in progress
![Image](https://user-images.githubusercontent.com/9144361/32307344-4db6f57a-bf3d-11e7-9735-5ab9401a09e2.jpg)


Sizing the height and installing the "L" columns.
![Image](https://user-images.githubusercontent.com/9144361/32307350-51358130-bf3d-11e7-9190-f3d965b38093.jpg)


