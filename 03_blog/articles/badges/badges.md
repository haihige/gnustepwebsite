# GNUStep now has badges

by Riccardo Mottola

Finally I got around implementing and committing badge support in GNUStep! I think it is one of the fine additions Apple did to the original OpenStep spec.

While Apple had it since MacOS 10.5, GNUstep didn't and GNUMail had to manage 3 different code paths: One for GNUstep, one for 10.4 Mac and one for 10.5 and later which I implemented myself, since GNUMail originally didn't have it. First, I with Fred and Richard brought up GNUmail code to match the 10.4 code path, which is generic and just draws the Icon. To do this, I had to change the code, since ImageReps are not writable in GNUstep, so NSCustomImageRep had to be used and it woks both on GNUstep and on Mac.
  
Later, proper badges support has been added in GNUstep, here the look with [GNUMail](https://www.nongnu.org/gnustep-nonfsf/gnumail/) and with a small test application, which is ported directly from Mac and compiled using xcode [buildtool](https://github.com/gnustep/libs-xcode).  

![](image1.png) 

As we were tried to match certain Apple behaviours, like ellipsis, but also an addition: I made the colors themable.  

Here a nice screenshot of the two things working with the Sonne theme. Thematic was enhanced to handle the badgeColor with its three shades matching the ring, text and badge background.  

![](image2.png)
