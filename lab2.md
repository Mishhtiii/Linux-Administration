Lab number 3-4

Problem:- View the gedit man page.
Use the man -k ext4 command to find the command to tune
ext4 file-system parameters.
Brace expansion is used to generate discretionary strings of
characters. Braces contain a comma-separated list of strings,or a sequence expression. The result includes the text that
precedes or follows the brace definition.

Solution: man gedit
          man -k ext4
          man tune2fs
          touch file{A,B,C}.txt
     Creates: fileA.txt  fileB.txt  fileC.txt
          echo file{1..5}.log
          file1.log file2.log file3.log file4.log file5.log
          echo backup-{Jan,Feb,Mar}-2025
          backup-Jan-2025 backup-Feb-2025 backup-Mar-2025

Implementation:-




       
