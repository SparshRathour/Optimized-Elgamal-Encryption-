# Optimized-Elgamal-Encryption-
We have optimized the elgamal encryption method to increase its security
## Multiple encryption rounds

#### Randomized prime no picked

Run server file to enter the data to be encrypted and then encrypted message appears on client

Optimizations made in it
1. Multiple rounds of encryption make the algorithm hard to break via brute force attack.
2. We randomize the initial prime number picked, the number of integers in the private key (number of rounds) whichmakes it hard for the hacker to crack the system.
3. A new key is generated for each of the participants of theconversation after each round of communication, whichprevents hackers from gaining access to future messageseven if they intercept the keys of one communication.
4. Since we have modified an existing algorithm in a novelway, hackers who intercept the public key will be confuse das to what algorithm we have used to encrypt our messagessince the structure of our key system is different.
5. By padding the message with a random number of randomcharacters during encryption we ensure that the attacker cant guess the length of the original message.
6. By padding the message, we also make it useless for the attacker to try and change the message in anymeaningful way as he doesn’t know which part of themessage is a pad and which is the message.
7. Since we map the characters of the encrypted message back toUnicode, the encrypted message is not displayed in many Englishdevices as the characters aren’t supported by the device. This may make it seem like the messages are getting corrupted during transmit but they actually aren’t.

8. Since this is an asymmetric public-key encryption system the attacker cant decode the message without the private key of the recipient of the message.
