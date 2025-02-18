# Silver Platter CTF
## Overview
---
Think you've got what it takes to outsmart the Hack Smarter Security team? They claim to be unbeatable, and now it's your chance to prove them wrong. Dive into their web server, find the hidden flags, and show the world your elite hacking skills. Good luck, and may the best hacker win!

But beware, this won't be a walk in the digital park. Hack Smarter Security has fortified the server against common attacks and their password policy requires passwords that have not been breached (they check it against the rockyou.txt wordlist - that's how 'cool' they are). The hacking gauntlet has been thrown, and it's time to elevate your game. 

Remember, only the most ingenious will rise to the top. May your code be swift, your exploits flawless, and victory yours!
Make sure you wait a full 5 minutes after you start the machine before scanning or doing any enumeration. This will make sure all the services have started. 

**What is the user flag?**

**What is the root flag?**
Recon / Enumeration / Port Scan
Null Scan Command: nmap –sN 10.10.161.182
Description: Sends TCP packets with no flags to test for open ports.
Open Ports:
-	22 / SSH
-	80 / HTTP
-	8080 HTTP-PROXY (Interesting)
 
NMAP Scans
nmap -p- 10.10.134.92 -Pn -T5 -v
nmap -p 80,8080,22 10.10.134.92 -Pn –v
