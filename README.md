# hexchat-shakespeare-insult

## What?
Shakespearean Insult generator script for IRSSI IRC client. Based on [this image from twitter](https://pbs.twimg.com/media/B9b6c0PIEAAJvao.jpg)

Ported from my [IRSSI script](https://github.com/0x27/irssi-shakespeare-insult) at the request of Reddit users.

## General Installation Notes
Drop it into your "addons" directory in Hexchat, and load it with "/py load shakespeare.py" or add to autoload. Reasonably painless to make work, compared to the absolute motherfuckery that was configuring irssi-python.

## Usage Notes
To use, just do /shakespeare to insult no one in particular (the open query window), or /shakespeare $nick to insult a specific user in the current channel.

## Screenshot
![Screencap](https://raw.githubusercontent.com/0x27/hexchat-shakespeare-insult/master/screenshot.png)

## Licence
Licenced under the [WTFPL](http://wtfpl.net), so do what you fucking want.

## Donate
BTC welcome, send to: 1F3sPdKSEL9mM8LBnymGG8Dv3QCPDSRYeh :>

# Bug Reports
Use the issue tracker. Its probably buggy as all hell, as it was my first dalliance with the Hexchat python API.

# Known Bugs
If you load the script multiple times, it will execute multiple copies of itself every time you call it. For example, if you load it 6 times, one call to it will blast out 6 insults. I have not yet figured out how to make it "blocking", and due to the sheer amusement value of it, have decided to not fix this until someone actually files a report :P
