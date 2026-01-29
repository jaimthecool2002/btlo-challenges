# Injection Series 4 Lab Report

- Q1) What is the process that would be first spawned by the sample? And what is the API used? (Format: Format: process, APICall)
  - Running the file in IDA environment showed the process and API used


- Q2) The value 4 has been pushed as a parameter to this API, what does that denote? (Format: FLAG)
  - There I found the value 4 being allocated as a parameter which on msdn website, correlated to a flag


- Q3) What is the domain that the malware tries to connect? (Format: domain.tld)
  - A powershell command contains a random string. Deecoding the string with base64 from Cyberchef reveals the answer


- Q4) What is the cmdlet used to download the file and what is the path of the file stored? (Format: CMDLET, path)
  - In the previous answer, it is mentioned what cmdlet and path was used


- Q5) Just after the file download instructions, a function from ntdll has been loaded and invoked by the sample. What is the function name? (Format: Function)
  - In IDA, a function is invoked just after the file downloads. The function is from ntdll which is the answer

- Q6) After the allocation of memory and writing the date into the allocated memory. What are the 2 APIs used to update the entry point and resume the thread? (Format: API, API)
  - Towards the end, the two APIs are mentioned which update the entry points and resume the thread

- Q7) What is the MITRE ID for this technique implemented in this sample? (Format: TXXXX.XXX)
  - On Mitre website, certain keywords like process injection and executable command will reveal this answer
