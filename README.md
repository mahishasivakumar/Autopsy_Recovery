# File Recovery using Autopsy

```
Register Number : 212222040095
Name : Mahisha S
```
## AIM:

This experiment aims to demonstrate:

- Create a **Disk Partition**.  

- Adding, deleting, and recovering files using Autopsy.

- Understanding the forensic recovery of deleted data.

- Removing the disk partition after the process.

## Step1: Creating a New Disk
  
- The new Disk Partition is created as **MAHISHA S**.
  ![Screenshot 2025-03-20 095119](https://github.com/user-attachments/assets/fa6779d1-c6e5-4a7b-a8b5-a6dab3b6b290)


  
## Step2: Adding and Deleting Files for Recovery

## 1. Copy Files to the Partition:

- Open File Explorer → Navigate to the newly created drive (C: or D:).

- Transfer images or files into it.
![Screenshot 2025-03-20 100942](https://github.com/user-attachments/assets/1fde9b34-b001-4db1-8bb6-599498ec6791)


## 2. Delete Files:

- Select one or more files → Press Delete.

- Empty the Recycle Bin to permanently remove them.

## Step3: Recovering Deleted Files Using Autopsy

## 1.Launch Autopsy and Set Up a New Case:

- Run Autopsy as Administrator.

- Click Create New Case.
![Screenshot 2025-03-19 222716](https://github.com/user-attachments/assets/4028e969-add1-46c4-beb2-3f336c7dcd3d)

- Enter a case name (e.g., Autopsy1).
- Select a location for the case folder → Click Next → Finish.
  ![Screenshot 2025-03-20 101159](https://github.com/user-attachments/assets/96e4d9e3-403b-47e7-985c-48bfd5ee65e8)

- Add optional information
  ![Screenshot 2025-03-20 101237](https://github.com/user-attachments/assets/97a42cf6-4e45-4bca-9ee0-fc11c6a52b4c)




## 2.Add the Partition as Evidence:

- Click Add Data Source → Choose Host.
   ![Screenshot 2025-03-20 101338](https://github.com/user-attachments/assets/2cae65dd-0d06-43ef-989e-7f07dad19883)



- Select Local Disk → Click Next.
   ![Screenshot 2025-03-20 101349](https://github.com/user-attachments/assets/0eafbcca-b430-45c7-9f0c-b6c5254d799b)



- Choose Disk → Select the VHD drive (Drive1).
  ![Screenshot 2025-03-20 101605](https://github.com/user-attachments/assets/44d4a210-6c1d-463c-9e0e-fd8b2551bc7c)



- Click Next → Keep the default settings → Click Finish.
  ![Screenshot 2025-03-20 101752](https://github.com/user-attachments/assets/ced6643a-ef0b-4de8-b4b6-b9bae1e9ac44)



- Allow Autopsy to process the disk.

## 3.Extract Deleted Files:

- In the left panel, navigate to File Views → Deleted Files.

- Locate your deleted images.
  ![Screenshot 2025-03-20 101848](https://github.com/user-attachments/assets/574b42fd-c254-4652-82a8-da39a0dfdc6b)



- Right-click an image → Click Extract File.

- Choose a folder for saving the recovered files (e.g., C:\image_recovery).

- The deleted images are now restored!
  ![Screenshot 2025-03-20 101945](https://github.com/user-attachments/assets/0f0e48f4-d91e-471b-bd88-054746a29af1)

- Check the disk.
  ![Screenshot 2025-03-20 102013](https://github.com/user-attachments/assets/efa22c7a-2080-4019-8d01-5e02bae8ab9a)

  
## Step 4: Removing the Disk Partition (Optional Cleanup)

## 1.Using Disk Management:

- Open Disk Management (Win + X → Disk Management).

- Identify the created partition.

- Right-click on the partition → Select Delete Volume.

## 2.Alternative Method via Settings:

- Click the Start button → Go to Settings.

- Select System → Click Storage.

- Click Advanced Storage Settings → Select Disks & Volumes.

- View the list of available disks.

- Select the created partition → Click Properties.

- Click the Delete option to remove it.

## Result:

This experiment successfully demonstrates the creation of a disk partition, the deletion and recovery of files using Autopsy, and the proper removal of the partition after completing the process.


  



