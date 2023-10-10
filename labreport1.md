# Lab Report 1 - Remote Access and FileSystem (Week 1)

## I will be explaining how these 3 basic filesystem commands work through example: 

* cd
* ls
* cat

## I will be exploring these commands through these 3 questions:

1) **What happends when we use the command with no arguments?**

![Image](labreport1cse15la.jpg)

* In this screenshot, the working directory was /home throughout the inputted commands 
* Outputs and reasoning behind them-
1) When we inputted cd, nothing happened since we didn't input any directory we wante dto chnge to, so we stayed in the working directory of home
2) When we inputted ls, since we were in the working directory of home, it printed out the only directory lecture1 inside it
3) When we inputted cat, I think there was an error, becuase the text cursor moved down and I couldn't use the terminal properly anymore - if I inputted ls after this, it would just print the word ls again

2) **What happends when we use the command with a path to a directory as an argument**

![Image](labreport1cse15lb.jpg)

* In this screenshot, /home was the working directory for cd but ls and cat were inputted in the working directory of ~/lecture1 (/home/lecture1)
* Outputs and reasoning behind them-
1) When we inputted cd /home/lecture1, my working directory on the terminal changed to that
2) When we inputted ls /home/lecture1, Hello.class, Hello.java, messages and README printed in the terminal. These are are all the files present inside lecture1
3) When we inputted cat /home/lecture1, it printed out that /home/lecture1 is a directory - It seems to be checking whether a directory of that name exists

3) **What happends when we use the command with a path to a file as an argument**
      
![Image](labreport1cse15lc.jpg)

* In this screenshot, the working directory was /home throughout the inputted commands
* Outputs and reasoning behind them-
1) When we inputted cd /home/lecture1/messages/en-us.txt, it printed out bash nad then replied that /home/lecture1/messages/en-us.txt wasn't a directory. I'm guessing cd ussually takes directories and so thsi error message showed up becuase we inputted a file
2) When we inputted ls /home/lecture1/messages/en-us.txt, it just printed out teh path /home/lecture1/messages/en-us.txt again
3) When we inputted cat /home/lecture1/messages/en-us.txt, the contents of en-us.txt, 'Hello World!' printed
