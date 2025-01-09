# Restore Quick Access Pinned Folders

As a 2nd Line Engineer with an MSc in Cyber Security, I often encounter challenges when migrating users from an old laptop to a new one. One common issue is the migration of pinned folders in Quick Access not syncing correctly, even when most files are stored in the cloud.

This repository provides a step-by-step guide to ensure all your Quick Access pinned folders are successfully transferred to your new device.

## **Steps to Restore Pinned Folders in Quick Access**

1. **Open File Explorer**  
   Press `Win + E` to open File Explorer.

2. **Navigate to the AutomaticDestinations Folder**  
   Copy and paste the following path into the File Explorer address bar and press Enter:  
   `%AppData%\Microsoft\Windows\Recent\AutomaticDestinations`  
   ![Step 2](screenshots/step2.png)

3. **Backup the Destination Files**  
   - Select all files in this folder (`Ctrl + A`).
   - Copy them (`Ctrl + C`).
   - Paste them into a new folder on your desktop or a cloud storage location.

4. **Access the Backup on the New Laptop**  
   Ensure the backup folder is accessible on your new laptop.

5. **Paste the Files into the Destination Folder**  
   - Navigate to the same path on your new laptop:  
     `%AppData%\Microsoft\Windows\Recent\AutomaticDestinations`
   - Paste the copied files into this location (`Ctrl + V`).

6. **Replace Existing Files if Prompted**  
   If prompted with a dialog, click **"Replace the file in the destination."**  
   ![Step 6](screenshots/step6.png)

7. **Refresh File Explorer**  
   Close and reopen File Explorer to apply the changes. Your pinned folders should now appear as they were on your old laptop.

## **Why This Matters**

Migrating pinned folders ensures that users maintain their workflow continuity, reducing downtime and frustration during device transitions. Sharing this method helps streamline IT support processes and enhances user satisfaction.

## **Contributing**

If you have additional tips or encounter issues with this process, feel free to open an issue or submit a pull request.

## **Connect with Me**

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/your-linkedin-profile) for more insights and discussions on IT support and cybersecurity.

---

**#ITSupport #2ndLineEngineer #TechTips #CyberSecurity #KnowledgeSharing**
