Kali Linux Task 2

This repository contains my Task 2 completed as part of my Linux learning journey.

Contents

- "zxc.txt" – Text file created for the assignment.

Skills Practiced

- Linux terminal commands
- File creation and management
- Git and GitHub basics
- Version control


**task 2**

1.Create A text ﬁle with name zxc.txt
“ Hello my name is <Yourname>, i got this course of linux and
said hello, and am tring to learn linux. I love linux, so i said HELLO
world "

**solution**

- create a text file named zxc.txt and add the text into the file

 -> echo "Hello my name is Yourname, I got this course of Linux and said hello, and am trying to learn Linux. I love Linux, so I said HELLO world." > zxc.txt

2. How many times did the word hello written?

   **solotion**

  command

   grep -c "hello" zxc.txt | wc -l
   
  this only count lowercase hello. Answer = 1

  command
  
  grep -oi "hello" zxc.txt | wc -l
  
  this counts all version of hello. Answer = 3

   4.how many words are there?

  **solution**
  
  command

wc -w zxc.txt

Answer = 22

LINUX FUNDAMENTALS

I made a short and easy-to-understand note from your Linux Fundamentals PPT.

1. What is Linux?

Linux is an open-source operating system based on the Linux Kernel.

The kernel is the core part of an OS that connects hardware and software and manages computer resources.
Linux was created by Linus Torvalds and released as an open-source project.
2. What is an Operating System (OS)?

An Operating System is the main software that allows users to Linux was created by Linus Torvalds and released as an open-source project.

2. What is an Operating System (OS)?

An Operating System is the main software that allows users to
interact with a computer.

It includes:

Kernel
Software applications
Desktop environment
File system
Window manager

What is Shell?

A Shell is a command-line interpreter that allows users to communicate with the Linux kernel.
It translates user commands into instructions understood by the kernel.

Common shells:

Bash
Zsh
Fish
SH

To check your current shell:

echo $Shell

Why Linux?

1. Lightweight and Fast

Linux can run on computers with lower hardware requirements.

2. Popular

Used by developers, servers, smartphones, and supercomputers.
There are hundreds of Linux distributions available.

3. Security and Hacking
   
Linux is widely used for cybersecurity because many security tools are available on Linux platforms.

4. Secure System
Linux has strong permissions and security features.

Linux Distributions (Distros)

A Linux distribution is a modified version of Linux with different tools, interfaces, and packages.

Examples:

Ubuntu
Debian
Kali Linux
Parrot OS
Arch Linux
Fedora
Android

Kali Linux

Kali Linux is a Debian-based Linux distribution designed for:
Penetration testing
Digital forensics
Cybersecurity learning

Features:

Desktop: XFCE
Package manager: APT
Shell: Zsh

Other Security Distros

->Parrot OS

-Debian-based system focused on:
                                -Security
                                -Privacy
                                -Development

Uses:
     -MATE desktop
     -APT package manager
     
Garuda Linux

->Based on Arch Linux.

Uses:
     -KDE Plasma desktop
     -Pacman package manager
     -Fish shell
    
WAYS TO USE LINUX

Linux can be used through:

1.Main operating system
2.Dual boot (Windows + Linux)
3.Virtual Machine
4.Cloud terminals
5.WSL (Windows Subsystem for Linux)
6.Termux on Android

->Virtual Machines (VM)

Virtualization allows one computer to run multiple operating systems.
It shares hardware resources like memory and CPU with virtual machines.

Examples:
         -VirtualBox
         -VMware
         -QEMU
         -Hyper-V

