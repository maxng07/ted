#  TED | Text-Encipher-Decipher 
TED or Text-Encipher-Decipher is a basic program to encipher or decipher a chunk of text similar to enigma machine. The encipher text can then be send over SMS, WhatsApp, WeChat, LINE and even email. The same program can be used to decipher the message to produce the original text. This will be useful if you are sending a text or message over an insecure connection or you want to ensure privacy even on secure communication channel.

This progam is part of a broader software application project to be used to transmit scrambled and encrypted text over both secure or insecure communication channels. This basic program is shared with the Public on general goodwill and to obtain any feedback. With the later, sender can ensure no one is snooping or watching the message as text are enciphered before transmitting on an insecure channel such as the internet or SMS. Even with secure channel such as WhatsApp, the sender can ensure true privacy, only the intended recipient or group of recipients with the correct passphrase key can decipher the message. Different Passphrase key can be used, but the same key is needed to decipher the respective enciphered message. <br>
Ted supports randomness of encipher text, the same text characters will produce different encipher message each time, making it harder for anyone snooping to guess what is being send. Ted also supports double byte character such as Chinese Characters, ted should work on other languages.

The author does not approved of any illegal use that can constitute or classify as illegal by respective Countries Government. You can send feedback through but the author is not obligated to provide any support.

<h2>Usage </h2>
ted [options...] <p<
Options:
  -e  Encryption set to true by default, to decrypt set -e=false or -e=0 <p>
  -p  passphrase to be used for encryption or decryption. Please remember the passphrase. <p>
<p>
<p>
For a quick tutorial on how to use ted, you can refer to the animated gif <a href="https://github.com/maxng07/ted/blob/master/ted.gif"> here </a>
  
<h2>Download </h2>
Ted has been tested to work on MAC OSX, but should work on Linux and Windows. I welcome any contribution to test it on both Linux and Windows system. <br>
You can download the latest binaries here: <br>
<h2>License </h2>
All Rights Reserved <p>
Text-Encipher-Decipher software uses a GO package for AES-GCMSIV which has a copyright license as part of BoringSSL. The copyright notice  is as below

/* Copyright (c) 2017, Google Inc. *

    This code was written to support development of BoringSSL and thus is
    considered part of BoringSSL and under the same license.
    Permission to use, copy, modify, and/or distribute this software for any
    purpose with or without fee is hereby granted, provided that the above
    copyright notice and this permission notice appear in all copies.
    THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
    WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
    MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY
    SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
    WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION
    OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN
    CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE. */


