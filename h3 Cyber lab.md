x) Read/watch/listen and summarize:

Heinonen 2026: How to Install Linux to Virtualbox?
- Goes through the installation of VirtualBox & Debian.
- Goes through downloading a Debian ISO and explanation of what ISO image is.
- Guides on how to create a new Virtual Machine in VirtualBox. In this case Debian Linux.
- Has some Post-installation tasks like first system package updation.

My question:
- How to safely use the VirtualBox?

Karvinen 2020: Command Line Basics Revisited
- Works as an introduction to Linux command line, perfect beginner-friendly guide.
- Explains most important commands and concepts.
- Key topics are: remote access with SSH, navigation of the filesystem, file and directory management & command history + tab completion.

My question:
- What are the most important commands to learn at first?

Karvinen 2022: Cracking Passwords with Hashcat
- Article is an introduction to Hashcat, an security testing and password recovery tool. 
- Demonstrates how to crack hashes by using a dictionary attack.
- Encourages to learn about creation of custom wordlists and partipation to Capture the Flag exercies.
- Password testing should be only done ethically and legally, with an proper permission.

My question:
- Where does the ethical line of using HashCat go, when it comes to cracking passwords?

b) Linux. Install Linux on a virtual machine. Use Debian 13-Trixie:

- Installed Virtual Machine -> Started creating a new one:
<img width="3024" height="4032" alt="IMG_2096" src="https://github.com/user-attachments/assets/d82cb243-da7b-45af-b954-93afc262c3b2" />

- Added the VM -Name, Chose the VM Folder and ISO Image. After that chose Linux as the OS and Debian + Debian (64-bit)
<img width="3024" height="4032" alt="IMG_2097" src="https://github.com/user-attachments/assets/998250d5-f9a2-4eb8-8781-b3d8505d5db0" />

- Chose the Base memory and the number of CPUS
<img width="3024" height="4032" alt="IMG_2098" src="https://github.com/user-attachments/assets/b9651c3b-bec4-46c5-bb61-7fa706d3786d" />

- Specified to create a New Virtual Hard Disk and the Disk Size -> Finished creation
<img width="3024" height="4032" alt="IMG_2099" src="https://github.com/user-attachments/assets/34186eb5-f1a1-4d5d-bc1d-3c8a60ce3bc8" />

-Powered the test-debian with Start --> Start with GUI
<img width="3024" height="4032" alt="IMG_2100" src="https://github.com/user-attachments/assets/63709ae6-c84d-49c9-8f0a-e9e72286c957" />

- Ran in to the first error with the assignment?
<img width="1024" height="768" alt="b93752bc-8a15-404c-a301-28e5b3050635" src="https://github.com/user-attachments/assets/b2aace34-1599-4b09-82fa-ee25c9ab35e9" />

- Went through the setup once again, and after that the VM started running as It should. Chose Live system (amd64)
<img width="768" height="1024" alt="bab19450-2c33-48ec-85a4-4db90046aeb6" src="https://github.com/user-attachments/assets/d6de6bda-b99a-4709-b0ff-7d177b4b973b" />

- Now It was running and I started to install the Debian!
<img width="1024" height="768" alt="44f22f20-7424-44a1-a17c-d89786232346" src="https://github.com/user-attachments/assets/bd86a274-fcf8-4674-ac92-933fd970fecf" />

- Chose the language for Debian 13
<img width="768" height="1024" alt="fa16594e-ca66-42cc-9175-784a580492e6" src="https://github.com/user-attachments/assets/bb226a66-2564-4340-8832-26e9228b1804" />

- Set the Region to Europe and Zone as Helsinki
<img width="768" height="1024" alt="f0ff0c93-2a24-4bec-9c2c-5577560553ff" src="https://github.com/user-attachments/assets/20130db4-0e90-4e02-9584-c2b5f41dc756" />

