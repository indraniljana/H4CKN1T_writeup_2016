<b>Problem:</b>

Network packet capture of a very spooky user is here. Can you find the flag? <a href="">(File)</a>



<b>Solution:</b>

As with all packet captures, I first opened it in Wireshark to see if I could find any big hints.
Surely, there was use of the TELNET protocol in abundance. It turns out that it was just a TELNET login.
As you might know, TELNET sends passwords as plaintext.
So I just clicked on one of the TELNET packets and followed the TCP stream, and the password popped right out, along with a username 
that looked so random that the problem setter must have set it in a hurry. Lulz, k?

<img src=""/>
