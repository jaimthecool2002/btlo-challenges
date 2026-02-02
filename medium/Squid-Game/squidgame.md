# Squid Game Lab Report

- Q1) What is the phone number on the invitation card in Squid Game? (Research this online!)
  - A simple Google search will reveal the answer for this question

- Q2) Can you extract something from the invitation card file? What is the name of the file?
  - Using steghide on the current image, after execution another image gets saved in the current working directory

- Q3) What hint text can be discovered in the final file?
  - Using stegsolve on the second image, it reveals in the gray bits section what the hint is

- Q4) What is the final flag?
  -  Upload the file on pixspy and see the teal colored pixels. Click on each pixel and copy paste its red value from RGB onto dcode.fr/en. Select ASCII to then reveal the flag.
