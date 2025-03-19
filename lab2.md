Lab Number 3-4

Problem:- View the gedit man page.
Use the man -k ext4 command to find the command to tune
ext4 file-system parameters.
Brace expansion is used to generate discretionary strings of
characters. Braces contain a comma-separated list of strings,or a sequence expression. The result includes the text that
precedes or follows the brace definition.

Solution: 

          man gedit

          man -k ext4
          
          man tune2fs
          
          touch file{A,B,C}.txt
          
     Creates: fileA.txt  fileB.txt  fileC.txt
     
          echo file{1..5}.log
          
          file1.log file2.log file3.log file4.log file5.log
          
          echo backup-{Jan,Feb,Mar}-2025
          
          backup-Jan-2025 backup-Feb-2025 backup-Mar-2025

Implementation:-

man gedit

<img width="936" alt="gedit" src="https://github.com/user-attachments/assets/27bcd885-80d2-4668-9568-10d4d7d6629e" />

man -k ext4
 
<img width="988" alt="fs" src="https://github.com/user-attachments/assets/4370d72d-4625-4679-bf00-7b3879122c5c" />

man tune2fs

<img width="955" alt="tune" src="https://github.com/user-attachments/assets/6c3e51b1-6ff1-421e-b8df-ffa529f86bc0" />

<img width="964" alt="echo" src="https://github.com/user-attachments/assets/89bbadba-cec9-48b2-b213-b4997e66a741" />




 






       
