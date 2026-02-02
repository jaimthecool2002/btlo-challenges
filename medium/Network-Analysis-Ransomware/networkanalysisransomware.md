# Network Analysis - Ransomware Lab Report

- Q1) What is the operating system of the host from which the network traffic was captured? (Look at Capture File Properties, copy the details exactly)
  - Open the .pcap file in Wireshark and go to Capture File Properties to see the OS of the host

- Q2) What is the full URL from which the ransomware executable was downloaded?
  - Put http as a display filter to see the first packet containing the URL from which the ransomware executable was downloaded

- Q3) Name the ransomware executable file?
  - The name is in the URL of the ransomware

- Q4) What is the MD5 hash of the ransomware?
  - Download the file via export objects and then use md5sum to see the MD5 hash of the ransomware

- Q5) What is the name of the ransomware?
  - Virustotal scan of this ransomware displays the name 

- Q6) What is the encryption algorithm used by the ransomware, according to the ransom note?
  - The ransom note displays the encryption algorithm used by the ransomware

- Q7) What is the domain beginning with ‘d’ that is related to ransomware traffic?
  - Virustotal displays the doman begineering with 'd' that is related to ransomware traffic

- Q8) Decrypt the Tender document and submit the flag
  - Tesladecrypt tools runs and decrypts the .micro file to .pdf file to display the flag
