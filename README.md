### NAME : MANOJ K
### REG NO : 212222223001
# FILE-RECOVERY-USING-AUTOPSY-SOFTWARE

## Register Number : 212222240015
## Name : AUGUSTINE J

## AIM:
To use Autopsy in to retrieve and analyze deleted files from a disk image.

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

![image](https://github.com/user-attachments/assets/fc3b6366-ef6d-415b-bf1d-ff9c5c81c2cb)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![image](https://github.com/user-attachments/assets/d9d8c966-80d6-4a14-9c8d-229d10a7709a)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![image](https://github.com/user-attachments/assets/194ef365-4774-4003-b2eb-f6444ca77993)

- Select **Local Disk** → **next** 

![image](https://github.com/user-attachments/assets/330e2e21-552b-4975-b64e-82383a611caa)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![image](https://github.com/user-attachments/assets/e112c53c-035c-41f7-83d9-475ae90b6a5d)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

<img width="1258" height="839" alt="Screenshot 2025-08-28 132003" src="https://github.com/user-attachments/assets/79b9c3f3-cc9f-47b9-a615-a313148bf546" />


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
<img width="1250" height="635" alt="Screenshot 2025-08-28 131521" src="https://github.com/user-attachments/assets/ff7f9b09-f521-4096-a6d1-aa16a07f7ca5" />

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
#### Folder before deleting the files
<img width="1919" height="702" alt="Screenshot 2025-08-28 131542" src="https://github.com/user-attachments/assets/799258f0-034b-4c0d-b1a8-94e6dfde3779" />


#### Folder after deleting the files
<img width="1842" height="945" alt="Screenshot 2025-08-28 140138" src="https://github.com/user-attachments/assets/9ac03065-61cc-44ef-83c4-b9c9d7080a8c" />


#### Extracting the deleted images using autopsy

![WhatsApp Image 2025-09-27 at 13 42 55_60f0a980](https://github.com/user-attachments/assets/38c54dba-a640-4859-bafa-4da2cb8edcb5)


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
