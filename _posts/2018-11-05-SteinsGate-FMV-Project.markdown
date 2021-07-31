---
title: Steins;Gate Steam - HQ FMV Project
date: 2018-11-05 04:20:00 +0300
description: Replacing low quality videos with higher quality ones.
image:
  src: /assets/img/SGHQFMV/SGcover.png
  width: 1280
  height: 720
tags: [Games, Video]
---


When the Steam version of Steins;Gate was produced, the developers decided to use a very well known and often reliable video codec - Bink.

Bink can be an amazing *compressor*, but whoever is encoding videos has to be very careful, otherwise Bink will destroy the video in order to achieve a small file size.

Suffice to say, Steins;Gate's bink videos are really, really, horribly compressed.

As someone who played the Steam version before any other port, I was shocked when I booted a copy of Steins;Gate on ps3 and watched it's versions of the videos.

Here are some comparisons:

(compare the images at full resolution to see the finer details)

| Steam | PS3 (upscaled) |
|--|--|
| ![Steam](/assets/img/SGHQFMV/comp1_steam.jpg) | ![PS3](/assets/img/SGHQFMV/comp1_ps3.jpg) |


| Steam: | PS3 (upscaled): |
|--|--|
| ![Steam](/assets/img/SGHQFMV/comp2_steam.jpg) | ![PS3](/assets/img/SGHQFMV/comp2_ps3.jpg) |

### The problem

Bink. 
  
Only Bink 1 is free to use. One can only encode Bink 2 videos if they buy a commercial license, so Bink 1 is my only option.  
  
As expected, Bink 1 is terrible, outdated and bloated. Bink 2 is the "new" and improved version of the encoder.  
  
Steins;Gate's videos were encoded using Bink 2, but without proper settings, the results were terrible. The videos look overly compressed and blocky.

### The solution (?)

My project aims to "port" and improve the videos by using VapourSynth as a way to filter them, and Bink 1 as the file format.  
  
However, to get Bink 1 videos to "look good", the encoding basically has to be extremely "bloated". The file size can be seen as "huge" to some people.  
  
With all of these limitations in mind, this project's clearly not perfect.  
  
However, I tried my best to retain as much quality as possible while keeping the videos at a "reasonable" file size.  
  
Also, I tried to correct the only problem with the ps3 videos: Aliasing present on sprites when a "transition" video is playing.  
Comparison:  
 
| PS3 (upscaled): | My project: | Steam: |  
|--|--|--|
| ![PS3](/assets/img/SGHQFMV/comp3_ps3.jpg) | ![My project](/assets/img/SGHQFMV/comp3_project.jpg) | ![Steam](/assets/img/SGHQFMV/comp3_steam.jpg) |

Sound wise, Bink 1 is also pretty terrible. However, there is workaround for that.

### Finally,
 
This project was designed to work with [Committee of Zero's improvement patch](https://steamcommunity.com/app/412830/discussions/0/215439774868934160/). Mainly the HQ audio portion. I have [forked its source code](https://github.com/nipkownix/sghd-patch) and used its "file redirection" feature to replace the Bink 1 audio with the ps3 sound files extracted from the same videos I used as a source for this project.  
  
If you don't use the aforementioned improvement patch, the videos will display no subtitles and you will hear noticeable lossy audio. Do as you please, but I do recommend using the improvement patch.


### What about the Japanese videos?

Committee of Zero's improvement patch has optional instructions guiding you to replace the hard-subbed English videos for the Japanese videos. The Japanese videos do look better than the English ones, but they are plagued by the same problems. In fact, the images I used for comparison earlier are from the Japanese videos. Their English counterparts look even worse.  
  
You can skip downloading the Japanese videos if you are going to use the ones from this project. Please remember that the videos from this project have no hardsubs and are a mix from both English and Japanese ps3 videos. Subtitles have to be [enabled](/assets/img/SGHQFMV/Subs.png) on the improvement patch.

### Downloads

The downloads are split into three optional parts:  
  

- [1080p videos](https://drive.google.com/file/d/1x5May_-WCfM7w0eV_7jmTcV8YrEDaiR_/view?usp=sharing) (2.9G)

- [720p videos](https://drive.google.com/file/d/1JkXdc6YArIXLNEVjfPmwT2Hh5FAYBVPF/view?usp=sharing) (1.5G)
    
- [HQ Audio](https://drive.google.com/file/d/1hwF2bfh9_c5qwWa0YHvZsP02iX0HQTVr/view?usp=sharing)
 
You probably won't need both video packs. 
1080p videos are used when the [movie quality is set to high](/assets/img/SGHQFMV/Launcher.png), and 720p videos are used when the quality is set to low.  
  
Copy the new files to:

> Steam\steamapps\common\STEINS;GATE\USRDIR\movie\

  
The HQ Audio pack should be installed "on top" of the [improvement patch](https://steamcommunity.com/app/412830/discussions/0/215439774868934160/), replacing existing files.


I have a Steam thread regarding the HQ FMV project [here](https://steamcommunity.com/app/412830/discussions/0/2798319091587347187/) if any assistance is needed.