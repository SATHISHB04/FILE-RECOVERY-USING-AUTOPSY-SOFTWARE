# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE

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
<img width="1920" height="1080" alt="Screenshot (52)" src="https://github.com/user-attachments/assets/c1496db4-5a37-4f85-8863-413902245937" />


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

<img width="1920" height="1080" alt="Screenshot (53)" src="https://github.com/user-attachments/assets/6a802e96-34e2-4c76-b0e7-16f7a7193b7c" />


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

- Select **Local Disk** → **next** 

<img width="1920" height="1080" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/2d9c5a0e-3130-4d43-9df6-55edf8dcfa9d" />


- Select Disk → **Choose the VHD drive (`Drive1`)**


<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/38933ec9-c650-4a3b-99dc-66b74528a2f5" />

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  


<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/734da96b-7914-4f06-afba-d43419d63450" />


<img width="1920" height="1080" alt="Screenshot (61)" src="https://github.com/user-attachments/assets/dbf93a85-a96b-4070-a906-02d8325dd161" />




- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :

#### Name -SATHISH.B
#### Reg. No. - 212224040299

### Folder before deleting the files
<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/b6c52d8d-dd0f-43e8-a48e-563efbe0120b" />


### Folder after deleting the files
<img width="1918" height="1077" alt="Screenshot 2025-08-29 094143" src="https://github.com/user-attachments/assets/7230d932-621c-4f3d-a550-90ab5b918864" />


### Folder after extracting the deleted images using autopsy


<img width="1920" height="1080" alt="Screenshot (62)" src="https://github.com/user-attachments/assets/50f6332e-7e57-467f-aabb-d7cb3c6239c8" />

## RESULT:

Deleted files were successfully retrieved and analyzed using Autopsy.

