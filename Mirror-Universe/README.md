Problem:

In the Leet galaxy, as the spaceship landed on Trevn, Nyna's excitement to see her twin-brother made her jump in the shuttle.
After all, this was a moment she had been waiting since major parts of the star, Geria got destroyed and 
her family travelled to a mirror universe far far away when Alan was just a year old.
"Thirty three years, since I met him. How old might he be?", asked Nyna.

"czBlN2wgN3VlMzMgbDM0ZTUu", replied the intelligent Mark I.

As we know, androids always reply in a hashed way, help Nyna decode Mark I's reply. 



Solution:

The reply is in Base64 encoded format, as can be realized if it is checked online for encoding detection on any of 
the abundantly available sites.
Sadly, the string we receive upon direct b64 decryption, “s0e7l 7ue33 l34e5.”, is not the flag.
Furthermore, it does not really make any sense if we try to read it.
However, if we look closely, keeping in mind that it is supposed to give us an age, we can after a few guesses figure out 
that the flag will actually be “f0r7y 7hr33 y34r5”, which reads “forty three years”.
I submitted this flag and it was accepted.