- Changed the Keyboard to Finnish and Finnish (classic)
<img width="768" height="1024" alt="28d3be8b-a8c7-4c83-ba2e-5f69f74340a9" src="https://github.com/user-attachments/assets/ee34eff6-115a-4858-bbea-35709d38412a" />

- After that I chose to Erase disk and went to the next stage
<img width="768" height="1024" alt="5a3d4cb3-eeb3-4535-91c7-f13c7e63d30a" src="https://github.com/user-attachments/assets/e344c9d1-2347-490b-b5b8-c8c83be5f51c" />
<img width="768" height="1024" alt="324a0b06-a82a-4735-9fa4-e9ea06334de4" src="https://github.com/user-attachments/assets/00884343-a27c-4f86-b227-1c83f508bb53" />

- Started installation of the Debian
<img width="768" height="1024" alt="d170aa8b-8b88-44e3-b1f2-7b60bf3ad4cc" src="https://github.com/user-attachments/assets/955fb117-d54f-4ebe-b3f2-55ab76a394dc" />

- Once it was installed, restarted the system and logged in with the assigned username and password
<img width="768" height="1024" alt="c1fcaf6f-6752-46e0-b404-e9f43185188a" src="https://github.com/user-attachments/assets/537f33a9-15bc-40ef-8fcb-a7c6dc5e9ef1" />
<img width="768" height="1024" alt="02bbf2f8-2e34-431a-b390-17cd230fc37d" src="https://github.com/user-attachments/assets/4ea7ffb3-0399-45c6-8fef-a0cae262df9e" />

- Updated & upgraded the system to finish the installation
<img width="768" height="1024" alt="c3ce5579-c844-4923-8ac8-c997bf888931" src="https://github.com/user-attachments/assets/402f101a-74b5-4415-8bb0-9336144f1f52" />

c) Crack. Crack the hash 6b1628b016dff46e6fa35684be6acc96 . Install hashcat and follow the steps in the article to crack the example hash.

- Received the update & installed hashcat
<img width="768" height="1024" alt="dfcc518c-f189-444f-8e6e-9ca2e453f341" src="https://github.com/user-attachments/assets/bc9db304-66fc-4356-b000-5dd2444aa9cf" />
<img width="768" height="1024" alt="cc42a5fb-27be-4dde-a649-253d40f1703f" src="https://github.com/user-attachments/assets/d9c22310-bb37-4982-8e93-76d99e81888d" />

- Ran the command for mkdir & cd + got the github-location. After that ran the tar command. Now having had downloaded the rockyou.txt.tar.gz
<img width="768" height="1024" alt="d8dd7407-fe52-4e6f-86c9-efa7cd897eba" src="https://github.com/user-attachments/assets/4f2a094f-9f9f-4580-9564-d43f2854b651" />

- Ran the different commands related to rockyou.txt.tar.gz: tar xf, rm & head
- After that ran command wc -l
- Had problems with the hashid -m commandline?
<img width="768" height="1024" alt="8afb9def-54be-4ea5-9d3c-6a6ca51b216d" src="https://github.com/user-attachments/assets/742c9d8f-f06f-40c0-b54c-f4a0bf3a9133" />

- Ran the command hashcat -m 0 with the password
<img width="768" height="1024" alt="b84d2fc9-5847-4d31-9aa1-8192b42e0091" src="https://github.com/user-attachments/assets/4d15a1c4-8769-42b1-94b9-3b118a33ee15" />
<img width="768" height="1024" alt="56923da6-dd26-4a5d-9824-2deefcbba647" src="https://github.com/user-attachments/assets/c7a79b87-cf8e-4ddf-844c-e27ae60809c5" />

-Finally ran cat solved command to get the password
<img width="768" height="1024" alt="e762bec7-7509-4de3-ac66-3d6607c2ad0e" src="https://github.com/user-attachments/assets/bc969bbc-31b1-42ba-9be4-f0fc23dcb594" />

- I did it! First time for everything :)
