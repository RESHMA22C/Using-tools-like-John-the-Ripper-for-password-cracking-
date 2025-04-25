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
 create a text file
 ![image](https://github.com/user-attachments/assets/c58c5150-adc1-48c7-84f0-13c99d99141c)
Create a Password-Protected ZIP File
![image](https://github.com/user-attachments/assets/7c2aeaa2-3ead-442b-8987-bba70e26a6f9)
# OR
~~~
zip -e secret.zip file.txt
~~~
Open John-The-Ripper Tool
![image](https://github.com/user-attachments/assets/8c488979-0a2d-42a8-a3bc-990880fa6962)
![image](https://github.com/user-attachments/assets/b9d44170-a02f-47d4-b21f-833f8c05473b)
Generate Hash Using zip2john
![image](https://github.com/user-attachments/assets/d9c1d51a-86b3-4427-85c8-1435a3ed85be)
cat hash.txt
![image](https://github.com/user-attachments/assets/15e6dd28-a983-4cdc-9e11-dad9b0b6b55f)
![image](https://github.com/user-attachments/assets/3155436a-c5c3-4d0a-af6b-301d42876d67)


## RESULT:
The password hashes were successfully cracked using John the Ripper.

