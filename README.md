# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/cb9a5d78-2bff-4596-b5d7-801e7095c41c)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/0de124cc-2dfc-4d7d-bac1-c3f3478bd624)


It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/d28df64e-936c-4bdf-83b4-186433bab429)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/05206243-8084-4551-92b3-963d3d41f101)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/47e3ae1d-ae4c-4902-9672-46199b552ee4)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/3e8316c2-dabd-41f7-8345-89b86c58192d)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/dfe4fce0-2d57-44ea-824a-8e164dad0e59)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/992a7955-3d03-4ba3-8cab-fb2843b63788)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/6008455f-2da6-4a41-ad26-3544400ea5e9)

SET logs the information regarding the Google credentials:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/ef861a0e-1fdb-4da6-b3f6-c837b8232591)


SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![image](https://github.com/Bharath745/creating-a-backdoor-with-SET/assets/94508354/ff55c6c7-e5d8-42e2-a687-4bc842563351)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
