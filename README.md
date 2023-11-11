# OpenSSH 4.7p1 CVE-2008-5161 Exploit
 

# Exploit Description 

The script first checks the version of the target SSH service to confirm that it is running OpenSSH version 4.7p1. If the version is correct, the script sets up the necessary parameters for the brute-force attack using a list of usernames and passwords from a wordlist file. The script then launches the exploit and waits for it to complete.

Once the exploit is completed, the script retrieves any active sessions that have been created and enters an interactive mode that allows the user to interact with the session.

To use this exploit, you must have the Metasploit Framework installed and configured on your system. You will also need to have a target system with OpenSSH version 4.7p1 installed and running.

# Setup Instructions
## 1. Set up a target system with OpenSSH version 4.7p1. You can use a virtual machine such as Metasploitable2 for this purpose.
![image](https://user-images.githubusercontent.com/87800233/236505619-3c582808-7779-46b7-a53d-f29a63252599.png)
## 2. Install the Metasploit Framework on your system. You can download and install it from the Metasploit website.

## 3. Clone or download the exploit code from the GitHub repository.
![image](https://user-images.githubusercontent.com/87800233/236511955-b5b4b1c6-2325-47b0-8a23-b16e6e43c129.png)

## 4. Install the Pwntools library by running the command pip install pwntools.
![image](https://user-images.githubusercontent.com/87800233/236504633-62627c10-88c5-4ef3-8ed4-d2746e12daf6.png)

## 5. Check your Target IP 
![image](https://user-images.githubusercontent.com/87800233/236505969-071ffac6-b657-4608-98a6-5c68493e5abc.png)

## In my case Its:-> 192.168.1.5
![image](https://user-images.githubusercontent.com/87800233/236506215-38dd8485-2a15-48b0-8e4b-e7370ca50373.png)

## Move to the exploit directory and give the execute permission to the exploit script by running the command ' chmod +x openssh_4.7p1.py '
![image](https://user-images.githubusercontent.com/87800233/236512436-0b172f2d-c45e-40bc-a2e3-b20c0e9bc18a.png)

### After all the setup, Now run the Exploit by gaving the Target IP

https://user-images.githubusercontent.com/87800233/236513807-b97fb778-aef0-4872-8878-e33b705c4b7b.mp4

# And here We Are In ( For The Win) and  Enjoy The InterActive shell.
