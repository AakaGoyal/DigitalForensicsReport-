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


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
