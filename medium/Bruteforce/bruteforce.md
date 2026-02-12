# Bruteforce Lab Report

<img width="940" height="637" alt="image" src="https://github.com/user-attachments/assets/e7c11bf4-13f5-4eec-ac75-419fca71ab5b" />

- Q1) How many Audit Failure events are there? (Format: Count of Events)
  - Run the read command along with a grep (filter) to search only for audit failures and then use that output as an input to the word count of lines to show the number of audit failure events in the file

<img width="940" height="601" alt="image" src="https://github.com/user-attachments/assets/17a5b4c8-5ee0-4374-b312-ae63d00cf794" />

- Q2) What is the username of the local account that is being targeted? (Format: Username)
  - Using the same logic as last time, applying grep with account name shows the username of the local account that is being targeted

<img width="940" height="1404" alt="image" src="https://github.com/user-attachments/assets/c13f47c8-717e-4501-b300-267ab1e2baa3" />

- Q3) What is the failure reason related to the Audit Failure logs? (Format: String)
  - Using the same logic as last time, applying grep with failure reason shows the reason related to the Audit Failure Logs

<img width="940" height="793" alt="image" src="https://github.com/user-attachments/assets/a13ed44f-0fb7-48ba-a613-11413d9fdc9f" />

- Q4) What is the Windows Event ID associated with these logon failures? (Format: ID)
  - As per common knowledge, 4625 is often associated with logon failures 

- Q5) What is the source IP conducting this attack? (Format: X.X.X.X)
  - Using the same logic as last time, applying grep with source IP shows the IP conducting this attack

<img width="940" height="364" alt="image" src="https://github.com/user-attachments/assets/a3721e97-f1e6-4d95-bb01-0ad5b1eccd5e" />

- Q6) What country is this IP address associated with? (Format: Country)
  - Searching the ip address on virustotal shows the country associated with this IP address

<img width="870" height="655" alt="image" src="https://github.com/user-attachments/assets/90d6ec40-a44f-4871-867d-5f3dd29ba33f" />

- Q7) What is the range of source ports that were used by the attacker to make these login requests? (LowestPort-HighestPort - Ex: 100-541)
  - Using sort on a file with all source ports renders the range of ports used by the attacker
