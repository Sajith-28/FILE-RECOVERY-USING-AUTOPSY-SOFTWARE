# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE
## Name : AANKARSH
## Reg No : 212223233001
## AIM
To use **Autopsy Digital Forensics Tool** to retrieve deleted files from a disk image.

---

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tool**: [Autopsy Digital Forensics](https://www.autopsy.com/)  
- **Test Data**: Disk image file (`disk.dd`, `disk.img`, `.E01`)

---

## ARCHITECTURE DIAGRAM

<img width="577" height="785" alt="Screenshot 2025-08-22 151258" src="https://github.com/user-attachments/assets/0e9e4744-5534-4828-8715-d6210ba065c3" />

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  
<img width="1707" height="949" alt="image" src="https://github.com/user-attachments/assets/51b57107-f29d-4442-9eb6-3ac3be75b67b" />



### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

- Select **Local Disk** → **next** 
<img width="1919" height="1078" alt="image" src="https://github.com/user-attachments/assets/177c8c5e-11a3-4311-bc44-20158e7fc497" />



- Select Disk → **Choose the VHD drive (`Drive1`)**



- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  
<img width="1919" height="990" alt="image" src="https://github.com/user-attachments/assets/faad7e83-9796-4c6c-a9e6-5774fe96fd38" />


<img width="1919" height="1042" alt="image" src="https://github.com/user-attachments/assets/384b1982-64af-43ea-9d51-076fb49e419f" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0a5ca034-eba3-41ea-b151-df23c784fc87" />



- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :

#### Name : SAJITH AHAMED F
#### Reg. No. - 212223240144

### Folder before deleting the files
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/64a7bf29-9749-4c85-ba6c-bef790784a2a" />



### Folder after deleting the files
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/f7ffb5ef-1cdd-4124-b5da-9c93a270e8da" />



### Folder after extracting the deleted images using autopsy


<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/125d51b4-b90f-45a4-aca8-0cd6d22abb78" />


## RESULT:

Deleted files were successfully retrieved and analyzed using Autopsy.

