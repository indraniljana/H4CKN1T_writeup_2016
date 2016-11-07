<b>Problem:</b>

Eight thousand years after this incident we found Znex V's QWERTY key-QR output of a part of the conversation. 
However, the output QR image got corrupted and got broken down into 36 different splits. 
Can you find the flag that is hidden in the QR code, if you know that the cipherkey is 26 letters long? <a href="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/QWERTY-QR/Q5.zip">(QR Code)</a>



<b>Solution:</b>

Since I do not use photoshop, I was first perplexed at how to solve this. Then it occured to me that I could use Office or something.
I do not know if there is another quicker way to solve this, I just dragged them around for half an hour before it looked good enough.
After completing the QR code, I scanned it to get "i0v 4k3 n0x wk07i3k? 50 600r 70 533 n0x!"

<img src="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/QWERTY-QR/Q5.JPG" />

However, it still didn't make sense in leet, and it struck me that it was a Qwerty cipher.
After deciphering it (google helped), the flag turned out to be "h0w 4r3 y0u br07h3r? 50 600d 70 533 y0u!"
