# Bruteforce Lab Report

- Q1) How many Audit Failure events are there? (Format: Count of Events)
  - Run the read command along with a grep (filter) to search only for audit failures and then use that output as an input to the word count of lines to show the number of audit failure events in the file

- Q2) What is the username of the local account that is being targeted? (Format: Username)
  - Using the same logic as last time, applying grep with account name shows the username of the local account that is being targeted

- Q3) What is the failure reason related to the Audit Failure logs? (Format: String)
  - Using the same logic as last time, applying grep with failure reason shows the reason related to the Audit Failure Logs

- Q4) What is the Windows Event ID associated with these logon failures? (Format: ID)
  - As per common knowledge, 4625 is often associated with logon failures 

- Q5) What is the source IP conducting this attack? (Format: X.X.X.X)
  - Using the same logic as last time, applying grep with source IP shows the IP conducting this attack

- Q6) What country is this IP address associated with? (Format: Country)
  - Searching the ip address on virustotal shows the country associated with this IP address

- Q7) What is the range of source ports that were used by the attacker to make these login requests? (LowestPort-HighestPort - Ex: 100-541)
  - Using sort on a file with all source ports renders the range of ports used by the attacker
