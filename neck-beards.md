# NECK BEARDS



Dude look at these neck beards. 

![](https://upload.wikimedia.org/wikipedia/commons/3/36/Ken_n_dennis.jpg)

Unix - It was developed back in 1969 by AT&T employees working at Bell Labs. Linux came about in either 1983 or 1984 or 1991, depending upon who's holding the knife. The GNU operating system was announced in 1983 by Richard Stallman and started in 1984, while the Linux kernel came about in 1991 courtesy of Linus Torvalds.Mar 24, 2008

![](https://pbs.twimg.com/media/DYHWYWuU0AEjzuJ.jpg)

### Operating Systems and Networks

> This section must introduce the modern computer OS foundations and it's filesystems and environments (unix/linux/dos). Booting up a board for the first time is essential and understanding the Linux/Unix and getting around, installing some packages and getting up and running to do some damage is key here. The creators of Linux/Unix/ terminals and bash could be explored. 

The history of Unix dates back to the mid-1960s when the Massachusetts Institute of Technology, AT&T Bell Labs, and General Electric were jointly developing an experimental time sharing operating system called Multics for the GE-645 mainframe. Multics introduced many innovations, but had many problems.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8f/Ken_Thompson_%28sitting%29_and_Dennis_Ritchie_at_PDP-11_%282876612463%29.jpg/1920px-Ken_Thompson_%28sitting%29_and_Dennis_Ritchie_at_PDP-11_%282876612463%29.jpg)

![](https://upload.wikimedia.org/wikipedia/commons/e/ee/Pdp-11-40.jpg)

![](https://upload.wikimedia.org/wikipedia/commons/d/d5/Version_7_Unix_SIMH_PDP11_Emulation_DMR.png)

![](http://sebastien.kirche.free.fr/ordinos/dec/pdp11/pdp11_002.jpg)

![](http://www.saccade.com/writing/projects/PDP11/PanelInCase_Side.jpg)

Ken Thompson, a programmer in the Labs' computing research department, had worked on Multics. He decided to write his own operating system.

![](https://pbs.twimg.com/media/DYHW1H9VQAAr7mS.jpg)

While he still had access to the Multics environment, he wrote simulations for the new file and paging system[clarification needed] on it. He also programmed a game called Space Travel, but it needed a more efficient and less expensive machine to run on, and eventually he found a little-used PDP-7 at Bell Labs.[4][5] On the PDP-7, in 1969, a team of Bell Labs researchers led by Thompson and Ritchie, including Rudd Canaday, developed a hierarchical file system, the concepts of computer processes and device files, a command-line interpreter, and some small utility programs.[3] The resulting system, much smaller than the envisioned Multics system, was to become Unix. In about a month's time, Thompson had implemented a self-hosting operating system with an assembler, editor and shell, using a GECOS machine for bootstrapping.[6]

History of the neckbeard.

![](http://res.cloudinary.com/dzryfxssm/image/upload/v1474555997/neckbeard_rnniog.jpg)

Note that all this led to the MAC OS
Note that Windows called theirs DOS



Show this if needed

![](https://upload.wikimedia.org/wikipedia/commons/thumb/7/77/Unix_history-simple.svg/2000px-Unix_history-simple.svg.png)


**CHAPTER WORKING NOTES**

* Bulleted list of the state of the chapter
* Todos
* ~~Tasks~~


## List of Technical Topics Covered

Before we can start hacking on anything, we need to ensure we have all the proper setup required. 

* Flash the Image
* Boot the PI
* Tour of Terminals & Linux - cheat sheet
* Segway to new tools built on Linux - skip to future -
* Our first BASH Script
* NPM, Node, Setup, IDE Intro
* Hello World (PI)

| Technical Takeaways |
| -- |
| Flash the OS |
| Boot to Root |
| Terminal Cheat Sheet |
| Bash some Packages |
| Node.js |
| NPM |
| Git |
| Hello World PI |
| 0:8 |
| 0:9 |
| 0:10 |

| Axiom Cards Unlocked |
| -- |
| Storage |
| Linux |
| Scripting |
| NPM |
| GIT |
| GPIO |

| Research |
| -- |
| PI Up & Running |
| Arduino Running |
| Environment Tutelage |
| [PI+UNO+Ubidots](https://www.hackster.io/daescobar/arduino-raspberry-pi-ubidots-made-easy-905d51?ref=search&ref_id=raspberry%20pi%20and%20arduino&offset=0)  |

# ART NEEDED...

![](http://placehold.it/800x500?text=KenThompson+Character+Working+Faces)
Ken Thompson character sheet plus working faces... 

![](http://placehold.it/800x500?text=KenThompson+DennisRitchie+working+at+a+PDP-11)
Ken Thompson (sitting) and Dennis Ritchie working together at a PDP-11


![](http://placehold.it/800x500?text=Shoulder+PDP-11)
Over the sholder shot close-up, just like Gou's over the sholder shots on laptop, of the PDP-11


**NOTES!**
SCREENPLAY TO ADD HERE -- need to flesh out this section asap.

GOU doing some serious hacking in unix, the unix cheat sheet -- getting the environments up and running and prepared to really do some hacking projects... SETUP... Need aretwork, bring in the stuff I got... padd around the stuff I got... 


This is where we need to boot up a system - this is where Gou's over should shots, booting the PI and other scenes come into play.

**PI SETUP SCRIPT**

1) I must *FLASH* the OS IMAGE if I want to boot the PI.

2) When I *BOOT* the PI with the IMAGE and hold F7 i get a [LINUX TERMINAL]

3) On Linux, I run [these commands] to get Node.js and NPM installed

4) When I install [GIT] using [NPM] i can then run any open source script or app.

5) When I *clone* a repo with GIT I can run it by following the README

6) If I [Install Gou's Remotify App] I can VNC or Terminal or SSH into my PI and get ROOT access and run any command on the machine I want. [add to Remoting In Chapter]

---

CHAPTER #
# NETWORK ACCESS

> Origins of the internet and networks. Brief history then immediate transition to modern day in Gou Sokyeo's life and knowledge of networks. 

**NOTE: **refactor the raw text below and create a refined set of storyboards and script based on it. Once complete, move to back or appendix. 

ARPANET adopted TCP/IP on January 1, 1983, and from there researchers began to assemble the “network of networks” that became the modern Internet. The online world then took on a more recognizable form in 1990, when computer scientist Tim Berners-Lee invented the World Wide Web.

![](http://worldwebforum.ch/download/attachments/12703568/03_13.jpg?version=1&modificationDate=1463641226643&api=v2)

Sir Timothy John Berners-Lee OM KBE FRS FREng FRSA FBCS (born 8 June 1955),[1] also known as TimBL, is an English computer scientist, best known as the inventor of the World Wide Web. He made a proposal for an information management system in March 1989,[3] and he implemented the first successful communication between a Hypertext Transfer Protocol (HTTP) client and server via the Internet sometime around mid-November of that same year.

erners-Lee was born in London, England,[21] one of four children born to Mary Lee Woods and Conway Berners-Lee. His parents worked on the first commercially-built computer, the Ferranti Mark 1. He attended Sheen Mount Primary School, and then went on to attend south west London's Emanuel School from 1969 to 1973, at the time a direct grant grammar school, which became an independent school in 1975.[1][14] A keen trainspotter as a child, he learnt about electronics from tinkering with a model railway.[22] He studied at The Queen's College, Oxford[1] from 1973 to 1976, where he received a first-class bachelor of arts degree in physics.

"I just had to take the hypertext idea and connect it to the Transmission Control Protocol and domain name system ideas and—ta-da!—the World Wide Web[27] ... Creating the web was really an act of desperation, because the situation without it was very difficult when I was working at CERN later. Most of the technology involved in the web, like the hypertext, like the Internet, multifont text objects, had all been designed already. I just had to put them together. It was a step of generalising, going to a higher level of abstraction, thinking about all the documentation systems out there as being possibly part of a larger imaginary documentation system."[28]

TCP, IP, UDP, POP, SMTP, HTTP, and FTP

Origins of TCP/IP - It is the set of communications protocols used for the Internet and other similar networks. It is named from two of the most important protocols in it: the Transmission Control Protocol (TCP) and the Internet Protocol (IP), which were the first two networking protocols defined in this standard.

History of HTTP - The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web. Hypertext is structured text that uses logical links (hyperlinks) between nodes containing text.

Invention of the IP Address, the internet, TCP/IP/ Protocols, SSH, etc. Only the need to knows that stood up. Intro to UNIX and the first OS systems. 

The hacks in this chapter are about getting into networks such as our own, accessing stuff running on our networks, including our root, the disk, etc. HEAVY on SSH'ing, remote control, even a VNC to finish up. 

> This is an important step in working with modern technology. Get root acces and control of the machines, their IP's, possibly SSH acess, VNC access, access to the code editors, etc.

**Segway to some functional stuff...
**

Ping is the most basic tool we use to check connectivity. We also use arp to check the local broadcast domain and the arp resolution table. traceroute(linux)/tracert(windows) is used to check the path to the destination host. “mtr” is a powerful tool to view the network part for a longer period of time, usually installed as an additional package. Windows version of mtr is also available, even a portable version. One more useful tool comes mostly of out the box is nslookup (windows and linux)  and dig for linux; they are very useful troubleshooting identifying dns related investigation. “whois” is one more tool useful to find out more in some ip or domain name, owner, contact authority, as number etc. Last but not the least netstat available both in windows and linux is a useful tool to find out the local network status easily. A follow the link for a detail tutorial on how to use these basic tools.

![](https://i1.wp.com/farm8.staticflickr.com/7082/7285929392_9b5fe3eb8f_z.jpg?zoom=2)



**Couple notes. Move this. **

The Raspberry Pi has no screen. All the available screens suck right now anyhow. 

We're going to setup a way for our phones to act as our linux shell and remote into our PI's static IP that we give it. 

This is the first major hacking into the PI event. This will be significant. 

**Important Links**
[Remote Control Raspberry Pi](https://www.gadgetdaily.xyz/remotely-control-your-raspberry-pi/)
Use web interface to control PI and get Terminal Access(read or write?)

[Node Wrapper on WPI](https://github.com/gavinhungry/wpi-gpio)
A no-frills wrapper around the WiringPi gpio command-line utility.

[Cams and Linux](http://elinux.org/RPi-Cam-Web-Interface)
Getting cam data and such.

**CHAPTER WORKING NOTES**

* Bulleted list of the state of the chapter
* Todos
* ~~Tasks~~


## List of Technical Topics Covered

Goals for chapter at this point...

* Understand all the relevant protocols and their history
* Get to TCP/IP/HTTP/SSH and give examples in technical and non-technical ways
* 

| Technical Takeaways |
| -- |
| TCP/IP |
| HTTP |
| NETSTAT & others |
| Identify all the network tools that come with linix |
| Understanding packets |
| Understanding SSH |

Turing and the invention of the FSM and modern varations of turing machines. This gets us to the point where we learn about binary, machine code, classifiers, algorithms, compilers, memory, stacks, heaps, etc. We get into the lowest level science of computers possibly then bring you back up high level so you don't have to re-invent the wheel or know too much of the low-level stuff. IE so you can use higher level language to abstract to do cool stuff \(ie do you really need to know all the deets about garbage collection?\), yes, enough to know what's really going on under the hood but not too much. There are many experiments and tests that can teach us about this and we will start by running them on our laptops in a fool-proof, simple to setup environment, before we even get into the PI. Once setup with some tools and an editor, we will dissect a PI and get into the anatomy of how they work, it's processor and eventually boot it and run some benchmark, memory and overclocking hacks. You'll ultimately walk away with a really good understanding of the tenants of computer sciences, how programs work and with the ability to execute your own scripts from your laptop or right from the PI using it's peripherals. It's the hello world chapter to computer science with some deep dives into low level computing and it finishes with the writing of a high level program, an intro to object oriented programs \(C program\) and a hello world script that takes full advantage and demonstrates the low level stuff at work.





