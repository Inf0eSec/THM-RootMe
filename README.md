# THM-RootMe write-up
**CTF > RootMe Write-up**


RootMe>_ is a CTF for beginners to practice all the basic steps in pentesting using a linux machine as a target. The aim of this exercise is to gain root privileges and grab the flag > **root.txt** 

This CTF allows the player to practice their skills using several tools and techniques that can be found on Kali or the THM AttackBox along with resources found online. 

**Task 1 - Deploy the machine**

  Without further a-do let's get started and deploy that machine!
  
  
  
  ![deploy](https://user-images.githubusercontent.com/100538982/164940287-dc7117d9-8ad2-4a05-abb2-600f6494ab63.png)


**Task 2 - Reconnaissance**

The first stage in any attack is to garner as much information on your target as you can through reconnaissance. The first question in this task points directly to conducting a port scan on the target machine to discover any open ports and live services. Looking down further on through the questions for this task we are asked for the version of apache running on this machine as well as the service running on port 22.  Already we have some clues as to the ports that maybe open on this target without actually touching it.  

  *Q. Scan the machine, how many ports are open?*


 

  *Q. What version of apache is running?*
  
  
  
  

  *Q. What service is running on port 22?*
  
  
  

  *Q. Find directories on the web server using the GoBuster tool.* 
  
  
  

  *Q. What is the hidden directory?*




**Tak 3 - Getting a shell**

  Find a form to upload and get a reverse shell and find the flag.*

  *Q. User.txt?*

**Task 4 - Privilege escalation**

  Now that we have shell, let's escalte our privieges to root.

  *Q. Search for files with SUID permission, which file is weird?*

  *Q. Find a form to escalate your privileges*

  *Q. root.txt*

