### REGISTER NUMBER : 212222230028
### NAME : DEEPIKA S
# LAB-1 Simulating the Forensics Lab Basics

## Aim :
   To install VirtualBox and set up a virtual machine(Kali Linux), install Autopsy and Sleuth Kit, and use them for forensic investigation by analyzing disk storage and file system.

## **Implementation Steps :**

### **Step 1: Install VirtualBox**
🔗 **Download VirtualBox**: [click here](https://virtualbox.en.softonic.com/)  

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.


### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Autopsy (GUI-based Forensic Tool)**
🔗 **Download Autopsy**: [Click Here](https://www.autopsy.com/download/)  

### **Installation Steps:**
1. Download the **Autopsy Windows Installer** from the official website.  
2. Extract the ZIP file and open the **bin** folder.  
3. Run `autopsy.exe` and set up a new forensic case for analysis.


### **Step 4: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version


### **Step 5: Create & Configure a Virtual Hard Disk (VHD) in Windows**

1. Press **Win + X**, Select Disk Management.
2. Click Action > Create **VHD**.
3. Choose a location and set a disk size (e.g., 10GB+).
4. Select Fixed Size or Dynamically Expanding and click OK.
5. In Disk Management, find your new disk (marked as "Not Initialized") -> Right-click the new disk → Initialize Disk → Select **MBR**.
6. Right-click Unallocated Space → **New Simple Volume** → Format the disk -> Click next → Finish.

---

## Output:

### **Virtual Box:**


![dfdi1](https://github.com/user-attachments/assets/9f9d15c7-990e-418a-935c-6ca463aeaae6)

---

### **Virtual Machine (Kali Linux)**


![dfdi2](https://github.com/user-attachments/assets/341d9085-24c2-45c1-9ee5-10f1b0465d85)

---

### **Autopsy**
![image](https://github.com/user-attachments/assets/32c14af6-2001-42e3-a880-c5d629bfede0)
![dfdi3](https://github.com/user-attachments/assets/45ae1f48-b238-49a6-ab68-064d70253029)
---
### **Sleuth Kit**
![dfdi sleuthkit1](https://github.com/user-attachments/assets/2ce303c5-a9cd-484e-acae-b0b770bc9b89)
![dfdi sleuth kit2](https://github.com/user-attachments/assets/e6b95c54-4caf-4a1e-b10f-0ddcab5f0330)


---
### **Creation of Virtual Hard Disk**
![dfdi new](https://github.com/user-attachments/assets/29fa9e3f-8939-4b8a-9b28-46e61d061b59)
![dfdi new1](https://github.com/user-attachments/assets/a184bd7e-8fa6-4001-9f68-c79c86819c07)

---

## Result :
The installation of VirtualBox, Autopsy, and Sleuth Kit, along with the setup of Kali Linux - Virtual Machine and the creation of a new virtual disk, has been successfully completed.
