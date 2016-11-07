<b>Problem:</b>

Tracking the work of a scientist, we found a picture which he wrote to his son when he got an award some years back.
However, the image appears to be corrupted. Can you recover the thing he told his son?

<a href="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/Best-Wishes/Q9.png">(Image File)</a>
<br><br><br>
<b>Solution:</b>

I was sidetracked for a while because I don't know why I felt it was an audio file and spent a lot of time trying to figure out what
was hidden in it.
Then at one point I opened it in a hex editor and saw that it had it had the last 2 bytes of the PNG header.
<img src="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/Best-Wishes/q9.JPG" />

After that, I just copied the first 2 bytes of the PNG header (the PNG header is 89 50 4E 47 0D 0A 1A 0A) to the beginning of the file, saved it, and viewed it to get the flag.
<img src="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/Best-Wishes/Q92.png" />
