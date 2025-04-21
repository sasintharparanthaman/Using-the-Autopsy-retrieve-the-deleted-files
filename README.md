# Using-the-Autopsy-retrieve-the-deleted-files
# NAME:SASINTHAR p
# REG:NO:212223230199

## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

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

![Screenshot 2025-03-26 184953](https://github.com/user-attachments/assets/17e26995-ee06-4446-afe8-e2514f6e78b6)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![Screenshot 2025-03-26 185459](https://github.com/user-attachments/assets/4569e32b-81f8-47d7-b290-ecd16496aa1b)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**


![Screenshot 2025-03-26 185619](https://github.com/user-attachments/assets/bb5dc0bc-f600-42f1-8e97-089923955ab3)


- Select **Local Disk** → **next** 

![Screenshot 2025-03-26 185635](https://github.com/user-attachments/assets/d749e016-024c-42d0-8e8f-fe4544d3bd28)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![Screenshot 2025-03-26 190245](https://github.com/user-attachments/assets/c9d3274d-61ac-4ded-9bb2-4157e42782d3)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![Screenshot 2025-03-26 190331](https://github.com/user-attachments/assets/71efd68d-ab5b-420c-b0fe-c51a14def849)

- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
![Screenshot 2025-03-26 190346](https://github.com/user-attachments/assets/b8aba34c-b21c-4236-9701-a7b6475d0a5c)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![Screenshot 2025-03-26 190356](https://github.com/user-attachments/assets/2fc2ee0c-d880-43a7-87b8-b8d651b6fd72)


### Folder after deleting the files

 ![Screenshot 2025-03-26 190407](https://github.com/user-attachments/assets/7bb06554-51ae-454b-84d7-220d4dc903e5)


### Folder after extracting the deleted images using autopsy
![Screenshot 2025-03-26 190356](https://github.com/user-attachments/assets/ee04c49e-2dc0-445a-9881-f815942cb17d)


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
