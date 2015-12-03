[[
title: Future Proofing your Research
tags: [sustainability]
]]
[TOC]

# Future Proofing Your Research

Back in 2003, Roy Rosenzweig wrote [Scarcity or Abundance? Preserving the Past in a Digital Era](http://chnm.gmu.edu/essays-on-history-new-media/essays/?essayid=6). Roy saw that the seeming abundance of historical materials online was illusory, that without proper training and funding, we would *lose* materials. If anything [things have gotten worse](http://www.theatlantic.com/technology/archive/2015/11/the-irony-of-writing-about-digital-preservation/416184/). However, there are important projects afoot that are trying to address this memory pit - projects like ['Web Archives'](http://webarchives.ca/about) and [The Internet Archive](https://archive.org). Google around the Internet Archive though and you'll find that there are concerns. Recently, Scott Weingart wrote about the Shoah Digital Archive, and the ways the [physicality of digital preservation can continue violence against the dead](http://www.scottbot.net/HIAL/?p=41498). 

But let's dial back a bit. What about our personal research?

## Bricks

<img src="/uploads/burntcomputer.jpg" style="PADDING-RIGHT: 5px"align="right">
I wrote my PhD from 1999 - 2002. I had a Toshiba laptop. I backed everything up onto iOmega zip drives. I was cutting edge, baby. One day, the screen on the laptop completely fritzed out. No problem; the laptop had a serial port, and I wired it up to a 17" (17 inches from about 8 before - this was _major_!) cathod-ray-tube monitor. Then the keys got too sticky with gunk, so I plugged in an external keyboard. My FrankenSystem got me through the PhD. 

Then, things changed. USB was invented. My life took me away from academia for a while. When I came back, and wanted my files, they were trapped - the 3.5" drive I had still worked, but none of my current machines had 3.5" drives. The woman from tech support managed to free the contents of my hard drive, and put them onto a cd-rom for me. All of my data was in dbase files; my writing was in .wpd files, and the graphics were in some format that used an unrecognizable file extension.

What was worse, this was just what I *remembered*. I couldn't actually read my data because it was encrypted and compressed to save space on the harddrive, using some Microsoft utility that was discontinued in '99, and I couldn't solve this problem.

Physical bricks, digital bricks: my data was all more or less lost. Only the stuff I published as _tables_ at the appendix of my _printed_ thesis survived, because I was able to OCR them and copy the data into Excel. (I did find some Excel files I made, but they were just awful, awful.)

## Backups and security

I invite you to read how I lost the [HeritageCrowd Project](electricarchaeology.ca/2012/05/18/how-i-lost-the-crowd-a-tale-of-sorrow-and-hope/). There, I built a horribly complicated system to encourage crowdsourced memories about the area. Because the site allowed user input forms connected to my database, robots (! - not even humans) were able to take down my site by first, abusing it to try to sell Viagra, and secondly, recognizing the site was compromised and taking it off line.

*Poof*

Work all gone. (Silver lining: an automatic backup of the mysql database was recovered). 

## The lesson

Two cautionary tales: hardware backups are only as good as they are current technology; writers of digital history need to be aware that there are other active agents involved. The other thing to observe concerns the technology that _did_ work, printed paper. Paper has a lot going for it. It's a low-level tech in that reading it involves only being able to see it (whether or not you can read the language is a function of script as a technology, and the culture of teaching and social values in which you are embedded). For we digital historians, the lessons are this.

1. have a backup and versioning strategy that transcends the hardware you happen to work with
2. keep your data in as simple a format as possible - human readable, able to be printed cleanly if necessary, and (most importanlty) able to be read by any computer now and into the future. That is to say: write your text in plain text (txt or md files), and keep your data in plain text as well (that might mean a table where commas separate the values - csv - or tabs - tsv).

Once we start figuring out our own personal futureproofing issues, we can begin to scale back up to the online world in general.

# Needful things
You will need then a text editor. Any of the default notepads or wordpads that come with your machine are not good enough (in most cases) because they still embed hidden typographic codes etc in your text. Download, and install either [Sublime Text](http://www.sublimetext.com/) or [Atom](https://atom.io/). The next part of your toolkit is [Pandoc](http://pandoc.org/). Download and install it. Finally, go to [Github](http://github.com) and sign up for an account. Download and install Github's desktop client.

You will be astonished at the things you can do with a simple text editor and pandoc, with an online repository in which to host things. 

As you progress through this course, you will end up adding to this basic toolkit. About time we started using these wonderful machines for things more than cat videos, eh?

(By the way, get [Screen-cast-o-matic](http://screencast-o-matic.com/). A quick video to share when things are going wrong does wonders for resolving stuff quickly).
