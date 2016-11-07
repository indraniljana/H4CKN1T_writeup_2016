<b>Problem:</b>

Network packet capture of a very spooky user is here. Along with that, there is a private key. Can you find the flag? <a href="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/SpookShook-II/Q12.zip">(File)</a>

<b>Input Format</b>
The network file along with the key.

<b>Constraints</b>
No constraints.

<b>Output Format</b>
Find the flag from the capture, without trailing digits, if found any.
<br><br><br>
<b>Solution:</b>

After opening the capture file, I saw that there was a TLS encrypted connection.
However, we have already been given the private key, so we only need to use it to decrypt the communication.
In wireshark, I imported that RSA private key in the Preferences menu.
<br><img src="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/SpookShook-II/importkey.JPG"/><br><br>
After that, it was simply a matter of following the SSL stream.

<br><img src="https://github.com/indraniljana/H4CKN1T_writeup_2016/blob/master/SpookShook-II/ans.JPG"/><br><br>

As the instructions clearly ask to remove trailing digits, the flag turns out to be "39u7v25n1jxkl"
