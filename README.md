# Zip-Bomb
A Zip-Bomb creator written in Visual C#


Zip Bomb

Warning & Disclaimer: This will most likely crash your compression program and maybe Windows in some case, so tread carefully :)
If there's enough demand I'll make more shit like this :) https://www.youtube.com/channel/UCrNwlOzrNyhzMbPGM8okmeA

I wont' explain exactly how this works, just kinda the simple theory, basically as everything is interpreted in binary, say for example you type direct binary into Notepad e.g. 11000111, the basic zipper e.g. Winrar/7-Zip basically compresses it so that it's 213031.
What this is translated into is 2 "1"'s, 3 "0"'s, and another 3 "1"'s, therefore the chatacters are reduced by 2 (from 8 to 6).
Obviously this is more effective at a larger scale since 2 chars are unlikely to cause a massive difference but yeah. So basically that's how your compression program (I recommend WinRar or 7-Zip) zips it, few Gb's into less than 1Mb.

I hope this kinda explains it haha I cba to go fully into detail, however if you've got any questions I'll be happy to answer them
