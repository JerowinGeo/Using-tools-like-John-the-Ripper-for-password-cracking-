# Using-tools-like-John-the-Ripper-for-password-cracking
## AIM:
To crack password hashes using John the Ripper in Kali Linux.

## DESIGN STEPS:
### Step 1:
Install John the Ripper using the command:

### Step 2:
Prepare the password hash file (e.g., using unshadow for Linux password and shadow files).


### Step 3:
Use John the Ripper to crack the hashes:

## PROGRAM:
Password Cracking with John the Ripper

## OUTPUT:
Cracked Passwords from Hash File
# Create a text file 
![image](https://github.com/user-attachments/assets/06bd2af8-d5a4-49bb-bc3f-71e870752be9)
# Create a Password-Protected ZIP File 
![image](https://github.com/user-attachments/assets/4a9a8caa-76fd-4ecb-a50b-b8aaa0519a4c)
# OR
```
zip -e secret.zip file.txt
```
Open John-The-Ripper Tool


![image](https://github.com/user-attachments/assets/4e698ea6-8e4b-42f3-8b4e-ef0c9efe34dc)
![image](https://github.com/user-attachments/assets/c680bc82-63e3-4821-b452-790964549b32)
# Generate Hash Using zip2john
![image](https://github.com/user-attachments/assets/026c80db-fe5b-48ae-b3c4-3fae513ed5da)
# cat hash.txt
![image](https://github.com/user-attachments/assets/f0e5c705-6989-44df-932c-f510cd79aac3)
![image](https://github.com/user-attachments/assets/109b0873-fd37-4754-bfdd-50811e864d6d)

## RESULT:
The password hashes were successfully cracked using John the Ripper.

