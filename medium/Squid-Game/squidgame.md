# Squid Game Lab Report

<img width="940" height="507" alt="image" src="https://github.com/user-attachments/assets/75ec8313-291e-4268-a53b-6077602bcb98" />

- Q1) What is the phone number on the invitation card in Squid Game? (Research this online!)
  - A simple Google search will reveal the answer for this question

<img width="940" height="499" alt="image" src="https://github.com/user-attachments/assets/b8efe492-e8b8-49be-9c5f-c56fde9c72a4" />

- Q2) Can you extract something from the invitation card file? What is the name of the file?
  - Using steghide on the current image, after execution another image gets saved in the current working directory

- Q3) What hint text can be discovered in the final file?
  - Using stegsolve on the second image, it reveals in the gray bits section what the hint is

<img width="940" height="504" alt="image" src="https://github.com/user-attachments/assets/9838c7ea-5ab0-4cf5-8edd-54fa72b17baa" />
<img width="940" height="423" alt="image" src="https://github.com/user-attachments/assets/e629dea9-ec59-4b09-a39a-e692c12a2523" />

- Q4) What is the final flag?
  -  Upload the file on pixspy and see the teal colored pixels. Click on each pixel and copy paste its red value from RGB onto dcode.fr/en. Select ASCII to then reveal the flag.
