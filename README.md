## Background
My first event as an Exco Member at NYP InfoSec was an Intro to Linux Workshop - where we helped new members set up a Linux Virtual Machine and showed them around the command line interface. I created the TuxRescue challenge as a fun finale activity, where participants could put their new skills to practice cracking a challenge typical of our biannual CTF competitions.

TuxRescue appeared again at NYP's Youth Cyber Exploration Program in 2022, as part of a series of lessons introducing secondary school students to basic cybersecurity skills.

## How To Play
1. Download the challenge file [here](https://drive.google.com/file/d/1M8e8cUliJwthKtN1bAPZw_sI5lG2FQ4W/view?usp=sharing).
2. Copy the folder to a Linux machine (or virtual machine), and unzip it.
3. Refer to `instructions.md` for the challenge questions.
4. If you're stuck, here are some hints https://gchq.github.io/CyberChef/#recipe=ROT13(true,true,false,13/breakpoint)&input=R0hLRVJGUEhSIFp2YXYtUEdTIA0KVXZhZ2YNCg0KU3ludCAyOiBVYmogcG5hIGxiaCBmdWJqIHV2cXFyYSBzYnlxcmVmIHZhIHl2YWhrPw0KU3ludCAzOiBabnhyIGZoZXIgbGJoZSBzdnlyYW56ciB2ZiB2YSBoY2NyZSBwbmZyIG5hcSBxYnJmIGFiZyBwYmFnbnZhIG5hbCBya2dyYWZ2YmFmIChyLnQuIGNuZmZwYnFyLmdrZykNClN5bnQgNDogR3VyIHNuZmdyZmcgam5sIGdiIHFiIGd1dmYgdmYganZndSBndXIgcHV6YnEgYWh6cmV2cG55IHNiZXpuZw0KU3ludCA1OiBKdW5nIHFicmYgcm5wdSBxZW50YmEgZnBldmNnIHFiPyBUYmJ0eXIgbmFxIGZyciBqdW5nIHJucHUgcGJ6em5hcSBxYnJmLiANClN5bnQgNjogSnVuZyB2ZiBndXIgc25mZ3JmZyBqbmwgZ2IgZnJhcSB2YWNoZyBnYiBuIHBienpuYXE/IFViaiBwbmEgbGJoIGVyY2VyZnJhZyBjZXJmZnZhdCBndXIgJ1JBR1JFJyB4cmw/DQoNCg0KU3ZhcXZhdCBHaGs6IEdoayB2ZiB3aGZnIG4gY3JhdGh2YS4gR3VyIHByeXkgZ3VuZyB1ciB2ZiB2YSBwYmh5cSBvciBmem55eXJlIGd1bmEgaGZobnku&ieol=CRLF&oeol=CRLF

(enable the rot13 cipher to see the hints)

## Missions
Flag 1: Enter Dragon Inc. Look at the cat.


Flag 2: The second flag is hidden in plain sight.


Flag 3: The third flag is in a safe in the Study.
Create a text file called "PASSCODE" with the contents "TUXISHERE". Then find a way to open the safe.



Flag 4: The fourth flag is in the Robotics Lab. The flag has been hidden on a special microchip that can only be read by a robot. Create a robot and give it the microchip to reveal the flag.
Create a user called 'ROBOT'. Make ROBOT the owner and group owner of the document called 'MICROCHIP'.
Give read (r), write (w) and execute (x) permissions to the owner (ROBOT), but only read (r) permissions to the group and everyone else.

Run the command './activate' to read the microchip.
You may delete the user 'ROBOT' after you get this flag.



Flag 5: The clone lab is under attack by dragon clones! Each dragon produces a different output, but only one will reveal the flag.



Flag 6: Last flag! This one his hidden high up in the building. No one has beaten 3-second parkour course yet. Will you be the first?


Don't have a Linux machine? Here's NYP InfoSec's [Kali Linux Virtual Machine guide](https://docs.google.com/document/d/1-0Zw5csHRWN5aEPBWzG5d1bh0H4ET2Jz38X7I-dsvtc/).


Unfortunately, TuxRescue doesn't work Windows Subsystem for Linux (WSL).
