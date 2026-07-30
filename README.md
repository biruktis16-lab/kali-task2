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
