# File Permission Task
1️⃣ Created the File /home/demo.txt
* sudo touch /home/demo.txt
- sudo → Runs the command as root (superuser) because /home might require admin privileges.
- touch /home/demo.txt → Creates an empty file named demo.txt inside /home

2️⃣ Changed the File Permissions
* sudo chmod 764 /home/demo.txt
chmod 764 → Modifies file permissions based on the task requirement:
- 7 (rwx) → Owner (root): Read, Write, and Execute.
- 6 (rw-) → Group: Read and Write.
- 4 (r--) → Others: Read-only.

3️⃣ Verified the File Permissions
* ls -l /home/demo.txt
- the ouput will be 
-rwxrw-r-- 1 root root 0 Feb 11 05:01 /home/demo.txt
✅ Completed Task
![image](https://github.com/user-attachments/assets/c2cf390e-58cc-4b7b-8a47-731dd636b827)
