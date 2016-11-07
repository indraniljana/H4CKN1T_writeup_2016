<b>Problem:</b>

Network packet capture of a very spooky user is here. Along with that, there is a private key. Can you find the flag? <a href="">(File)</a>

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
<br><img src=""/><br><br>
After that, it was simply a matter of following the SSL stream.

<br><img src=""/><br><br>
