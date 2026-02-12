# Injection Series 4 Lab Report

<img width="940" height="483" alt="image" src="https://github.com/user-attachments/assets/da2e1775-1c00-4a29-858e-2208ab73a715" />

- Q1) What is the process that would be first spawned by the sample? And what is the API used? (Format: Format: process, APICall)
  - Running the file in IDA environment showed the process and API used

<img width="940" height="511" alt="image" src="https://github.com/user-attachments/assets/b323205d-403f-45e1-9857-2f33dfc3c46e" />

- Q2) The value 4 has been pushed as a parameter to this API, what does that denote? (Format: FLAG)
  - There I found the value 4 being allocated as a parameter which on msdn website, correlated to a flag

<img width="940" height="491" alt="image" src="https://github.com/user-attachments/assets/992c1f24-ba86-4f8f-9df9-e4905df6b0e3" />

- Q3) What is the domain that the malware tries to connect? (Format: domain.tld)
  - A powershell command contains a random string. Deecoding the string with base64 from Cyberchef reveals the answer

<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/e852bc87-4be2-412b-9e80-4589617b6ab8" />

- Q4) What is the cmdlet used to download the file and what is the path of the file stored? (Format: CMDLET, path)
  - In the previous answer, it is mentioned what cmdlet and path was used

<img width="940" height="269" alt="image" src="https://github.com/user-attachments/assets/3c0ead43-5af4-48ee-9b3b-7ed327b68e72" />

- Q5) Just after the file download instructions, a function from ntdll has been loaded and invoked by the sample. What is the function name? (Format: Function)
  - In IDA, a function is invoked just after the file downloads. The function is from ntdll which is the answer

<img width="940" height="480" alt="image" src="https://github.com/user-attachments/assets/a0b95a05-0df8-47dd-8696-5858bb631957" />

- Q6) After the allocation of memory and writing the date into the allocated memory. What are the 2 APIs used to update the entry point and resume the thread? (Format: API, API)
  - Towards the end, the two APIs are mentioned which update the entry points and resume the thread

<img width="940" height="462" alt="image" src="https://github.com/user-attachments/assets/cb5a980a-bc13-4f56-910b-cac1c9fee147" />

- Q7) What is the MITRE ID for this technique implemented in this sample? (Format: TXXXX.XXX)
  - On Mitre website, certain keywords like process injection and executable command will reveal this answer
