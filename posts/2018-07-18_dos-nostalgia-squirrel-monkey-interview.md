---
uuid:             c26e6db1-06c5-4d6a-b886-aae780760556
layout:           post
title:            'Command Line'
slug:             dos-nostalgia-squirrel-monkey-interview
subtitle:         'Nearly 40 years ago, DOS reshaped computing on the IBM PC. These days, nostalgia for that era—and a dose of fresh creativity—is keeping its legacy alive.'
date:             '2018-07-18 03:01:00'
updated:          '2018-07-18 16:04:05'
author:           'David Buck'
author_slug:      david
header_img:       'https://tedium.imgix.net/2018/07/tedium071718.gif'
status:           published
language:         en_US
meta_title:       'The Creativity Driving DOS Nostalgia '
meta_description: 'Nearly 40 years ago, DOS reshaped computing on the IBM PC. These days, nostalgia for that era—and a dose of fresh creativity—is keeping its legacy alive.'
tags:
  - dos
  - ms-dos
  - ibm-pc
  - nostalgia
  - squirrel-monkey
  - the-8-bit-guy
  - jo-luijten
  - computers
  - computer-history
  - retro
  - homebrew

---

[whitebox]

_Hey all, Ernie here with a fresh piece [from David Buck](https://tedium.co/author/david/), who has moved away from his NES for a while to tell you all about how awesome DOS is as a creative medium. Yeah, DOS._

[big]**Today in Tedium:** From the early 90s, up until 2005 or so, I did much of my computer gaming on an American Megatrends IBM PC, running MS-DOS and Windows 3.11. I even got online once using Netscape Communicator. It wasn’t that I had a special affinity for legacy systems or felt nostalgic, it’s just that I have a gaming backlog going all the way back to 1994. These days, nostalgia is helping to revive interest in some of these legacy systems. One man has taken using DOS and QBasic to a higher art form with his Squirrel Monkey videos. In today’s Tedium, we’ll meet Jo Luijten—the man behind the nostalgia and examine how a legacy operating system is being used in unique and creative ways today. _— David @ Tedium_[/big]

[/whitebox]

[adbox bgcolor="#052D49" color="#ffffff" accent="#F96854"]

[![Tedium on Patreon](https://tedium.imgix.net/2017/11/patreonnewb.png)](https://www.patreon.com/tedium)

**Keep Us Moving!** Tedium takes a lot of time to work on and snark wise about. [If you want to help us out](https://www.patreon.com/tedium), we have a Patreon page where you can donate. [Keep the issues coming](https://www.patreon.com/tedium)!

[small]We accept advertising, too! <a href=“http://tedium.co/advertising/“>Check out this page to learn more</a>.[/small]

[/adbox]

[redbox]

[number]
### 1981
[/number]

**The year the original version** of the Disk Operating System (DOS) was introduced to the world. Coded by Seattle Computer Products employee [Tim Paterson](http://www.patersontech.com/dos/softalk.aspx) in the first half of 1980 (as QDOS—the quick and dirty operating system), DOS became the main operating system for millions of microcomputers of the time thanks to its early association with the IBM PC. In an [April 1986 interview with *Computer World* magazine](https://books.google.com/books?id=WwgoLLivAL0C&pg=PA54), Paterson talked at length about his experience with DOS. Written in 8080 Assembly language on a Z80 machine and later translated into 8086, the quick and dirty operating system would eventually be sold to Microsoft for $50,000 and become MS-DOS.

[/redbox][whitebox]

![IBM DOS](https://tedium.imgix.net/2018/07/0717_dos.jpg)

*The initial version of IBM DOS. ([Wikimedia Commons](https://commons.wikimedia.org/wiki/File:IBM_PC_DOS_1.0_screenshot.jpg))*

### A single tasking, single user, non-graphical command line operating system

**In early 1980, IBM was looking** for an operating system for its upcoming original personal computer. Microsoft had [already been working on an idea for an operating system for use with the 8086 chip](http://www.patersontech.com/dos/byte%E2%80%93history.aspx), pairing up with Seattle Computer Products to create stand-alone disk BASIC the previous year. While they waited for an 8086 version of CP/M (a massive subject on its own)—a [popular 8-bit operating system in wide use at the time](https://history-computer.com/ModernComputer/Software/DOS.html)—they grew impatient and set to work on an operating system of their own. From this impatience, a coder for Seattle Computer Products set to work on a new operating system—86-DOS.

In a [March 1983 interview with _Softalk_](http://www.patersontech.com/dos/softalk.aspx), Paterson discusses the DOS project:

> “We needed an operating system at Seattle Computer for our own computers and I wanted to do one. So we decided to go for it. I was waiting for Digital to come out with CP/M-86. I thought they would have it real soon. If they had beat me I wouldn’t have taken the trouble. I had always wanted to write my own operating system. I’ve always hated CP/M and thought I could do it a lot better. Step one was to write down what CP/M-80 did. Step two was to design a file system that was fast and efficient.”
>  
> One of the significant differences between MS-DOS and CP/M-86, when it finally appeared, was the file management system. CP/M usually provides a window to no more than 16K or 32K. With MS-DOS, the entire file is available. Paterson created QDOS’s file management module using the same method found in standalone Basic-86.


Eventually, Microsoft would release a GUI-based system that ran on MS-DOS, called Microsoft Windows—and the rest, as they say, is history. 

MS-DOS has a long and interesting history, expertly told over at [the Computer History Museum](http://www.computerhistory.org/atchm/microsoft-ms-dos-early-source-code/)—where you can also download the first two versions of MS-DOS for noncommercial use and we won’t touch on the CP/M vs. DOS controversy here—[_WIRED_ already did that in 2012](https://www.wired.com/2012/08/ms-dos-examined-for-thef/)—but it remains a fascinating subject. Perhaps the most interesting thing about MS-DOS in 2018 is how nostalgia for the operating system is driving creativity online in new and different ways.

[/whitebox][redbox]

[quote]
### “When I designed DOS, I knew that fitting the cluster number in a single byte, limiting the number of clusters to 256, wouldn’t get the job done as disks got bigger. I increased the FAT entry to 12 bits, allowing over 4000 clusters. With a cluster size of as much as 16K bytes, this would allow for disks as large as 64MB. You could even push it to a 32K cluster and 128MB disk size, although that large cluster could waste a lot space.” 
[/quote]

**— Tim Paterson, from his personal website**. Paterson [wasn’t happy with the way CP/M tracked disk space](http://dosmandrivel.blogspot.com/2007/09/design-of-dos.html?m=1). He was concerned with poor performance, especially while searching for files. Because FAT entries are stored as a chain, it’s much faster to read files.

[/redbox][whitebox]

![Planet X3](https://tedium.imgix.net/2018/07/0717_planetx3.jpg)

*A screenshot of Planet X3's tile editor, running in DOSBox. (via The 8-Bit Guy's Facebook Page)*

### The YouTuber that made more than $100k on Kickstarter by building a DOS game

**Some legacy operating systems** [occasionally find strange and new applications](https://tedium.co/2017/04/20/obscure-operating-systems-os2-qnx/) long after they’ve become obsolete, and DOS is no exception. Take the case of David Murray—perhaps better known for his YouTube channels [The 8-Bit Guy](http://www.the8bitguy.com/) or [8-Bit Keys](http://www.the8bitguy.com/category/8-bit-keys/)—a guy who’s programming a [brand new game in DOS](https://kotaku.com/in-2018-a-pc-game-is-being-made-in-dos-1827463766) in 2018.

Following the massive success of his [Kickstarter campaign](https://www.kickstarter.com/projects/1973096722/planet-x3-for-ms-dos), Murray is unleashing _Planet X3_ into the world. The game is a sequel to Murray’s Commodore 64 homebrew _[Planet X2](http://www.the8bitguy.com/planet-x2-announced/)_, from 2017. He’s getting remarkably close to finishing the game, but creating an MS-DOS game in 2018 is not without its challenges. 

In a recent interview with [_Gamasutra_](https://www.gamasutra.com/view/news/320530/Meet_the_dev_making_his_first_DOS_game__in_2018.php?elq_mid=85651&elq_cid=13565941), Murray discusses these challenges—predominantly related to graphics and storage space—and expresses his excitement about making an MS-DOS game in the modern day, an excitement shared by his fans.

He also points out that while the game will be released on physical media—3.5 inch and 5.25 inch floppy disks, of course—most folks will probably use an emulator like [DOSBox](https://www.dosbox.com/). 

“A lot of people want the physical media and box,” he noted to the website. “Granted, a lot of those people will never use the physical media, they’ll use the digital download and they’ll play it on DOSBox, but nevertheless, they want to own it, and that’s part of the appeal of it.”

While DOS is still being used to create and play games, there’s another unique use of the operating system—multimedia production. 

[/whitebox][redbox]

[quote]
### “The idea of creating a non-existent world in the past intrigued me. Although it’s not my goal to make realistic what-if videos, I think that the vast majorities of retrofied social media, games and websites could have worked in the Eighties.” 
[/quote]

**— Jo Luijten,** a Dutch television engineer who lives and works in the United States, on why he created Squirrel Monkey and _Wonders of the World Wide Web_. Although partly motivated by nostalgia, it isn’t the only reason he makes his creations.

[/redbox][whitebox]

![Jo Luijten](https://tedium.imgix.net/2018/07/0717_weirdpauljo.jpg)

*Jo Luijten, right, shown with fellow YouTuber Weird Paul Petroskey.*

### Meet the guy who uses DOS to create multimedia productions

If you’re a regular reader of sites like [Nerdist](https://nerdist.com/?s=squirrel-monkey), [Boing Boing](https://boingboing.net/2018/07/16/what-would-ebay-have-been-like.html) or Wired (among _many_ others), then you’re probably familiar with the multimedia presence of Jo Luijten, though you may not know his name. The 40 year old Dutch content engineer started making retro inspired videos in 2012 when he began goofing around in MS Paint. The retro-inspired _Angry Birds_ scene he created was uploaded to YouTube and Squirrel Monkey— a [Youtube channel](http://www.youtube.com/squirrelmonkeycom) with fake VHS-documentaries that show what social media, games and apps would have looked like if they were made in the Eighties and Nineties—was born.

While he uses modern technology to edit and record audio, he still uses a combination of DOS and QuickBasic to create his Squirrel Monkey videos. Autodesk Animator, Schism tracker and Scream Tracker III clone to generate music and sound effects round out his legacy software arsenal.

For his recent [Amazon in the 80s](https://youtu.be/hUi-yUpBqo0) video, he used the following code:

![QuickBasic](https://tedium.imgix.net/2018/07/quickbasic.jpg)

Presented as a science and technology television program called _Wonders of the World Wide Web_, the show uses a VHS aesthetic and voiceover from Luijten’s wife, Kinna McInroe— a voice you may recognize from the feature film 1999 _Office Space_.

The show itself demonstrates a hypothetical look at what today’s popular sites and services may have been like in the area of MS-DOS and video stores. It’s like the [Video Professor](https://tedium.co/2016/11/15/video-professor-infomercial-history/) meets [Wondere Werald](https://nl.wikipedia.org/wiki/Wondere_Wereld) (a Dutch science and technology informational program).

Each segment has its own charms and humor, but here are a few of Luijten’s— and Tedium’s—favorites:

https://www.youtube.com/watch?v=xrYRH3PYYT0

*If Facebook were invented in the '90s …*

https://www.youtube.com/watch?v=2UgPAZtRErI

*Discord in the Eighties*

https://www.youtube.com/watch?v=hUi-yUpBqo0

*Amazon in the Eighties*

https://www.youtube.com/watch?v=qoU36wOBWPI

*If @Soundcloud was around in 1994 …*

https://www.youtube.com/watch?v=MsDIw3gXD74

*Twitch in the '80s*

https://www.youtube.com/watch?v=xGcrvGTMgkg

*Siri in the '80s*

https://www.youtube.com/watch?v=R6bZxUvb7K0

*Snapchat in the '90s*

https://www.youtube.com/watch?v=tqD9OCa8ywQ

*The Wikipedia in the '80s*

https://www.youtube.com/watch?v=jzPgOq89thw

*eBay in 1988*

Each Squirrel Monkey video is its own hilarious, self-contained skit and there are many more coming soon. Luijten is always open to collaboration as well and can be reached through his [official website](http://www.joluijten.com).

[/whitebox][redbox]

[quote]
### “Although my videos are situated in a parallel universe, the graphics bring back memories to many people. I often hear reactions like ‘this brings me back’ or ‘wow, I’m old.’ I’ve even received reactions from teenagers who don’t understand why they feel nostalgic as well.”
[/quote]

**— Luijten,** on reactions to his Squirrel Monkey content. His YouTube channel was at 50,000 subscribers at the time of our interview and has already grown to 60,000 at the time of publishing. He shows no signs of slowing down and works with smaller channels—such as [Weird Paul Petroskey](https://www.youtube.com/user/weirdpaulp) (regularly featured in several videos)—to help them gain an audience.

[/redbox][whitebox]

![International Guild of DOS Users](https://tedium.imgix.net/2018/07/0717_guild.jpg)

### DOS fan? Jo Luijten can make you an honorary member of The International Guild of DOS Users

**Despite its origins as a joke,** you too can be made an honorary member of [The International Guild of DOS Users](http://www.igodu.org/).

Per Luijten, the website began as a humorous repository of DOS-related information. Designed to have the appearance of a DOS-based tutorial program (or perhaps an early World Wide Web page), the site is a logical extension of the Squirrel Monkey aesthetic—a retro, stylized look at modern tech, dripping with nostalgia for the old stuff.

DOS is one of Jo’s favorite operating systems.

> I made IGODU.org in one evening when I was bored and jobless. Although it is a joke, I receive many serious requests by email from people who wanted to become a member. I replied and made them a lifetime honorary member.
>  
> As a child I grew up with command prompt based operating systems like MS-DOS and CP/M. What I like about both systems is that they are to the point, have a calm look, and that I am in control. New operating systems often do things that you don’t want them to do. A couple of days ago, I wanted to check my email before I had to go to work and suddenly Windows started to download a bunch of updates without asking me first. 
>  
> Sometimes typing commands works faster than clicking through settings, so in my college days, I programmed an application called WinDOS, that turns a Windows desktop into a DOS-screen so that you can use DOS-commands in a Windows environment. I also made a couple of new DOS commands like the command “pizza” that allows you to order online food. I never finished it.

IGODU is still not a true organization—it’s basically one big exercise in absurdism—but if you contact Jo through the site, he may just make you a lifetime member. Still, the site contains some useful information and the colorful, nostalgic design is fun in its elegant simplicity. You may even learn a few DOS tricks you’ve never known about before.

[/whitebox][redbox]

[number]
### three
[/number]

**The number of titles** in one of my favorite computer game series’ from the MS-DOS era, _Jill of the Jungle_. The 1992 arcade action/platformer from [Epic Megagames](https://www.epicgames.com/site/en-US/home) began life as shareware and sold well enough to spawn two sequels—_Jill Goes Underground_ and _Jill Saves the Prince_. With a mix of platforming and action/adventure, the game is short, fun romp from a long-gone era. The game is still fun, if a bit dated and can be played at the [Internet Archive](https://archive.org/details/msdos_Jill_of_the_Jungle_1992). While it reignited my interest in DOS gaming, I’m not the only one feeling nostalgic about this operating system these days.

[/redbox][whitebox]

### So … what if Tedium were published in the 80s?

**Most of us here at Tedium grew up with MS-DOS** and these early computer games and programs. _(Editor’s note: I’m currently staving off an addition to [Epic Pinball](https://amzn.to/2zPdtG7). I may not survive.)_ Combining that with some of our topic selections and our visual themes, it isn’t difficult to imagine what our publication would look like in the 80s. Jo was kind enough to create a GIF imagining what Tedium would look like in the 80s:

![Tedium for DOS](https://media.giphy.com/media/41fdAWZX887dBSHtAd/giphy.gif)

We would probably be more like an early BBS system, still chasing the long tail with glorious EGA graphics and a command line interface. Just load up your Tedium floppy disk and at the C:\ prompt, type:

```
C:\>cd\tedium
```

Then:

```
C:\tedium>read
```

Select your text size and topics, hit ENTER and enjoy reading Tedium! Feel free to send us suggestions by picking up suggestion cards at your local gas station and mailing them to:

Tedium: the Dull Side of the Internet
PO Box 10-NES
R. Stevie Moore Street
Springfield, USA*

_*not an actual address or real thing at all. Offer subject to change at any time. Not valid in the contiguous United States or anywhere. If you received a faulty disk, that’s a shame._

[/whitebox][graybox]

**There is a certain elegance to Luijten’s work.** It isn’t just the run-of-the-mill, “Hey, look! It’s something from now … but in the 80s!” type of disposable content that’s been done to death. The superb writing, editing and sophistication of _Wonders of the World Wide Web_ make it worthwhile to view the series multiple times while simultaneously showing off what a legacy operating system can do.

It’s not just David Murray or Jo Luijten dwelling on nostalgia. They’re actively using nostalgia to inject something fresh into their own modern day creations, just like our friends in the [NES homebrew community](https://tedium.co/2018/04/10/nes-homebrew-scene-history/).

Creating something new, yet familiar is being elevated to a fine art and Jo Luijten—the Squirrel Monkey himself—is at the heart of it.

_**Correction:** An earlier version of this story misstated the full name of DOS. We regret the error._

[/graybox]
