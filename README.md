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
![1](https://github.com/user-attachments/assets/ffe84e70-a60f-45ce-bf82-354ab23505ef)
- Create an txt file
![2](https://github.com/user-attachments/assets/947be5b1-386b-47ad-a334-622b15f9892a)
-  Create a Password-Protected ZIP File
![3](https://github.com/user-attachments/assets/3457aa14-0d5e-472a-ba1d-2e6a9671d9a8)
### OR
```
zip -e secret.zip file.txt
```

- Open John-The-Ripper Tool

![4](https://github.com/user-attachments/assets/f7e40ae9-aa91-4c8e-9357-390f23712f49)

![5](https://github.com/user-attachments/assets/56c595b0-b836-46bc-b688-a241437b208f)
- Generate Hash Using zip2john
![6](https://github.com/user-attachments/assets/442a6e71-6e99-4835-bb2a-0b6fcf034503)
- cat hash.txt
![7](https://github.com/user-attachments/assets/59c207a1-3936-4db7-8f05-6128724ed02b)
![8](https://github.com/user-attachments/assets/0e5794e2-7377-42cd-9aee-0488e5c5c8e9)

## OUTPUT:
Cracked Passwords from Hash File

## RESULT:
The password hashes were successfully cracked using John the Ripper.

