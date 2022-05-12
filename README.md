# CSE2138(SYSTEM PROGRAMING)
Introduction
This is an individual project!
The purpose of this project is to become more familiar with machine level programming. 
Each of you will work with a special “binary bomb”. A binary bomb is a program that consists of a sequence of
phases. Each phase expects you to type a particular string on stdin. If you type the correct string, then the phase is
defused and the bomb proceeds to the next phase. Otherwise, the bomb explodes by printing "BOOM!!!" and then
terminating. The bomb is defused when every phase has been defused.
There are too many bombs for us to deal with, so we are giving each of you a different bomb to defuse. Your
mission is to defuse your bomb before the due date. Below, the two steps of the project are explained in detail.
Step 1: Get Your Bomb
Each “bomb” is a Linux binary executable file that has been compiled from a C program. To obtain your bomb, you
should download all the bombs from the Canvas service.
Each bomb for the class will be in a zip file called bombs.zip. In this file, you will find your special bomb
bombk.zip, where k is the unique number of your bomb indicating your student ID. You will only need your file
for the project. Inside your file bombk.zip, you will find the following files:
• bomb: The executable binary bomb.
• bomb.c: Source file with the bomb’s main routine.
Step 2: Defuse Your Bomb
Your job for this lab is to defuse your bomb.
You can use many tools to help you defuse your bomb. Please look at the hints section for some tips and ideas. The
best way is to use your favorite debugger to step through the disassembled binary.
Although phases get progressively harder to defuse, the expertise you gain as you move from phase to phase should
offset this difficulty. However, the last phase will challenge even the best students, so please don’t wait until the last
minute to start.
The bomb ignores blank input lines. If you run your bomb with a command line argument, for example,
linux> ./bomb psol.txt
then it will read the input lines from psol.txt until it reaches EOF (end of file), and then switch over to stdin.
To avoid accidentally exploding the bomb, you will need to learn how to single-step through the assembly code and
how to set breakpoints. You will also need to learn how to inspect both the registers and the memory states. One of
the nice side-effects of doing this project is that you will get very good at using a debugger. This is a crucial skill
that will pay big bonuses the rest of your career.
The first four phases are worth 15 points each. Phases 5 and 6 are a little more difficult, so they are worth 20 points
each.
