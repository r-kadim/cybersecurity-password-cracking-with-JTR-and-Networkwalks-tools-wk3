# NETWORKWALKS-RKADIM-B084-WK3-PM1 & PM2-PASSWORD-CRACKING-WITH-JTR-AND-NETWORKWALKS-TOOLS

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Cybersecurity-404040?style=flat-square&labelColor=C00000" />
  <img src="https://img.shields.io/badge/John%20the%20Ripper%20-v2.2-0070C0?style=flat-square&labelColor=000000" />
  <img src="https://custom-icon-badges.demolab.com/badge/Microsoft Windows%20-v10-0078D6?logo=windows10&logoColor=white" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-E87500?" />
</p>

##
The purpose of this lab is to learn to recover the password of a protected PDF files and help you learn how password cracking works and why it is important to use strong passwords.

##  Lab Configuration
*   **Host OS:** Windows 10 Home
*   **Host RAM:**  16.0 GB (15.8 GB usable)
*   **Processor:** Intel Core i7-11800H @ 2.3 GHz
*   **Graphics:** NVIDIA RTX 3060 Laptop GPU (6 GB), Intel(R) UHD Graphpics (128 MB)
*   **Storage:** Micron 3400 477 GB NVMe M.2 SSD, Western Digital WD10SPX 932 GB HDD

### Step 1 . Download and Install John the Ripper.
John the Ripper is downloaded from https://www.openwall.com/john/ and is installed in Windows computer.

**Tool:** John the Ripper, Windows

### Step 2 . Download and Install Johnny GUI
Johnny GUI is downloaded from https://openwall.info/wiki/john/johnny and installed in the Windows environment.

**Tool:** Johnny GUI, Windows

### Step 3. Add John the Ripper to Johnny GUI.
Open Johnny GUI and in settings browse to the John the Ripper executable file john.exe .
<p align="center">
<img width="578.667" height="463.333" alt="Johnny JTR link pg" src="https://github.com/user-attachments/assets/fd400a02-acce-488a-ae6d-ef7099d4666a" />
</p>

### Step 4. Downloaded the encrypted PDF files and uploaded them to a hash website https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php to get its hash.
<p align="center">
<img width="824" height="490" alt="hash website" src="https://github.com/user-attachments/assets/3dcc7432-d06c-4edf-b52b-87c1796bce1f" />
</p>

[My Locked PDF1.pdf](https://github.com/user-attachments/files/35129374/My.Locked.PDF1.pdf)
[My Locked PDF2.pdf](https://github.com/user-attachments/files/35129378/My.Locked.PDF2.pdf)
[My Locked PDF3.pdf](https://github.com/user-attachments/files/35129391/My.Locked.PDF3.pdf)
[My Locked PDF1 (for NW Tools Lab WK3-PM2).pdf](https://github.com/user-attachments/files/35129394/My.Locked.PDF1.for.NW.Tools.Lab.WK3-PM2.pdf)


### Step 5. Copied each hash to a text file.
<p align="center">
<img width="437.5" height="302" alt="hash files" src="https://github.com/user-attachments/assets/f729cd85-6ed5-4958-8952-4ec2f52415e7" />
</p>

### Step 6. Opened each hash text file in Johnny and clicked Start New Attack. For each text file a password is shown. 
<p align="center">
<img width="434.5" height="348" alt="cracked" src="https://github.com/user-attachments/assets/b9a34224-0092-41b6-8eb6-6799c24173e8" />
</p>

Used that specific password to open each specific pdf file. 

<img width="400" height="565" alt="image" src="https://github.com/user-attachments/assets/a47c8f25-7bd0-4b31-81fd-98d2945b97c7" />
<img width="400" height="568.099" alt="image" src="https://github.com/user-attachments/assets/754de3a4-cd15-41d6-be09-2c1102f4d603" />
<img width="400" height="493.8338" alt="image" src="https://github.com/user-attachments/assets/6a935002-9b08-471c-bcef-5d35291ca784" />
<img width="400" height="483.06878" alt="image" src="https://github.com/user-attachments/assets/e8c231ec-b9d2-42d8-a71d-545973a775b4" />

### Step 7. Repeated Step 4 using Networkwalks website https://networkwalks.com/hash-calculator/ .
<p align="center">
<img width="1920" height="965" alt="NW Hash web" src="https://github.com/user-attachments/assets/f35a00f3-c4ed-451f-861c-c77b678ce328" />
</p>


### Step 8. Copied that hash and pasted it on Networkwalks website https://networkwalks.com/password-cracker/ .
<p align="center">
<img width="1920" height="971" alt="NW PW Cracker" src="https://github.com/user-attachments/assets/844501ef-4046-475a-9430-b8e6e159b72c" />
</p>

### Step 9. Pressed Start Cracking which similar to Johnny of John the Ripper above cracked the password this time without creating the separate text file with hash.
<p align="center">
<img width="1920" height="974" alt="NW PW Cracked" src="https://github.com/user-attachments/assets/ace9fe32-cff6-45ef-9ba3-fe46ad401af6" />
</p>

<img width="756" height="913" alt="image" src="https://github.com/user-attachments/assets/ea22cf0c-530b-4b38-94ee-49965e4d834b" />

## What I Learned

In this project I learned encryption is a two-way function that what is encrypted can be decrypted with the proper key. The proper key can be revealed using tools like Jack the Ripper by providing the tool with the hash of the encrypted file.

* Password cracking involves recovering passwords from stored data or protected files, primarily to evaluate password strength and highlight the risks of weak passwords.
* Common passwords can be easily discovered, emphasizing the necessity for stronger alternative.
* Password protected files store passwords as hashes and recovery involves extracting the hash and using a cracking tool to match it against potential passwords. 

##  Tools & Resources

- **John the Ripper:** [https://www.openwall.com/john/](https://www.openwall.com/john/)
- **Johnny GUI:** [https://virtualbox.org/wiki/Downloads](https://openwall.info/wiki/john/johnny)
  
##  Author
**Rajesh Kadim**\
Cybersecurity Intern B084

LinkedIn: https://www.linkedin.com/in/rajesh-kadim/

##  Project Information
Program Name: Cybersecurity at Networkwalks | **Week:** 03 | Project: Password Cracking with John the Ripper & Networkwalks Tools | **Repository:** GitHub
