# Intro-to-Wireshark

### What is Wireshark?

Wireshark is a packct capturing and analyzing program. What wireshark essentially does is monitor and relay network communications on the network you are connected to.

## How to install Wireshark

### Mac and Windows Installation

Naviate to [Wiresharks Website](https://www.wireshark.org) and click the "get started" button, this should scroll you down to the downloads section, pick the download that best suits you 

![image](https://github.com/JoshuaHartz/Intro-to-Wireshark/assets/102620766/61ba2143-7f60-43e8-af3c-0a79676809f8)



### What can Wireshark do?

Wireshark can do many things. It is a very versitile tool, here are some of the things it can do:
1. Inspection of hundreds of protocols
2. Live packet capture and offline analysis
3. CLI support
4. complex filtering
5. VoIP analysis
6. analysis of different capture file formats
7. Decryption support
8. Coloring

and many more...

<br>

## Wireshark the Basics.

NCL has a category called Network Traffic Analysis. This category can be daunting to new-comers that have never used wireshark or any similar tools. There can be alot of information ranging from a few hundred to a few tens of thousands of packts. Overcoming a NTA challenge is recognizing what its asking and figuring out the best way to tackle what its asking. 


There is a few ways to think before even looking at the data inside the packets. After reading the challenge questions and getting an idea of what the challenge is about, I like to follow this process.

1. Figure out how many packets are captured. This can save you hours, typically NCL follows the pattern of 2 types of pcaps. very large pcaps, and small pcaps. A very large pcap is almost a dead giveaway that you will find the answers in the statistics or extra analysis tools that wireshark provides. With small pcap challenges you will most likely have to start digging through packets to scrape information together and hopefully come across what you are looking for.  

2. Uing information from the challenge, I like to scroll through the packets and see what protocols im dealing with. Just to see if I can find anything on the surface without getting too deep. If you identify any protocols that standout or anything "fishy" packet wise its probably going to be the best place to start your analysis. 

3. After this point, my next steps get tailored to the challenge at hand. Dont be afraid to toy around and experiment!

and if I have no idea what to do or what im doing I start googling. 


<br>

### Wireshak GUI

Now that you have a general idea on how to give the business to some packets, lets talk GUI.

When you first open Wireshark you are met with this:

![image](https://github.com/JoshuaHartz/Intro-to-Wireshark/assets/102620766/6be91ac8-376d-4c32-8a37-33ab106c050e)

This is the main menu. It will show you recently opened pcaps and your availiable active connections you can start capturing on. Under that there are also extra resources given to you by Wireshark and collaborators. 

Here I made a quick tutorial of what you can do in wireshark using a past challenge I got right. Its not a complete wireshark rundown, that would take forever to do, but its a taste to what wireshark can do.

[View the video](https://drive.google.com/file/d/17ShzioxyoGTobRnfBcyxO04YCm2mXzjh/view?usp=share_link)

I also strongly encourage the use of any external online resources, cyberskyline makes good videos as well on their own gym challenges. That brings me to my next reccomendation. When the gymnasium goes live, run through the NTA section to see how they like to use Wireshark and other tools. 





