[[
title: About
]]
[TOC]

# Shawn Graham
Associate Prof of Digital Humanities
[@electricarchaeo](http://twitter.com/electricarchaeo)
- research blog at [electric archaeology](http://electricarchaeology.ca)
- open notebook at [shawngraham.github.io](http://shawngraham.github.io)
- office at PA 406
- email at shawn dot graham at carleton dot ca
- Office hours by chance or arrangement

<iframe width="560" height="315" src="https://www.youtube.com/embed/HaSblM-Qz3A" frameborder="0" allowfullscreen></iframe>

## About this site
This site is powered by [PyKwiki](http://pykwiki.nullism.com/) (see below)

Icons are from the [Noun Project](https://thenounproject.com/):

- 'Designer' by Marie Van den Broeck from the Noun Project
- 'Lock', by Jafri Ali 
- 'Robot', by Rutmer Zijlstra

Other images:

- 'Doc Brown' by [Martin Casanova](beyondthemarquee.com/3056/doc-brown-martin-casanova)
- 'Burnt and abandoned computer' by [Darkday](https://www.flickr.com/photos/drainrat/13262802714) 
- 'Hand Knitted Laptop' by [KateMonkey](https://www.flickr.com/photos/katemonkey/5665916936)

### Workflow
This site is a static site generated using the python package 'PyKwiki'. Individual files are written in markdown format. Then, at the command line, I run ```$ python pywkiki cache -f``` which reads all of my markdown files and turns them into static html. These html files are then synced to a github repository on the gh-pages branch. That branch is configured using a `CNAME` file to point to the subdomain I registered for this course, `grad.craftingdigitalhistory.ca`.  That subdomain is similarly configured with a `CNAME` entry via the cpanel to point back to `shawngraham.github.io`. This way, instead of futzing with ftp, I use version control to keep everything in sync. This also has the happy side effect that you can fork a copy of this site for your own reference.

I've used wordpress blogs in the past for course websites, and these work well enough. But I've become disenchanted with the Wordpress interface, and I rather like the idea of writing once, deploying everywhere. When I write in markdown, the plain text files stay with me and I can use `pandoc` to convert them to whatever else I need. The other thing is, these files will always remain machine readable, whatever Microscoft or Apple do. 

You, too, will learn how to do this.
