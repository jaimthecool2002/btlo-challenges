# Veriarty Lab Report

- Q1) What is the hash type (-m flag) used by hashcat to crack the password? (Format: Hash Type Number)
  - Since the algorithms used to secure the information is known, i.e., AES and SHA256, it can be seen on the Veracrypt website which hash type can be used by hashcat to crack the password

- Q2) What is the password to unlock the container? (Format: Password)
  - Using hashcat, it can be brute-forced using the wordlist given to find the password for container.vc

- Q3) What is the name of Moriaty's general sending the email? (Format: FirstName)
  - After the initial mounting using the hashcat password, it gives few files which includes a secret.key file. Using that keyfile on the container.vc file reveals another set of files which has a .txt file containing the name of Moriarty's general sending the email

- Q4) Where is the meeting supposed to be taking place? (Format: Place Name, Location Name)
  - Within the second mounting using the keyfile, the place name and location name is given in the image files

- Q5) When is the meeting supposed to be taking place? (Format: 1st February, 12:34)
  - Within the second mounting using the keyfile, the date and time is given in the image files. It is in binary so after conversion is reveals the date and time of the meeting.
