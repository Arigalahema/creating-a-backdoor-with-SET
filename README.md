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
## OUTPUT


<img width="707" height="897" alt="image" src="https://github.com/user-attachments/assets/8edb79d5-a692-4103-b804-aebe8093c2aa" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="413" height="247" alt="image" src="https://github.com/user-attachments/assets/2f130648-b51d-43c9-87ae-3e2bd032336e" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="865" height="623" alt="image" src="https://github.com/user-attachments/assets/9e3e9509-4754-4533-bf71-719039526adb" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT


1<img width="705" height="356" alt="image" src="https://github.com/user-attachments/assets/c7f4c9cc-ec8d-412d-b94e-3b386b80155a" />

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="840" height="386" alt="image" src="https://github.com/user-attachments/assets/96cb0397-dfeb-49e1-b610-b346ca591809" />


It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="837" height="415" alt="image" src="https://github.com/user-attachments/assets/7a8d4f2e-6894-43c7-bf2e-4881fa510d12" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="840" height="167" alt="image" src="https://github.com/user-attachments/assets/aa1618c2-465b-40ad-a7ff-29f0dcfdc414" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1007" height="868" alt="image" src="https://github.com/user-attachments/assets/ef1fe31e-8736-4dd0-95a6-5f4d59ff2448" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1566" height="451" alt="image" src="https://github.com/user-attachments/assets/8d4eb19a-5485-40da-96f6-e29d6d1f69f1" />










## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
