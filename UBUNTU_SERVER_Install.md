# OS Installation Guide

## Step 1: Reboot the Server
1. Restart the server and wait for the boot screen to appear.
<img width="1129" alt="Screenshot 2025-03-08 at 10 38 04 AM" src="https://github.com/user-attachments/assets/e2e6beb0-36bf-40a0-b0fd-40f4090d3db7" />

2. Look for the key assigned to `Invoke Boot Menu` (e.g., `F11`).
3. Press `F11` repeatedly until you see `Invoking Boot Menu` at the bottom of the screen.

---
## Step 2: Select Bootable Medium
1. The boot menu window will appear.
<img width="1440" alt="Screenshot 2025-03-08 at 10 44 15 AM" src="https://github.com/user-attachments/assets/23bce2cd-f55b-4e0f-8751-76104961d39b" />
2. Select the appropriate bootable medium, e.g., `hp v150w PMAP`.


---
## Step 3: Ignore Initial Prompts
1. You may see some dialogue windows; ignore them and wait for the Ubuntu welcome screen.
<img width="1440" alt="Screenshot 2025-03-08 at 10 58 00 AM" src="https://github.com/user-attachments/assets/84edcd01-198f-4434-a611-a50bfbf7b4f1" />
<img width="1440" alt="Screenshot 2025-03-08 at 10 59 28 AM" src="https://github.com/user-attachments/assets/f42d9fd3-15e0-49b7-b2d9-60c2fe63e70f" />
<img width="1440" alt="Screenshot 2025-03-08 at 10 59 19 AM" src="https://github.com/user-attachments/assets/90a91b22-474d-44f1-b6c3-5633d19ee658" />
<img width="1440" alt="Screenshot 2025-03-08 at 10 59 33 AM" src="https://github.com/user-attachments/assets/a36dfc68-e7be-4cbf-ba99-09d98efeeac1" />


---
## Step 4: Welcome Screen & Initial Configuration
1. Once the welcome screen appears, proceed with the default selections.
<img width="1440" alt="Screenshot 2025-03-08 at 10 59 38 AM" src="https://github.com/user-attachments/assets/cf40dc05-3478-472a-874b-1bb05acda433" />
<img width="1440" alt="Screenshot 2025-03-08 at 11 01 03 AM" src="https://github.com/user-attachments/assets/0e20479a-dad7-4a58-a15f-e9421d968fe6" />
<img width="1440" alt="Screenshot 2025-03-08 at 11 01 45 AM" src="https://github.com/user-attachments/assets/e4ddbc91-f539-4305-8cd4-f4f564b62aca" />

---
## Step 5: Configure Network Settings
1. Configure your network as shown below.
<img width="1440" alt="Screenshot 2025-03-08 at 11 03 23 AM" src="https://github.com/user-attachments/assets/e6c8165b-1ef5-413b-80e8-097a56758a0b" />
<img width="1440" alt="Screenshot 2025-03-08 at 11 02 32 AM" src="https://github.com/user-attachments/assets/79524677-a16e-4d86-8437-e1969e6189b2" />
<img width="1440" alt="Screenshot 2025-03-08 at 11 02 41 AM" src="https://github.com/user-attachments/assets/6c944cf3-c0fd-40e3-b8b6-d055ab7e7291" />
<img width="1440" alt="Screenshot 2025-03-08 at 11 03 08 AM" src="https://github.com/user-attachments/assets/0092c9d9-d9ff-4933-96e7-2bd08ba5bdef" />

> **NOTE:** Here you just need to change the `Address` Filed based on which server you are using, rest of the fileds (`Subnet`, `Gateway`, `Name Servers`) will reamin same for every server.

---
## Step 6: Continue with Default Options
1. Continue with the default settings on subsequent screens.
<img width="1440" alt="Screenshot 2025-03-08 at 11 04 48 AM" src="https://github.com/user-attachments/assets/792bd37f-3379-497f-a032-8afdf14aabc8" />

<img width="1440" alt="Screenshot 2025-03-08 at 11 04 57 AM" src="https://github.com/user-attachments/assets/056331ab-133f-471e-9710-c74e3bba3f12" />

---
## Step 7: Configure Storage
1. Ensure the `LVM group` is disabled. This is an important step.
<img width="1440" alt="Screenshot 2025-03-08 at 11 05 05 AM" src="https://github.com/user-attachments/assets/c5d575c2-ae00-489e-837d-5dc7d6ddd4f8" />
 
<img width="1440" alt="Screenshot 2025-03-08 at 11 05 21 AM" src="https://github.com/user-attachments/assets/7366b9c7-8d22-4679-a476-8ad80caf4664" />

<img width="1440" alt="Screenshot 2025-03-08 at 11 05 37 AM" src="https://github.com/user-attachments/assets/1f325320-7e65-42c3-b21e-95af6957fc83" />

> Make sure you have selected the disk with highest size available(default) e.g. 1 TB(931.51G) here and continue 
<img width="1440" alt="Screenshot 2025-03-08 at 11 05 51 AM" src="https://github.com/user-attachments/assets/0e7adb3e-fb7b-4b6a-87fc-8c21a4a0df9f" />

> Select continue and proceed


---
## Step 8: Profile Setup
1. Enter your profile details.
<img width="1440" alt="Screenshot 2025-03-08 at 11 06 13 AM" src="https://github.com/user-attachments/assets/6c0c8a11-1851-4445-bd9a-dd3c297f703a" />


---
## Step 9: Enable SSH
1. Ensure `Install OpenSSH Server` is enabled.
<img width="1440" alt="Screenshot 2025-03-08 at 11 06 31 AM" src="https://github.com/user-attachments/assets/ede9f504-2027-4f5b-b60b-e96405b283cd" />

---
## Step 10: Continue with Default Options
1. Proceed with default selections on further screens.
<img width="1440" alt="Screenshot 2025-03-08 at 11 06 39 AM" src="https://github.com/user-attachments/assets/ab3e7d4a-aec1-4f2b-84bb-7e69e0534be5" />

---
## Step 11: OS Installation
1. The OS installation process will begin.
<img width="1440" alt="Screenshot 2025-03-08 at 11 06 48 AM" src="https://github.com/user-attachments/assets/4db1e21f-3249-47e9-96c8-565368c35233" />
<img width="1440" alt="Screenshot 2025-03-08 at 11 06 51 AM" src="https://github.com/user-attachments/assets/d0a3f709-2aa2-4d7a-84e1-eebced05087f" />
<img width="1440" alt="Screenshot 2025-03-08 at 11 14 07 AM" src="https://github.com/user-attachments/assets/e732b669-4b71-44e8-afed-b26acda3c796" />

2. Wait until the installation is complete and the `Reboot` option appears.
<img width="1440" alt="Screenshot 2025-03-08 at 11 22 25 AM" src="https://github.com/user-attachments/assets/98b9dad9-57c7-4cfc-a9d9-7088473f609d" />

---
## Step 12: Final Step - Reboot
1. Click `Reboot Now` to complete the installation.

That's it! The OS installation process is now complete.

---

```note
NOTE:
1. There could be other steps too like enabling Ubuntu Pro, based on different OS versions. In such cases, just proceed with default options. Here, I have used `Ubuntu Server 20.4.5 LTS`.
2. Important steps in OS installation are:
   2.1 Storage Configuration (Disable LVM groups)

   2.2 Network Configuration (Set Static IPV4)

   2.3 SSH Setup (Enable `Install OpenSSH Server`)
```
