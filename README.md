# Home-Lab-setup-scanning-vulnerbilities-using-Nessus-
Setting up a homelab and scanning vulnerabilities on metasploitable2 virtual machine

This project is about leveraging Nessus to scan for vulnerabilites on a deliberately vulnerable machine metasploit2
and creating a professional report that could be given to a CISO or any senior security employee for quick understanding 
of vulnerabilities existing , the potential business harm they can cause and solutions that can be implemented to secure 
the system.

The project can be done by using:
VirtualBox ( any virtualization platform ) 
Metasploitable2 machine image 
Kali linux virtual machine (or any other security capable linux distribution) , you can also use your actual linux based os if you want to 
Nessus Tool
In this case I have used my own Arch linux host machine as an attack machine 

Steps:
1.Download and setup 2 virtual machines (attack machine and metasplotable2)
2.Make sure they are on host-only network with the attached network adapter ( you can do this in the network settings of the virtual box) 
3.Initialize the metasploitable2 machine
4.Try to ping it using the attack machine to see if the network is estabilished
5.Setup Nessus tool on the attack machine
6.Start a network scan on the target machine 
7.After the scan is completed you can see the vulnerabilite and information found categorized on the basis of their criticality
8.Read about the vulnerbilities , their cve's and their patch or find alternate solutions to it
9.Create a professional report about your findings and solutions ,mention the business impact they can cause , include quick summary of any similar case and it's impact
10.Your project is complete (You can further study about the vulnerbilities and their exploits and try to develop solutions around it )

<img width="813" height="576" alt="Screenshot_2026-06-07_17-25-39" src="https://github.com/user-attachments/assets/7983cfc0-d5f6-40c1-9532-c478ad657b7c" />

<img width="714" height="834" alt="Screenshot_2026-06-07_17-22-16" src="https://github.com/user-attachments/assets/17138233-0e52-49e2-9fd8-2ec79073ec92" />

<img width="1610" height="811" alt="Screenshot_2026-06-07_17-21-26" src="https://github.com/user-attachments/assets/8f7d5687-565e-49ad-a630-0d2933c9d835" />
