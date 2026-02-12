# Reverse Engineering Lab Report

<img width="940" height="753" alt="image" src="https://github.com/user-attachments/assets/71b18860-ef25-4c4a-894e-a01dcf33d35b" />

- Q1) What is the language the program is written?
  - Using detect-it-easy, it will on loading show the language the program was written in

<img width="940" height="193" alt="image" src="https://github.com/user-attachments/assets/27f789fc-8c43-4a1e-b84a-cf0c289bbd5b" />

- Q2) What is the build id?
  - Using grep after strings on the .exe file will reveal the build id

<img width="653" height="363" alt="image" src="https://github.com/user-attachments/assets/e1d963e1-ee30-4a97-b735-c29ed1075eaa" />

- Q3) What is the dependency package the sample uses for invoking windows APIs
  - Running the .exe file on IDA will show the dependency package being used

<img width="940" height="334" alt="image" src="https://github.com/user-attachments/assets/48785f7c-ad80-46ac-b0f7-d0fce66a9ca5" />

- Q4) What is the victim process? (Hint: 32bit)
  - Filtering the strings with a .exe filter shows a reference to another file which is the victim process

<img width="940" height="178" alt="image" src="https://github.com/user-attachments/assets/cad3c23d-b1a7-469a-a5db-4c112b20f747" />

- Q5) What is the process invoked from the shellcode?
  - Filtering the strings with a shell filter shows a powershell command of a process invoked

- Q6) What is the name of the created file?
  - Using the encrypted code and converting it on Cyberchef reveals the name of the file created

- Q7) What is the name of the actual tool executed?
  - Using the encrypted code and converting it on Cyberchef reveals the name of the actual tool executed
