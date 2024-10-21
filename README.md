# PipBoy watchface for WearOS
PIP-Boy watchface app for WearOS.

## Table of content

- [Installation](#installation)
- [Functionality](#behaviour)
- [Change it yourself](#try-changing-watchface-yourself)
- [CHECK OUT different version of this watchface!](#different-version)

## About the watchface

> This thing is made just for fun after getting WearOS device on hand. About 2-3 hours spent in total. Initially shared in couple of places and changed due to requests at November 2022. Following seldom requests from different directions made sharing enhanced or fixed versions harder. So i just created this repo. There is WatchFaceStudio link. It is free and easy to use (which leads to limited functionality). Change it yourself. If you want me to change it, write me any place you can and i will add it. Eventually... It may take some time to notice and get to it. I am not even using this watch face myself, so it is quite a low priority.

![GIF](misc/pipboy_wf.gif) 

Always on display is different.

![AOD](misc/aod.png)

Simple watch face for an Wear OS devices. Only for circular devices. Created using Samsung's [WatchFaceStudio](https://developer.samsung.com/watch-face-studio/download.html) (WFS), so it is not really sophisticated, and quite a number of things can only be added using some trick, if ever.

> The file with *.wfs* extension is savefile with the project. Said savefile is, in fact, just an easily extractable archive. It contains all assets. None of those are made by me, as well as I don't own any IP. Using it commercially or otherwise may require permissions. But project's savefile itself? You are free to change and use it anyhow.


Maybe one day i will try making it from scratch on Flutter. Just to see how well Flutter works on WearOS devices.

## Behaviour

Everything is on the screen. Except...

1. Changing parts are:
* Three PipBoy animations (the ones i was able to find and seemed fitting - walking, wakingup/goingtosleep, resting);
* Extra animation for heartbeat > 140 - adrenaline/exhaustion.
* Low charge indicator for % < 35. Just text, though.
* Charging indicator.
2. Invisible shortcuts (complications) at certain places.
3. Some more colours (check in watchface settings).

![Colours](misc/colours.png)

## Installation

> On the right side of the page you can find [Releases](https://github.com/universewithtin/pipboy_watchface/releases) section. There you can see last version or pick older ones.

You can follow this guide to install watchface on the watch. Things may be just a little bit different for newer updates of your watch. But this video should work just fine.
[![Guide](https://img.youtube.com/vi/Oab9GabAuxc/0.jpg)](https://www.youtube.com/watch?v=Oab9GabAuxc)

> [!IMPORTANT]
> While installing APKs is getting safer and safer, downloading and installing watchface this way may be not your preferred action. 

In that case, download WFS and you can compile your own APK file. That would not require anything but pressing couple of buttons.


## Try changing watchface yourself

- Download [WatchFaceStudio](https://developer.samsung.com/watch-face-studio/download.html) (about 400mb)
- Download file with *.wfs* extension here.
- Watch the video below. Or just poke whatever you like. It's not like you can ruin anything badly.
- Compile APK there or sideload directly to your watch. Guide for that is in [Installation](#installation) section.
[![WFS](https://img.youtube.com/vi/2t02rF1Tybg/0.jpg)](https://www.youtube.com/watch?v=2t02rF1Tybg)

> [!TIP]
> - Basically, opacity. Check the opacity modificator for elements. Want something gone or appear at certain time or trigger? As all of it comes by boolean(0-1) or changing some number. 
> - Multiply/divide/substract/add that number to the opacity and you will get that effect. One thing disappears and other appears on that place.
> Yes, WFS is limited just like that. But it provides creation of energy efficient and any system compitable application.
> - If you are adding pictures, try to resize them into smaller resolution. No use of fullHD pictures on screen this small.
 


## Different version

> [!TIP]
> Someone reached out with own version of this watchface. Honestly, it is better than mine in terms of detalization. 


- [Link to Reddit](https://www.reddit.com/r/Fallout/comments/1fwgs95/custom_pipboy_face_for_my_galaxy_smart_watch/)
- [Link to the release comment](https://www.reddit.com/r/Fallout/comments/1fwgs95/comment/lqeinn0/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button) (In case links will change)
- If no APK provided there by the time you check the link, you can still install WFS and create one yourself or sideload it.

![info_pic](/misc/other_version.png)
