# EncryptionForFun
 This repo is a collection of cryptography scripts which I have reproduced from sources I have found form books and online. The main source of motivation is the book "The Story Of Codes" by Stephen Pincock and Mark Frary


Book: https://www.amazon.com/Story-Codes-History-Secret-Communication/dp/1911130897


For simplicity I will mostly rely on the english language for statistical reasons, but other languages may come into use depending on the experiments I perform.

Language is the medium used to communicate with others. If communication is seen as the exchange between two or more parties, then cryptography is the practice of consealing the information within said communication, or message ($M$), such that the information evades all outsiders. This is done by "destroying" the syntactic structure of the communication (or message) as much as possible while still retaining some information which makes the original message understandable via some method of reconstruction. This reconstruction method usually require some common knowledge, called a "key" ($K$) used by the recieving party to decipher the destroyed message. A destroyed message is also called cipher text ($M'$).

In the scripts here I will implement methods for transforming $M$ into $M'$ and decoding $M'$ into $M$ by using the hidden key $K$. FOrmally then I define a method 
$D$($M$, $K$):-> $M'$
