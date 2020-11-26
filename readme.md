# The "janktop"

I hacked together a "laptop" by combining an old desktop computer and the monitor from a broken laptop. It's more of a portable desktop, but the idea is there. Is it practical? Not really, no. Was it fun? Yes. 

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
After conceiving this nutty idea, I stripped an old laptop of its screen and bought a control board for it. It didn't come with any wiring, so I had to splice together a power adapter and a transformer to get the voltage and the fitting correct. I connected it to my desktop to make sure it worked, which it did. 

Now I had to decide what parts to buy for the laptop. Initially, I was going to build a custom rig, but that proved to be too expensive for something I wasn't completely sure was going to work (both in function and form). I found a cheap old desktop online that I think belonged to a public school or a large firm. The point is that it was old and inexpensive.

The first thing I did when I received the desktop in the mail was weight it. It was too heavy, and I decided to build the case out of wood on account of how heavy the metal case was. I opened it up and took it apart to see how much space could be saved. I made the foolish mistake of doing this before even making sure it even worked. I came to my senses and hooked up the cabling to the computer and LCD to make sure everything worked. 

I laid out all of the main components on a piece of wood then cut that to size. The next step is the beginning of the jankiness. The cables that go from the power supply to the motherboard were too short, so I tore apart the side of the PSU with some pliers to get a few extra centimeters. Don't worry, I peeled off the "Void if Seal Broken" sticker so I can return the computer and get my money back.

The wires were still too short so I ended up having to extend them. This is most of the reason why I consider this project jank. 22 wires cut in half and extended = 44 soldering joints. This took a couple hours because of the tight spacing and lack of experience. The $8 Hardware Fright (it's a pun, not a misnomer) soldering arm came in handy. This took a long time because I had to map each cut back to its original wire. I didn't have the sense to look at the pinout for the cabling, and I didn't want to risk simply matching colors. 

The next issue to resolve was powering the LCD. I needed to pull 12v from somewhere on the board. First I looked at the mini sata power pinout for the cd/dvd drive, but that only relayed 3v. I looked at the pinout for the sata power cable that was powering the 12v, 120 gb stock hard drive. The cable had separate 3, 5, and 12v lines. I cut the 12v line and a ground line to use for the LCD power, and spliced that to a power cable wire. I decided to use the hard drive from my current laptop, since it only required 5v (also because I wouldn't need to configure any software because Linux doesn't really care about any hardware changes).


After the cable extension, everything fit properly on the base. A quick note on the quality of woodwork: The tools I had were a coping saw, circular saw, drill, and jigsaw. I'm bad at it. I held everything down with wood, glue, and screws. To make the structure of the case, I made four "L" shaped beams and glued them to the corners of the base.I glued/screwed the LCD to a piece of wood the same size as the base, and prayed the hinge location and fitting would work. It didn't. To complete the frame, I connected the four L-shaped columns with straight pieces of wood. After these support pieces were in places, I readjusted the LCD attachment (several times) and shadily screwed it onto the main assembly. 

The last steps were to put side panels on the assembly. The front was the easiest because it is just a flat piece of wood. The back panel needed a hole for the power cable, and needed to be shortened several times to allow clearance for the screen to open up. The left side of the case was difficult because it needed a hole for the fan, and the right side was difficult because it was the last bit of construction I had to do and I was lazy. I just glued a couple scrap pieces of wood to it. It looks fine.

The final thing I did was take a handle from a cabinet and screw it onto the face, since it was a bit hard to carry. Unfortunately the laptop came out looking like a drawer. It did work, however. There's a conclusion at the end. 





## pictures

Testing the system. Mind the mess. I'm young, that's an excuse, right?

![Image](https://user-images.githubusercontent.com/9144361/100384705-a0f6cb00-2fd5-11eb-8db1-9df8bacf8f2a.jpg)

Jank power supply modification
![Image](https://user-images.githubusercontent.com/9144361/32307098-088a21c6-bf3c-11e7-911e-481c778be29b.jpg)


The soldering setup.  Sorry about the blur and the orientation. Click on the images for the correct orientation. Still new to this. 
![Image](https://user-images.githubusercontent.com/9144361/32307347-500d56f2-bf3d-11e7-8851-a53f784cca1c.jpg)

Soldering in progress
![Image](https://user-images.githubusercontent.com/9144361/32307344-4db6f57a-bf3d-11e7-9735-5ab9401a09e2.jpg)


Sizing the height and installing the "L" columns.
![Image](https://user-images.githubusercontent.com/9144361/32307350-51358130-bf3d-11e7-9190-f3d965b38093.jpg)


Top-Down view of the final product. Note the excess of wires and lack of structure for modular components.
![Image](https://user-images.githubusercontent.com/9144361/32306204-3c639572-bf37-11e7-8333-ffd370b2370e.jpg)


The final product seen as would be in use. I tended to use it with the keyboard and mouse out of the tray. Yes, I shouldve made a 
|__ ___ | - shaped table that was flippable, but I was done with the project.
![Image](https://user-images.githubusercontent.com/9144361/32306205-3c900d82-bf37-11e7-9dd4-72bbca573ac3.jpg)


Top-Down view of the final product. Closed. 
![Image](https://user-images.githubusercontent.com/9144361/32306206-3cbab942-bf37-11e7-96ff-6218e6d1bd3c.jpg)

Side-view of the fan
![Image](https://user-images.githubusercontent.com/9144361/32306207-3ce88a20-bf37-11e7-9569-c69c5770a334.jpg)

View of the rear.
![Image](https://user-images.githubusercontent.com/9144361/32306208-3d190a38-bf37-11e7-963d-fad98b84c5e8.jpg)

Standing up. Looks like of like a briefcase. 
![Image](https://user-images.githubusercontent.com/9144361/32306209-3d441a3e-bf37-11e7-8060-365133df4293.jpg)


## Conclusion 

I am happy with the results, and I learned a lot from this project. The laptop came out a bit clunky and quite large, but that couldn't really be helped with the tools and materials at hand. If I were to continue with this idea, building off this prototype and putting a decent amount of money into it, there is a lot I would change. The first issue is the size. The total height is about 5.75 inches, 2 of which came from the keyboard I decided to use. To make it smaller, I would first have an external power supply. This would mean buying a separate transformer and having some kind of power circuit inside the case. The keyboard could be replaced by several laptop keyboards I have from broken laptops, but I don't know how easy it would be to essentially create a drive for it. This would also get rid of the need for an external mouse, but I like having the real thing over a trackpoint or trackpad. The last thing I could do is use a different cooling system for the CPU. The current stock heatsink is large and clunky. I know of some low profile air coolers, but I was looking into the idea of a closed loop CPU-specific water cooler. 

A final note on this project. If made with decent components, it may be worth it in terms of price/performance, but the power draw cannot compete with that of modern laptops. It is simply too inefficient. Although it wasn't too difficult to use, it is simply no replacement for a laptop. It is, at best, a portable desktop. 









