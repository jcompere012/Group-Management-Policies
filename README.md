# Group-Policy-Management
Creating and configure GPOs

# Objective 
- Creating 2 GPOs within the domain controller and confirm there are working within the client machine

## Disable Domain Firewall GPO
- Created the GPO to turn off the firewall then configure it
- to test it add the lab client computer once confirm
- remove the Lab client VM and add the authenticated Users
- log into the client VM and verify the GPO is working
- Run Command "gpupdate /force "   "gpresult /r /scope:computer"

<img width="1733" height="850" alt="Screenshot 2025-12-10 at 5 03 04 PM" src="https://github.com/user-attachments/assets/1524917d-5eb3-4931-971f-1fec783010e1" />


<img width="1201" height="850" alt="Screenshot 2025-12-10 at 5 06 35 PM" src="https://github.com/user-attachments/assets/b6e7e705-b87d-4088-adc0-425f7a5c5af8" />

<img width="1201" height="850" alt="Screenshot 2025-12-10 at 5 08 55 PM" src="https://github.com/user-attachments/assets/c048c598-7472-4c70-958a-a20ece2fd75b" />

<img width="1201" height="834" alt="Screenshot 2025-12-10 at 5 09 46 PM" src="https://github.com/user-attachments/assets/3d46ff1c-1e91-4b96-bb2a-3ce484f95857" />

<img width="1201" height="293" alt="Screenshot 2025-12-10 at 5 10 45 PM" src="https://github.com/user-attachments/assets/f5be7385-733a-4c8d-a6ad-126240faa074" />

<img width="1201" height="771" alt="Screenshot 2025-12-10 at 5 13 19 PM" src="https://github.com/user-attachments/assets/6f5c9622-8b82-4d38-83ed-1256e19fcfc7" />


## Hide Control Panel
- Created the GPO to hide the control panel for a certain user
- configure the gpo to add the user and their computer
- Log in as the User `Lab\jbower` Apply the same update


<img width="1665" height="950" alt="Screenshot 2025-12-10 at 5 16 18 PM" src="https://github.com/user-attachments/assets/ff4551a0-0b1f-4ae8-a07d-dd88c556dbef" />

<img width="1211" height="768" alt="Screenshot 2025-12-10 at 5 38 19 PM" src="https://github.com/user-attachments/assets/039081d2-8369-4606-b166-da0965a023c8" />


<img width="921" height="595" alt="Screenshot 2025-12-10 at 5 39 36 PM" src="https://github.com/user-attachments/assets/c6d5e0c8-1d7c-4061-8235-d6790019b49b" />


<img width="968" height="184" alt="Screenshot 2025-12-10 at 5 40 49 PM" src="https://github.com/user-attachments/assets/86c76e32-65f3-488a-ad0c-9b6a34f14a30" />


<img width="968" height="184" alt="Screenshot 2025-12-10 at 5 40 59 PM" src="https://github.com/user-attachments/assets/87a00c4a-9577-49d5-b11b-c71025a79672" />























