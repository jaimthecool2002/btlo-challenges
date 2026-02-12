# Network Analysis - Ransomware Lab Report

<img width="940" height="505" alt="image" src="https://github.com/user-attachments/assets/719f679e-27e4-462d-8134-a0c01bbf45ab" />

- Q1) What is the operating system of the host from which the network traffic was captured? (Look at Capture File Properties, copy the details exactly)
  - Open the .pcap file in Wireshark and go to Capture File Properties to see the OS of the host

<img width="940" height="509" alt="image" src="https://github.com/user-attachments/assets/bc018d52-7fe1-4496-94f9-1c22b2e7891d" />

- Q2) What is the full URL from which the ransomware executable was downloaded?
  - Put http as a display filter to see the first packet containing the URL from which the ransomware executable was downloaded

<img width="940" height="498" alt="image" src="https://github.com/user-attachments/assets/ac46c10c-e2c9-45c6-be79-3c4e96956ef4" />

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
