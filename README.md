# R I P-berry Pi Anti-tutorial

This is a cautionary tale against what I did!! **DO NOT DO WHAT I DID AND BREAK A RASPBERRY PI!!!** 

## The beginning 

Interested in hardware projects, I got a Raspberry Pi! 10/10 setup instructions plus I had done it before, but here's how my station was setup.
![the setup](setup.jpg).

Raspberry Pi is super cool!! It contains a 64-BIT QUAD CORE PROCESSOR for a p tiny package, and you can hookup a keyboard, mouse, monitor, headphones, ethernet cable, etc. I straightup will get my future kid one of these if they ever ask for a computer, because this is really all you need. 

I wish I had more pictures with it, but as I was setting up, I assumed I'd have more time with my Pi. Really teaches you to cherish time with loved ones because they can be gone any time. The Pi comes with a super simple OS aptly named NOOB, and its sole purpose is to connect you to internet to install another OS, kind of like the real life use case of Internet Explorer.

## The uneventful but delightful middle 

Again, no pictures because I thought I'd be able to DEMO this, but I installed Raspian and it was GR8. I installed multiple c0diNg apps as well as Minecraft. Here's the beautiful inside of the Pi (no longer functional).
![my pi](pi.jpg)

## The start of the end

Wanting to do more with the kit pictured below, I started following [this tutorial](https://learn.sparkfun.com/tutorials/raspberry-gpio).
![the open kit](kit.jpg)

The tutorial gives a very good overview of how to program for the Pi's hardware components! I followed it closely with my minimal electrical engineerly experience, yielding a bread board like this one below after some trial and error.
![pic from website](stolen.jpg)
With the `blink.py` script also from the tutorial, I programmed the red light to blink when the red button was pressed!! So fun. 

Armed with my new brilliance and invincibility, I set out to make a MORE advanced circuit. The end result looks something like this.
![cool bread board that COULD'VE been everything](breadboard.jpg)

BUT my grand vision was never realized! In fact, the Raspberry Pi is no longer alive!! WHY HAS SUCH A TRAGEDY BEFALLEN UPON US, u may ask?? 

## A superficial overview of what happened

As I was wiring, my screen went black. I was so concentrated on making magic happen I didn't even realize. When I did, I thought something was wrong with my display, so I tried to SSH into my Pi, then getting stuck because I didn't know its IP address. 

After putting on my #debuggingHat, I tried disconnecting the bread board, and the Pi turned on again!! I *should have* realized at this time that the circuit was the source of my problems. BUT, what I thought instead was "wow! It's back so I should try connecting everything again!" So I PUT BACK the bread board, shorting the Pi again, this time permanently killing my poor sweet Raspberry Pi.


## A technical explanation of what happened

Here is a picture of exactly where things went wrong:
![ding ding ding](danger.jpg)
Look at where the white wire is. To its right, on the Pi Wedge, is a 3.3V label, and its left end is (now correctly) connected to the positive row of the bread board. Out of IGNORANCE, I connected it to the negative row of the breadboard, effectively zapping the 3.3V back into the Raspberry Pi, KILLING it.


## Takeaways

I want to continue working with Raspberry Pis as this was SUPER fun, but the next time I do this, I WON'T KEEP THE BREAD BOARD CONNECTED!! And I'll try to actually understand what I'm wiring instead of going by intuition. 

I'M SORRY FOR HURTING A POOR, INNOCENT RASPBERRY PI IN THIS PROCESS.