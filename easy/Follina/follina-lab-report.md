# Follina Lab Report

- Q1) What is the SHA1 hash value of the sample? (Format: SHA1Hash)

  Using sha1sum command along with the filename would give the sha1 hash value

- Q2) According to VirusTotal, what is the full filetype of the provided sample? (Format: X X X X)

  Upload the file in virustotal, under details tab is the full filetype

- Q3) Extract the URL that is used within the sample and submit it (Format: https://x.domain.tld/path/to/something)

  On virustotal, under the relations tab is the url used within sample

- Q4) What is the name of the XML file that is storing the extracted URL? (Format: file.name.ext)

  On virustotal, it is under the bundled files section

- Q5) The extracted URL accesses a HTML file that triggers the vulnerability to execute a malicious payload. According to the HTML processing functions, any files with fewer than <Number> bytes would not invoke the payload. Submit the <Number> (Format: Number of Bytes)
  I googled this with "follina vulnerability" and it showed the answer

- Q6) After execution, the sample will try to kill a process if it is already running. What is the name of this process? (Format: filename.ext)
  This was also on Google within the first few results that come up

- Q7) You were asked to write a process-based detection rule using Windows Event ID 4688. What would be the ProcessName and ParentProcessname used in this detection rule? [Hint: OSINT time!] (Format: ProcessName, ParentProcessName)
  The answer to this lied within the Github link which comes after a Google search

- Q8) Submit the MITRE technique ID used by the sample for Execution [Hint: Online sandbox platforms can help!] (Format: TXXXX)
  I checked the MITRE Framework for this question

- Q9) Submit the CVE associated with the vulnerability that is being exploited (Format: CVE-XXXX-XXXXX)
  Available on the virustotal scan front page
