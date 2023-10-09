# Description
*Using tabcomplete in the terminal will add years to your life, esp. when dealing with long, rambling directory structures and filenames: [Addadshashanammu.zip]*
# Hints Provided
*After unziping, this problem can be solved with 11 button presses (mostly Tab).*
# Approach Taken to Solving the CTF
I started by unzipping the provided .zip folder to my Downloads folder on my Linux VM. After unzipping, I opened the folder up in the basic file manager to take a look. When I realized that the file provided in the final folder was unopenable, I turned back to the Linux terminal to attempt reading it. 

At first, I tried to use `cat fang-of-haynekhtnamet` which displayed the file, but most of it was unintelligible ASCII symbols. 


After that first attempt, I remembered from a previous CTF that you could make a file an executable by using chmod. However that also failed, and I was left at a loss at what exactly I needed to do next.

After thinking about how to move forward, I decided to turn to another walkthrough to figure out was wrong about my approach. From there I learned that you must do `./fang-of-haynekhtnamet` to open the file. 

After doing that, the file was successfully opened, and the CTF flag was provided.
# What I Learned
I learned that a file can be opened by doing `./` which I did not know before as I am very new to this whole process.
