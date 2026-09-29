## INTRODUCTION
I learned that password cracking is the process of recovering a password from a protected file or stored data. Security professionals often use password-cracking techniques to evaluate password strength and demonstrate the risks associated with weak passwords. Through this process, I can see how short or commonly used passwords can be discovered quickly, emphasizing the importance of creating strong and secure passwords.

I also learned that many file types, such as PDF, ZIP, and Microsoft Office documents, can be protected with passwords. When a file is secured, its password is stored in the form of a hash, which is a scrambled representation of the original password. To recover the password, I first need to extract the hash from the protected file and then use a password-cracking tool to test possible passwords until a match is found.

In this lab, I used two free online tools provided by Networkwalks. First, I used the Hash Calculator to extract the hash from a password-protected PDF file. Next, I used the Password Cracker to recover the original password from the extracted hash. Since both tools run directly in a web browser, I was able to complete the exercise without installing any additional software.

This lab helped me understand the password-cracking process step by step and showed me why strong passwords are essential for protecting sensitive information and preventing unauthorized access.

# What I did
<p>I first visited the Networkwalks <a href="https://networkwalks.com/hash-calculator/">hash calculator</a> and generated the hash value of the PDF file.</p>
 
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/31dce76b-1464-4ec3-9631-e2191a7d623e" />
 
<p>After obtaining the hash, I navigated to the Networkwalks <a href="https://networkwalks.com/password-cracker/">Password Cracker</a> tool in my browser.</p>
 
<img width="874" height="533" alt="image" src="https://github.com/user-attachments/assets/9d143421-0785-4937-9b40-cdc85322b56a" />
 
<p>I then copied the generated hash and pasted it into the password-cracking tool before starting the password recovery process. The application tested multiple password combinations until it identified the password that matched the supplied hash value.</p>
 
<img width="885" height="922" alt="image" src="https://github.com/user-attachments/assets/9990c4c1-6c1b-4fd0-81dd-e0f821a967cd" />
 
<p>After recovering the password, I used it to open the protected PDF document. The image below shows the contents of the PDF file after it was successfully accessed.</p>
 
<img width="801" height="896" alt="image" src="https://github.com/user-attachments/assets/481736d4-509e-481f-8fd4-5e3bdb150852" />

