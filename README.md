# Fanuc-Backup-Restore

Fanuc Backup & Restore is used to Creating the backup from the robot controller and Restoring files to the robot controller. The Backup & restore is performed by using the FTP Server & Clint functionality. The below image shows the application view of start-up. The application has 2 functions, they are

➢ Create Backup

➢ Restore Backup

• Restore a selected file (Single file upload)

• Restore all the files in selected folder


**Connect to Fanuc Robot**

Connect to the Fanuc robot using following steps. After connection only, Backup or Restore the files is able to perform.

✓ Enter the IP Address of the robot

✓ Enter the User Name & Password of the robot for user access credentials.

✓ Press Connect button

If the connection is successful or unsuccessful, you can able to know from the status bar.


**Create Backup**
To create the backup from the controller

✓ After the robot connected, Press Create Backup button.

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


**Open Web Browser**
This option is open the Internet explorer and shows the robot status, programs and comments.

✓ Enter the robot Ip Address and press “Open Web Browser” under “Tools menu”


**Output window:**

**Show all Network devices**

This Option show all the connected network devices for checking the device is connceted or not connected.


**Disconnect from the Robot**

✓ Press the Disconnect button to disconnect robot


**Help**

Help menu shows help file and About the software.

