# INTRODUCTION
<p>John the Ripper (JTR) is a widely used password recovery and security auditing tool that helps professionals evaluate password strength. Originally developed for Unix systems, it now supports Windows, Linux, and macOS. The tool is capable of cracking various password hash formats and recovering passwords from protected files such as PDF, ZIP, and Microsoft Office documents.</p>

<p>In this lab exercise, I used JTR John and JTR Johnny to recover the password of a password-protected PDF file. Through this activity, I gained practical experience in password cracking techniques and developed a better understanding of the importance of creating strong passwords to safeguard sensitive information.</p>


# Lab setup

I downloaded John The Ripper from the official website <a>https://www.openwall.com/john/</a> and installed it.
<img width="700" height="500" alt="Screenshot 2026-09-24 213333" src="https://github.com/user-attachments/assets/1fb0217e-5a80-4847-a778-2dfde7800f09" />

I extracted the hash using the PDF HASH EXTRACTOR from <a>https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php</a>

<img width="511" height="370" alt="Screenshot 2026-09-24 213502" src="https://github.com/user-attachments/assets/ba7c9b8f-7b2c-4bb7-933c-2acc25492b12" />

I saved the extracted hash in a txt file then attacked it using John The Ripper. 

<img width="874" height="684" alt="image" src="https://github.com/user-attachments/assets/cc0c6a39-3c7f-4592-aeed-8b22a917f1f1" />
The password is now cracked and can be used to open the pdf file.
