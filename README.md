rainbowdanceparty
=================

This is The Rainbow Dance Party.

The idea is to have short-throw projectors mounted on the floor or ceiling, right next to the wall (if on the floor then protected from dancers by a barrier of some kind), projecting a live, real-time feed of the dancers themselves, but the images of the dancers, which are captured with cameras mounted behind the screens being projected on, through little holes in the screens, are actually projected as cutouts of the dancers filled with rainbow-colored particles.

The further away from the screen the dancers are, the more they fade into black.  This is done by using an Asus Xtion PRO LIVE, or similar, to determine how far away the dancers actually are.

There is also a sound sensor that identifies bass beats by listening for a certain frequency threshold.  When the frequency suddenly drops below the threshold, the color of the dancers changes suddenly to red, and then particle fades back into the rainbow-colored particles dancing within the dancers.


New idea
========
Like the Rainbow Dance Party, but in reverse, I'd like to make a projection that makes the dancers appear to have radiant rays emanating from behind each of them, as if they were each eclipsing a star.  It would look something like the picture on this page: http://www.sonos-studio.com/RSVP/LA, but rather than a circle it would be the shape of the dancer, and it would move in real time.

Problems
========
The main problem I am running into trying to implement this is that performing these transformations on the fly using computer vision requires so much processing power (at least the way I'm currently coding them) that it's impossible to make it look like it's happening in real time.  The FPS just isn't there.  I talked to a guy recently who was doing a light show for Rashad Becker at the Luminary for New Music Circle.  I can't remember the guy's name right now, but I have it written down somewhere... Anyway he was doing these amazing things with real-time responsiveness, so I asked him some questions after the show and he told me that it was all done using analog equipment.  He said that I should get an old video mixer from eBay and learn how to use it.  
