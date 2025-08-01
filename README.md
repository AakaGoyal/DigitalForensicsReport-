<h1>Digital Forensic Findings and Reflective Report  </h1>

<h2>Description</h2>
Creative Visions conducted an in-house digital forensic analysis following the suspicion that employee Matt Smith had downloaded and 
exported confidential client data. The investigation was initiated after the IT department witnessed unusual USB activity, causing 
concern for unauthorized transfer of data. 
 
The overall objective was to determine whether Matt had viewed, transferred, or attempted to conceal confidential information using 
his company-provided laptop and USB drive. Forensic images of the laptop disk (win10.raw) and memory (memory.raw) were acquired 
and hash-verified with FTK Imager (Williams, 2012). The disk image was queried for system items, user data, and registry hives, with 
analysis focused on Matt's profile NTUSER.DAT hive (cvmatt). 
 
The investigation process followed NIST SP 800-86 (NIST, 2006) forensic process: Collection, Examination, Analysis, and Reporting. 
Forensic utilities such as FTK Imager (Carrier, 2005), RegRipper (Carvey, 2018), and Notepad++ were utilized to extract and examine 
file system and registry evidence. Key findings showed that Matt opened and zipped confidential files (aurora.7z) with a USB device 
connected. Although memory examination was not exhaustive due to symbol limitations, registry and file evidence sufficed to show 
the termination of unauthorized handling of data.
<br />


<h2>Tools used in Investigation</h2>

FTK Imager
RegRipper
RegistryExplorer
Notepad++
Volatility 3 (attempted)
Strings64.exe (attempted)
Snipping Tool / Screenshot Utility





<h2>Platform and Environments Used </h2>

- <b>Windows 10</b>
- <b>TryHackMe</b>

Screenshots 
<img width="1012" height="767" alt="image" src="https://github.com/user-attachments/assets/256fa677-06e4-4e79-95c6-58d997811b84" />
<img width="1010" height="764" alt="image" src="https://github.com/user-attachments/assets/e1483d83-8dbc-4dee-b09f-a44a604f7205" />
<img width="1016" height="768" alt="image" src="https://github.com/user-attachments/assets/8b131ad7-68b4-44a1-937a-a74d515936bc" />
<img width="998" height="759" alt="image" src="https://github.com/user-attachments/assets/47a9f62f-fe8b-4738-ad51-05931981dafe" />
<img width="1010" height="768" alt="image" src="https://github.com/user-attachments/assets/36585c8b-7a09-4f66-8ea5-7a6291035b94" />
<img width="1007" height="770" alt="image" src="https://github.com/user-attachments/assets/9e0fec93-b912-4d35-966c-30ccd0f1e8d5" />
<img width="1009" height="773" alt="image" src="https://github.com/user-attachments/assets/51a0cf51-375a-4d61-a03a-97e74e6cd5bd" />
<img width="1015" height="772" alt="image" src="https://github.com/user-attachments/assets/10f8956f-dfe5-4a3e-b61d-26afeb31bdc8" />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
