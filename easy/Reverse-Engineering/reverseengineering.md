# Reverse Engineering Lab Report

- Q1) What is the language the program is written?
  - Using detect-it-easy, it will on loading show the language the program was written in

- Q2) What is the build id?
  - Using grep after strings on the .exe file will reveal the build id

- Q3) What is the dependency package the sample uses for invoking windows APIs
  - Running the .exe file on IDA will show the dependency package being used

- Q4) What is the victim process? (Hint: 32bit)
  - Filtering the strings with a .exe filter shows a reference to another file which is the victim process

- Q5) What is the process invoked from the shellcode?
  - Filtering the strings with a shell filter shows a powershell command of a process invoked

- Q6) What is the name of the created file?
  - Using the encrypted code and converting it on Cyberchef reveals the name of the file created

- Q7) What is the name of the actual tool executed?
  - Using the encrypted code and converting it on Cyberchef reveals the name of the actual tool executed
