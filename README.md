# aurelias-show-ripper
A tool to make ripping DVDs (or Blu-Rays) containing multiple episodes of a TV show less tedious

## Rationale
I like to go [thrifting](https://en.wiktionary.org/wiki/thrift#Verb) sometimes, and when I do, I will sometimes find a DVD box set of a TV show that I like, or that someone in my household likes. And being the geek that I am, I don't really want to muck around with the physical media. I'd much rather have it on my media server (e.g. [Plex](https://plex.tv)). And so I will open up [Handbrake](https://handbrake.fr/) or [MakeMKV](https://www.makemkv.com/) to rip the disc. But I need to figure out which titles on the disc correspond to which episodes, and if I want the metadata (episode title, show name, etc.) I have to go in and manually enter it for each episode. For shows with a lot of episodes (I'm looking at you, Doctor Who), this gets old fast. This tool is designed to automate away some of that tedium

## Enter Aurelia's Show Ripper!
When complete, this tool will scan a disk, get the episodes from [TVDB](https://www.thetvdb.com/), and rip them in a format of your choosing to a directory of your choosing. There will still be some user input involved, but hopefully much less than with the Handbrake GUI.



