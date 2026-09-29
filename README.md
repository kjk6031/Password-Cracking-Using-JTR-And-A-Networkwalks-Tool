# Password Recovery and Hash Cracking Lab
## Introduction

Password cracking is the process of recovering a password from a protected file or stored data. Security professionals use password-cracking techniques to evaluate password strength, identify weak credentials, and demonstrate potential security risks associated with poor password management.

In this lab, I explored the process of password recovery using two different approaches:

John the Ripper (JTR) for offline password recovery.
Networkwalks online tools for browser-based hash extraction and password recovery.

The exercise involved extracting a hash from a password-protected PDF file, using password recovery tools to identify the password, and successfully accessing the protected document. This hands-on activity provided practical experience with password auditing techniques and reinforced the importance of using strong passwords to protect sensitive information.

## Objectives
Understand how password-protected PDF files store password information.
Learn the process of extracting password hashes from secured documents.
Gain practical experience with password recovery tools.
Observe how weak passwords can be recovered through dictionary-based attacks.
Appreciate the importance of strong password policies and secure password management.

## Lab Environment
### Tools Used
<strong>John the Ripper Lab</strong>
John the Ripper (JTR)
Website: https://www.openwall.com/john
PDF Hash Extractor
Website: https://://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

<strong>Networkwalks Online Lab</strong>
Hash Calculator
Website: https://networkwalks.com/hash-calculator/
Password Cracker Through Dictionary Attacks
Website: https://networkwalks.com/password-cracker/


## Method 1: Password Recovery Using John the Ripper

<b><i>Step 1: Install John the Ripper.</i></b>
I downloaded and installed John the Ripper from the official Openwall website.

<b><i>Step 2: Extract the PDF Hash.</i></b>
Next, I used the PDF Hash Extractor to obtain the password hash from the protected PDF file.
<img width="511" height="370" alt="Screenshot 2026-09-24 213502" src="https://github.com/user-attachments/assets/44b42bd6-aa96-4cf1-97f5-250413fe6d73" />

<b><i>Step 3: Crack the Password.</i></b>
The extracted hash was saved to a text file and processed using John the Ripper. The tool performed a password-recovery attack and successfully identified the correct password.
<img width="874" height="684" alt="Screenshot 2026-09-28 233814" src="https://github.com/user-attachments/assets/e58cd405-c92e-44c6-9e2d-cfa3065ec452" />

<b><i>Step 4: Access the Protected File.</i></b>
After recovering the password, I unlocked the PDF document and successfully retrieved the embedded flag:
<img width="800" height="912" alt="image" src="https://github.com/user-attachments/assets/5c8c0c49-9111-4aa1-a731-9c288c51e097" />


nw{cybersecurity_flag_captured_2608}

## Method 2: Password Recovery Using Networkwalks Tools
<b><i>Step 1: Generate the File Hash.</i></b>
I visited the Networkwalks Hash Calculator and generated the hash of the password-protected PDF file.
<img width="868" height="704" alt="image" src="https://github.com/user-attachments/assets/aa039822-d8e7-40d3-94bb-50886372e68b" />


<b><i>Step 2: Launch the Password Cracker.</i></b>
After obtaining the hash value, I opened the Networkwalks Password Cracker tool.

<b><i>Step 3: Recover the Password.</i></b>
The generated hash was pasted into the password-cracking tool and the recovery process was started. The tool tested multiple password candidates until a matching password was found.
<img width="885" height="922" alt="image" src="https://github.com/user-attachments/assets/481cffa3-dd4d-4d08-b744-c4c7b7e3127e" />


<b><i>Step 4: Open the PDF File.</i></b>
Once the password was recovered, I used it to unlock the PDF document and verify its contents.
<img width="801" height="896" alt="image" src="https://github.com/user-attachments/assets/7ac64970-3344-480a-8b40-ff5cc9bbeebc" />


### Key Concepts Learned

#### Password Hashing
A <strong>password hash</strong> is a one-way cryptographic representation of a password. Instead of storing actual passwords, systems generally store hashes, making direct password recovery difficult.

#### Dictionary Attacks
A <strong>dictionary attack</strong> attempts to recover passwords by comparing password hashes against hashes generated from a predefined list of commonly used passwords.

#### Password Recovery
<strong>Password recovery</strong> tools automate the process of testing password candidates until a match is found, allowing authorized users and security professionals to regain access to protected resources.

#### PDF Security
<strong>PDF files</strong> can be protected with passwords to prevent unauthorized access. However, weak passwords remain vulnerable to password-recovery techniques.

## Lessons Learned
Through this lab, I learned several important cybersecurity concepts:

Passwords are not typically stored directly; they are stored as hashes.
Weak passwords can often be recovered within a short time using automated tools.
Dictionary attacks remain highly effective against common and predictable passwords.
Password complexity significantly increases resistance against password-recovery attempts.
Hash extraction is an essential step when performing password auditing on protected files.
Different tools can achieve the same objective through different approaches, such as offline recovery with John the Ripper and browser-based recovery using Networkwalks.
Security testing helps organizations identify weaknesses before attackers can exploit them.
Strong passwords should combine uppercase letters, lowercase letters, numbers, and special characters.
Password managers can help users generate and manage strong, unique passwords.
Multi-factor authentication (MFA) adds an extra layer of protection even if a password is compromised.

## Conclusion
This lab successfully demonstrated the process of extracting a password hash from a protected PDF file and recovering the password using both John the Ripper and Networkwalks tools. The exercise provided practical exposure to password auditing concepts, highlighted the risks associated with weak passwords, and reinforced the importance of implementing strong authentication practices to protect sensitive information.


# Author

**Kwabeng Jeffrey Kingsley**\
Cybersecurity Student B083

LinkedIn: www.linkedin.com/in/jeffery-kwabeng-aa53a82b5

## Project Information

**Program Name: **Cybersecurity at Networkwalks | **Week: **03 | **Project: **Password Cracking Using JTR And A Networkwalks Tool | **Repository: **https://github.com/kjk6031/Password-Cracking-Using-JTR-And-A-Networkwalks-Tool


