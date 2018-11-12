
This is my open source arduino projector. I was so excited to discover it that I haven't even tested it yet!
I bought a spotlight to make a black light out of.I realized that the tiny led and the convex lens would make a projector.
This is just a rough test design. I didn't get it done for halloween because I figured it out less than 2 days before.
Where do ideas come from anyways?
Enjoy.

I used the very popular nokia 5510 lcd.You have to use one that can have a big rectangle cut in the pcb so the light shines through it.
Then you put it in front of the lens and let the led shine through. You can figure the wiring out from the code but remember to use a
 voltage converter like a diode and resistor for the data lines because they are 3v.
 
 It's very rough but it gets me in the "idea space". 
 
 The sketch just flips through the images right now. I will add an sd card and other features later.
 
 the rotate.html file has javascript I used to convert a binary image to the nokia format. It's rough but it works.
 
 Here is the spotlight I have.
 
![Alt text](spotlight.png)
 
 Here is the lcd module. It's very popular. you can cut a rectangle the size of the lcd in this one.
 
![Alt text](nokia5510.jpg)

I'm using my favorite construction technique. modules pushed through perfboard with wire wrap. See my other projects for an example.
 
This is just an Arduino displaying a series of images. The only thing different is the lcd. Here is how I constructed the lens. It isn't easy. Be prepared to spend time working with tiny delicate parts.

You have to take display apart and strip it down to the bare glass. It has a reflective sticker on the back that you have to peel off to make it more transparent. The glass is polarized too. This eevblog video was very helpful.

https://www.youtube.com/watch?v=mo4_5vG8bbU

Thanks again Dave!

![Alt text](housing.png.jpg)

The problem with doing this is the rubber coductors that attach to the glass. I had one module from china that had conductive traces on the glass and the rubber conductor would not make good connection after I modified it. I tried many things to replace the rubber conductor but nothing has worked yet. I tried conductive wire glue. I took the pins out of female headers but couldn't get that to work. The pins are 1mm pitch and I thought an sd card connector woud work but it won't. Finally I settled for the construction you see. I glued two nuts to the display to hold the piece of pcb on. I'm going to look to see if I can find those rubber conductor new somewhere. I had more LCDs from sparkfun and the conductor seemed to be stuck to the glass good and I never took it off.

I built the projector and found that I didn't need the convex lens. Just a flat piece of plexiglass worked. You do need the small LED though,I think. The convex lens makes a good magnifier anyway. A different housing might be better. the further you move the display from the light the smaller the image gets. Right now the image is a little light but I'm working on that. A higher resolution would be nicer too.



 improvements to come...
