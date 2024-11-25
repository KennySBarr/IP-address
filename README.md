<p align="center">
 
![R](https://github.com/user-attachments/assets/8831c247-35ed-4b77-922c-7cf1df64d3a4)

</p>

<h1> Post Attack: Log Search IP Address Look up</h1>
In this activity, you will continue in your role as a security analyst at Candy Corp.
Candy Corp has recently experienced a network attack on its websites. It needs your help determining which Candy website was the main target of the attack.
Your manager provides you with log files for each of Candy Corp's websites.
Each log file contains the IP addresses that connected to each website on the day of the attack.
You are tasked with counting the IP addresses in each file to determine which Candy website was the main target of the attack.
<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Linux Command Line

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2> Naviating Linux

<p>

![Screenshot 2024-11-24 233827](https://github.com/user-attachments/assets/f8ad532d-f9af-4052-8e6f-924dfb684f82)

![Screenshot 2024-11-24 233847](https://github.com/user-attachments/assets/916e9280-aae2-441c-b3a7-1cb98ff77fbd)



>
</p>
<p>
STEP 1: There are log files for each website within this directory. Each log file contains a list of IP addresses.
 
- Each line represents an hour.

- Each line includes the IP addresses that connected to the website during that hour.


</p>
<br />

<p>
  
![Screenshot 2024-11-24 233859](https://github.com/user-attachments/assets/6e4b144c-3ce6-478f-81d9-103806410267)

STEP 2: Using man pages, research how to use the wc command to count the total number of IP addresses in each file.

Hint: There is more than one IP address on each line, so the line-count command will not work.

After looking through the man page commands, "-w" was the command needed to complete the next step of the lab



<p>
  
![Screenshot 2024-11-24 234632](https://github.com/user-attachments/assets/e05bcd8e-a75f-4675-913a-7d30c09b7711)





>
</p>
<p>
STEP 3: Run the command to determine which website had the most network connections and was, therefore, the likely target of the attack.

-  - Use "-w" with all the websites in the file on the command line
 
   - Example: wc 1.com 2.com 3.com -w
 
   - After using the command I came to the conclusion Peanutbuttery.com was the targeted site for the attack
  
</p>
<br />
