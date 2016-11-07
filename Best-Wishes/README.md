<b>Problem:</b>

Tracking the work of a scientist, we found a picture which he wrote to his son when he got an award some years back.
However, the image appears to be corrupted. Can you recover the thing he told his son?

<img src="" />



<b>Solution:</b>

I was sidetracked for a while because I don't know why I felt it was an audio file and spent a lot of time trying to figure out what
was hidden in it.
Then at one point I opened it in a hex editor and saw that it had no file header!
<img src="" />

After that, I just copied the PNG header (89 50 4E 47 0D 0A 1A 0A) to the beginning of the file, saved it, and viewed it to get the flag.
