# Lab4: Describing combinatorial and sequential logic in Verilog 

In this lab, you will construct a basic ALU-like hardware module. You will write a small program for it in an assembly language, write the Verilog hardware description for the module, and simulate it with Verilator.

## Setting up your hardware development environment
For the lab work you will be required to remote connect to the Linux lab machines in Uni, or you can physically come in and use the terminals in the lab session. If remote connecting, and not using the physical Linux machines in the labs, I fully encourage you to embrace the command line and to do all of your development via ssh. I understand that this might be daunting for some, it was for me when I first started, so I have made some videos to try and help you along.

### Connecting to a machine in the Linux lab
To connect to a lab machine you will need a few things:
1. A linux lab account, COSIT should have emailed you with the details for this a week or two ago. Please let me know if you don't have one.
2. Setting up VPN access to the University. 
3. An ssh client with X11 forwarding setup on your local machine.

__Connecting to the Uni VPN__

Please follow the guides [[here](http://vpn.swan.ac.uk/)]. _(I'm sorry, I know pulse secure is painful, I wish they had not closed the ssh ports last year)_

__Setting up ssh and X11 forwarding:__

To setup ssh and X11 forwarding I have found the following tutorials helpful in the past:
* [[For Windows](https://youtu.be/FlHVuA_98SA?t=151)]
* [[For Linux (Ubuntu)](https://youtu.be/FlHVuA_98SA)]
* [[For Mac](https://www.cyberciti.biz/faq/apple-osx-mountain-lion-mavericks-install-xquartz-server/)]

Once you have that setup on your machine, pick a linux machine machine from [[here](machines/list.md)], and try and connect. 

## Basic bash and vim tutorial

I encourage you to try and work via ssh, using the bash terminal. In case you are not familiar with this, or need a quick refresher, then please watch the following short 5 min video that will demonstrate some basic usage.

<p align="center">
        <a href="http://www.youtube.com/watch?feature=player_embedded&v=ZfgbowDwgRU
        " target="_blank"><img src="misc/basic_vim_and_bash_usage.png"
        alt="Lesson Video" width="510" height="360" border="10" /></a>
</p>

## Testing out your lab environment

Once you've got ssh setup, connected to a machine, and familiarised yourself with bash and vim. Let's try simulating a hardware circuit. Please watch the following video:

<p align="center">
        <a href="http://www.youtube.com/watch?feature=player_embedded&v=r3rT3wBTRoU
        " target="_blank"><img src="misc/testing_lab_setup.png"
        alt="Lesson Video" width="510" height="360" border="10" /></a>
</p>
