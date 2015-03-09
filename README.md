livewall
========

Livewall is a simple bash script to let you display videos from YouTube or
your own computer as live wallpapers on Mac OS X.

It operates from the command line, because GUIs are hard.

Prerequisites
-------------

To use it, you need to have [VLC](https://www.videolan.org/vlc/) installed.
For YouTube support, you need [youtube-dl](https://rg3.github.io/youtube-dl/).
(We don't actually download Youtube videos, we just use it to get a streaming
URL we can pass to VLC).

Installation
------------

You need to put `livewall` somewhere in your PATH. Perhaps like this:

```
curl https://raw.githubusercontent.com/sgentle/livewall/master/livewall -o /usr/local/bin/livewall
chmod a+x /usr/local/bin/livewall
```

Depending on your `/usr/local/bin` permissions, you might need to put sudo in
front of those.

You also probably want to look at the source before you run it. You don't know
me very well, and maybe I'm trying to steal your passwords or replace every
video on your hard drive with Rick Astley. Seriously, the source is [only 8
lines long](https://www.youtube.com/watch?v=dQw4w9WgXcQ).

Usage
-----

Just type this
```
livewall ~/Downloads/mycoolvideo.mp4
```

Or this:
```
livewall https://www.youtube.com/watch?v=KUgrBTNbSe4
```

You can also specify a quality like this:
```
livewall https://www.youtube.com/watch?v=KUgrBTNbSe4 720p
```


I have a list of neat places to look for Youtube nature videos [on my
website](https://samgentle.com/posts/2015-03-09-livewall).
