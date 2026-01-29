# Follina Lab Report

- Q1) What is the SHA1 hash value of the sample? (Format: SHA1Hash)
  06727ffda60359236a8029e0b3e8a0fd11c23313

- Q2) According to VirusTotal, what is the full filetype of the provided sample? (Format: X X X X)
  Office Open XML Document

- Q3) Extract the URL that is used within the sample and submit it (Format: https://x.domain.tld/path/to/something)
   	https://www.xmlformats.com/office/word/2022/wordprocessingDrawing/RDF842l.html 

- Q4) What is the name of the XML file that is storing the extracted URL? (Format: file.name.ext)
  document.xml.rels

- Q5) The extracted URL accesses a HTML file that triggers the vulnerability to execute a malicious payload. According to the HTML processing functions, any files with fewer than <Number> bytes would not invoke the payload. Submit the <Number> (Format: Number of Bytes)
  4096

- Q6) After execution, the sample will try to kill a process if it is already running. What is the name of this process? (Format: filename.ext)
  msdt.exe

- Q7) You were asked to write a process-based detection rule using Windows Event ID 4688. What would be the ProcessName and ParentProcessname used in this detection rule? [Hint: OSINT time!] (Format: ProcessName, ParentProcessName)
  msdt.exe, winword.exe

- Q8) Submit the MITRE technique ID used by the sample for Execution [Hint: Online sandbox platforms can help!] (Format: TXXXX)
  T1059

- Q9) Submit the CVE associated with the vulnerability that is being exploited (Format: CVE-XXXX-XXXXX)
  CVE-2022-30190
