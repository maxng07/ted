#  <img src="https://github.com/maxng07/ted/blob/master/mi.png"> TED | Text-Encipher-Decipher 
TED or Text-Encipher-Decipher is a basic program to encipher or decipher a chunk of text similar to enigma machine. The encipher text can then be send over SMS, WhatsApp, WeChat, LINE and even email. The same program will decipher the encrypted message to produce the original text. This will be useful if you are sending a text or message over an insecure connection or you want to ensure true privacy even on secure communication channel.

This progam is part of a broader software application project to be used to transmit scrambled and encrypted text over both secure or insecure communication channels. This basic program is shared with the Public on general goodwill and to obtain feedback. With the later, sender can ensure no one is snooping or watching the message as text are enciphered before transmitting on an insecure channel such as the internet or SMS or popular Tencent Wechat. Even with a secure channel such as WhatsApp, the sender can ensure true privacy, only the intended recipient or group of recipients with the correct passphrase key can decipher the message. Different Passphrase key can be used, but the same key is needed to decipher the respective encrypted message encipher by that key. <p>
  
Ted supports <br>
(1) Randomness of encipher output text; the same text characters encrypted by TED will produce different message output every time, making it harder for anyone snooping around intentionally to guess what is being send. <br>
(2) Support of Double-byte Characters such as Chinese Character (汉子), TED should work on other languages. Do provide feedback of any languages that is not possible to be enciphered by TED. <br>
(3) Integrity check is being done during decryption, if any message is altered, deciphering will produce an error and program aborted. <p>

The author does not approved of any illegal use that can constitute or classify as illegal by respective Countries Government. You can send feedback through but the author is not obligated to provide any support.

<h2>Usage </h2>
`ted [options...]` <br>
Options: <br>
  -e  Encryption set to true by default, to decrypt set -e=false or -e=0 <br>
  -p  passphrase to be used for encryption or decryption. Please remember the passphrase used. <br>

</p>
For a quick tutorial on how to use TED, you can refer to the animated gif <a href="https://github.com/maxng07/ted/blob/master/ted.gif"> here </a>
  
<h2>Download </h2>
TED has been tested to work on MAC OSX, but should work on Linux and Windows. I welcome any contribution to test TED on both Linux and Windows system. <br>
You can download the latest binaries <a href="https://github.com/maxng07/ted/releases">here </a>: <br>

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


