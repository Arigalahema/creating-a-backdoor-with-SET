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
<img width="1689" height="931" alt=" (2)" src="https://github.com/user-attachments/assets/048b57ba-328a-43ba-92a9-98ca647ed348" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="1860" height="845" alt="bd4f3aab-d73b-4883-a4c4-76763dd16357" src="https://github.com/user-attachments/assets/a19510f5-7155-4c1b-90ea-dd3329f340de" />




It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="547" height="211" alt="595846254-dd3a38ee-b58d-4f8b-bf2a-530a15bde52e" src="https://github.com/user-attachments/assets/7372142d-111e-4376-a90c-bb0f7fb13e54" />




The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="1920" height="307" alt="595845317-32d7b1cc-5ffe-49fa-b674-8989d44434dc" src="https://github.com/user-attachments/assets/70ab6b66-897b-4e8d-a203-f24b1bcd0b8b" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="1920" height="635" alt="595845649-cc5a959a-3f62-4fc1-bf00-064d0de74d72" src="https://github.com/user-attachments/assets/24d5910d-93a1-4dcd-990b-4cfc4b139092" />




It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="1909" height="824" alt="06b79a6b-c508-4f6a-9db3-dabb764ae330" src="https://github.com/user-attachments/assets/966c21db-9aee-4920-bc60-6a9ea64e438f" />





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:





In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="902" height="1024" alt="_img_12021255784463804763" src="https://github.com/user-attachments/assets/6fa0a257-b9ce-4dab-938e-0f85bc6cb60d" />



SET logs the information regarding the Google credentials:
## OUTPUT


<img width="1024" height="563" alt="_img_11706331084865133380" src="https://github.com/user-attachments/assets/df7c630b-0d84-40f7-acf7-621e36baf7e1" />














## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
