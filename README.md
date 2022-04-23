# THM-RootMe write-up
**CTF > RootMe Write-up**


RootMe>_ is a CTF for beginners to practice all the basic steps in pentesting using a linux machine as a target. The aim of this exercise is to gain root privileges and grab the flag > **root.txt** 

This CTF allows the player to practice their skills using several tools and techniques that can be found on Kali or the THM AttackBox along with resources found online. 

**Task 1 - Deploy the machine**

  Without further a-do let's get started and deploy that machine!
  
  
  
  ![deploy](https://user-images.githubusercontent.com/100538982/164940287-dc7117d9-8ad2-4a05-abb2-600f6494ab63.png)


**Task 2 - Reconnaissance**

The first stage in **attack** is to gather as much information on the target through reconnaissance. Reading through the first question in this task points directly to conducting a port scan on the target machine to discover any open ports and live services. 

  *Q. Scan the machine, how many ports are open?*
  
$>  

![nmap](https://user-images.githubusercontent.com/100538982/164941609-a051a910-658c-4227-a1c6-65bdc1c4e6dc.png)

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

