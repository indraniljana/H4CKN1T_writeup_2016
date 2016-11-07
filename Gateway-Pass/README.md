<b>Problem:</b>

Jinko has always been a fan of doing forbidden things. 
This time he found a fantasy binary file to enter the Kingdom of Dreams, but he doesn't know how to get pass the secured password check. 
Help him with the password. Here is the <a href="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/Gateway-Pass/GatewayToKingdom">(binary file)</a>
<br><br><br>
<b>Solution:</b>
Ah! Good old reverse engineering!
As with most problems, I tried searching for strings in IDA, but couldn't find anything that looked like a flag.
Curious.
After flipping through some of the functions in the code, I saw that the main function looked interesting.
Time to try to decompile it.
After generating pseudocode in IDA 64bit, this is what I found:<br>
<img src="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/Gateway-Pass/gate.JPG"/>
<br>
As is evident, the characters of the flag are stored in individual variables. What we need to do is simply convert the ASCII code to char,
 and put them together to get our flag.
 
 The flag turns out to be "g00d g4m3 w3ll pl4y3d"
 
 GG EZ.
