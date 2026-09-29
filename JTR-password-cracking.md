# INTRODUCTION
<p>John the Ripper (JTR) is a widely used password recovery and security auditing tool that helps professionals evaluate password strength. Originally developed for Unix systems, it now supports Windows, Linux, and macOS. The tool is capable of cracking various password hash formats and recovering passwords from protected files such as PDF, ZIP, and Microsoft Office documents.</p>

<p>In this lab exercise, I used JTR John and JTR Johnny to recover the password of a password-protected PDF file. Through this activity, I gained practical experience in password cracking techniques and developed a better understanding of the importance of creating strong passwords to safeguard sensitive information.</p>


# Lab setup

<p>
I downloaded <strong>John the Ripper</strong> from the official website
www.openwall.com/john and successfully installed it on my system.
</p>
 
<img width="868" height="681" alt="Screenshot 2026-09-24 213333" src="https://github.com/user-attachments/assets/59700944-3e47-434d-bcd9-44f0c288f41f" />

 
<p>
Next, I extracted the PDF hash using the <strong>PDF Hash Extractor</strong> available at https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php. The tool generated the hash value required for the password-cracking process.
</p>
 
<img width="511" height="370" alt="Screenshot 2026-09-24 213502"
src="https://github.com/user-attachments/assets/ba7c9b8f-7b2c-4bb7-933c-2acc25492b12" />
 
<p>
Afterward, I saved the extracted hash in a text file and used John the Ripper to perform a password-cracking attack against the protected PDF document. The tool successfully recovered the correct password.
</p>
 
<img width="874" height="684" alt="John the Ripper Password Cracking Process"
src="https://github.com/user-attachments/assets/cc0c6a39-3c7f-4592-aeed-8b22a917f1f1" />
 
<p>
Once the password had been recovered, it was used to unlock and open the PDF file. Upon accessing the document, the following flag was revealed:
</p>
 
<p>
<strong>nw{cybersecurity_flag_captured_2608}</strong>
</p>
 
<img width="800" height="912" alt="Retrieved Flag"
src="https://github.com/user-attachments/assets/1df7044c-4fe8-4e3c-89a8-dcc6e80d1e63" />
 
<p>
This exercise demonstrates the process of extracting a PDF hash, saving it for analysis, using John the Ripper to recover the password, and successfully accessing the protected content to obtain the flag.
</p>

# Tools Used
<ol>
  <li>PDF hash Extractor - <a href="https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php">Online Hash Crack</a></li>
  <li>John The Ripper (JTR) - <a href="www.openwall.com/john">Openwall</a></li>
</ol>
