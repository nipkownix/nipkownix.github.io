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

## The problem

Bink. 
  
Only Bink 1 is free to use. One can only encode Bink 2 videos if they buy a commercial license, so Bink 1 is my only option.  
  
As expected, Bink 1 is terrible, outdated and bloated. Bink 2 is the "new" and improved version of the encoder.  
  
Steins;Gate's videos were encoded using Bink 2, but without proper settings, the results were terrible. The videos look overly compressed and blocky.

## The solution (?)

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

## Finally,
 
This project was designed to work with [Committee of Zero's improvement patch](https://steamcommunity.com/app/412830/discussions/0/215439774868934160/). I have used its "file redirection" feature to replace the videos.  
  
Committee of Zero's improvement patch is **required**, not optional. Install it before installing the HQ FMV project.

## Download

- [SG-HQ-FMV_2.1.zip](https://drive.google.com/file/d/1-iTgzpjWBqTQfC4SE43S9wYIheef3k1Q/view)
<br>

## Installation
- Extract the "languagebarrier" folder to `Steam\steamapps\common\STEINS;GATE`.

  
**The FMV pack should be installed "on top" of the [improvement patch](https://steamcommunity.com/app/412830/discussions/0/215439774868934160/), replacing existing files.**


I have a Steam thread regarding the HQ FMV project [here](https://steamcommunity.com/app/412830/discussions/0/2798319091587347187/) if any assistance is needed.
