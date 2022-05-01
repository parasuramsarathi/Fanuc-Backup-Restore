# Fanuc-Backup-Restore

Fanuc Backup & Restore is used to Creating the backup from the robot controller and Restoring files to the robot controller. The Backup & restore is performed by using the FTP Server & Clint functionality. The below image shows the application view of start-up. The application has 2 functions, they are

➢ Create Backup

➢ Restore Backup

   • Restore a selected file (Single file upload)

   • Restore all the files in selected folder
![image](https://user-images.githubusercontent.com/39395111/166147149-86546a94-a542-4cb5-9691-67129cf0f7d2.png)

**Create Backup**

To create the backup from the controller

✓ Connect the robot

✓ After the robot getting connected with a PC, Press Create Backup button.

✓ Select the backup folder and press “OK”. Selected backup folder shows in the display.

✓ Backup started, see the status of backup in the status bar (“Backup from the Robot Controller in Progress...”)

✓ Wait until the process completion (“Backup completed”), see the below image for your reference.

✓ If you want to open the Backup folder, Press “Open Backup folder” option under the “Tools menu”


**Restore Backup**

**1. Restore a selected file (Single file upload)**

This will upload the selected file into the robot controller. The selected file should be the Fanuc Programming file (.TP, .LS, .KL, .MN) or Fanuc Variable file (.VR) or Fanuc IO Configuration file (.IO). Other format files are not allowed to restore.

✓ Select the file and Press “Ok”

✓ Wait until the Restoring operation complete.

✓ If the Show log file is checked, it will show the restore log.

✓ If you want to show the log by using the “Show Restore log file” option under the Tools menu.

**2. Restore all the files in selected folder**

Restore by folder will not restrict by file formats. All the other options are same as Restore file.

**Help**

Help menu shows help file and About the software. Detail user manual is attached in the Help.

