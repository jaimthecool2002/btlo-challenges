# Follina Lab Report

<img width="747" height="163" alt="image" src="https://github.com/user-attachments/assets/3dd82ee6-1ba6-455f-b187-62e584feefc9" />

- Q1) What is the SHA1 hash value of the sample? (Format: SHA1Hash)
  - Using sha1sum command along with the filename would give the sha1 hash value

<img width="940" height="488" alt="image" src="https://github.com/user-attachments/assets/7c3abcb4-10d0-4718-add5-96de222c4bb1" />

<img width="940" height="466" alt="image" src="https://github.com/user-attachments/assets/9519c575-67ba-4f66-96ba-caac6a553549" />

- Q2) According to VirusTotal, what is the full filetype of the provided sample? (Format: X X X X)
  - Upload the file in virustotal, under details tab is the full filetype

<img width="940" height="469" alt="image" src="https://github.com/user-attachments/assets/b132e8f2-4e89-4c81-912e-03c1baf303a9" />

- Q3) Extract the URL that is used within the sample and submit it (Format: https://x.domain.tld/path/to/something)
  - On virustotal, under the relations tab is the url used within sample

<img width="940" height="419" alt="image" src="https://github.com/user-attachments/assets/67422c41-02e9-4381-a3c4-3354d8b6691f" />

- Q4) What is the name of the XML file that is storing the extracted URL? (Format: file.name.ext)
  - On virustotal, it is under the bundled files section

<img width="940" height="458" alt="image" src="https://github.com/user-attachments/assets/d5c73d26-3975-419d-b2b4-75898fd17b81" />

- Q5) The extracted URL accesses a HTML file that triggers the vulnerability to execute a malicious payload. According to the HTML processing functions, any files with fewer than <Number> bytes would not invoke the payload. Submit the <Number> (Format: Number of Bytes)
  - I googled this with "follina vulnerability" and it showed the answer

<img width="940" height="432" alt="image" src="https://github.com/user-attachments/assets/84e81f16-4bdd-4ab7-b096-85110ad63ac6" />

- Q6) After execution, the sample will try to kill a process if it is already running. What is the name of this process? (Format: filename.ext)
  - This was also on Google within the first few results that come up

<img width="940" height="355" alt="image" src="https://github.com/user-attachments/assets/e49638f8-72fb-42ed-a063-c7fc55cff534" />

- Q7) You were asked to write a process-based detection rule using Windows Event ID 4688. What would be the ProcessName and ParentProcessname used in this detection rule? [Hint: OSINT time!] (Format: ProcessName, ParentProcessName)
  - The answer to this lied within the Github link which comes after a Google search

<img width="940" height="472" alt="image" src="https://github.com/user-attachments/assets/d4b1333f-7a9b-4377-bc0b-5fa89f59538c" />

- Q8) Submit the MITRE technique ID used by the sample for Execution [Hint: Online sandbox platforms can help!] (Format: TXXXX)
  - I checked the MITRE Framework for this question

<img width="940" height="488" alt="image" src="https://github.com/user-attachments/assets/d380c37d-1336-4cd3-a8e0-2771ea7663e3" />

- Q9) Submit the CVE associated with the vulnerability that is being exploited (Format: CVE-XXXX-XXXXX)
  - Available on the virustotal scan front page
