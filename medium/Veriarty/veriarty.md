# Veriarty Lab Report

<img width="940" height="282" alt="image" src="https://github.com/user-attachments/assets/d05aea18-7e57-40f3-8115-0303ff363252" />

- Q1) What is the hash type (-m flag) used by hashcat to crack the password? (Format: Hash Type Number)
  - Since the algorithms used to secure the information is known, i.e., AES and SHA256, it can be seen on the Veracrypt website which hash type can be used by hashcat to crack the password

<img width="940" height="681" alt="image" src="https://github.com/user-attachments/assets/e8f63629-c683-438a-8975-bd51d13799c9" />
<img width="905" height="144" alt="image" src="https://github.com/user-attachments/assets/69f3395f-f54d-4fd7-bfd5-d847cb6379e0" />

- Q2) What is the password to unlock the container? (Format: Password)
  - Using hashcat, it can be brute-forced using the wordlist given to find the password for container.vc

<img width="940" height="190" alt="image" src="https://github.com/user-attachments/assets/1acd1987-1aa9-40e3-9cd3-536997d86b84" />

- Q3) What is the name of Moriaty's general sending the email? (Format: FirstName)
  - After the initial mounting using the hashcat password, it gives few files which includes a secret.key file. Using that keyfile on the container.vc file reveals another set of files which has a .txt file containing the name of Moriarty's general sending the email

<img width="940" height="1089" alt="image" src="https://github.com/user-attachments/assets/c9d02fce-5089-4e67-a7e9-48dae68173da" />
<img width="940" height="627" alt="image" src="https://github.com/user-attachments/assets/e4019a5e-726e-46b2-8d31-0ed33fe66305" />

- Q4) Where is the meeting supposed to be taking place? (Format: Place Name, Location Name)
  - Within the second mounting using the keyfile, the place name and location name is given in the image files

<img width="940" height="1146" alt="image" src="https://github.com/user-attachments/assets/3941472f-f5e1-4748-bf25-4aa055577929" />

- Q5) When is the meeting supposed to be taking place? (Format: 1st February, 12:34)
  - Within the second mounting using the keyfile, the date and time is given in the image files. It is in binary so after conversion is reveals the date and time of the meeting.
