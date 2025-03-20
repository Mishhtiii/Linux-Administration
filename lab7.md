Lab Number 13-14

Problem:- Implement chown, chmod command with their options

Solution: 

          touch testfile.txt

          mkdir testdir

          sudo chown operator1 testfile.txt
          
          sudo chown :consultants testdir
          
          sudo chown -R operator2:developers testdir

          chmod u+x testfile.txt
          
          chmod g-w testdir
          
          chmod 750 testdir
          
          chmod -R 644 testdir

          ls -l testfile.txt
         
          ls -ld testdir


Implementation:-

<img width="962" alt="chown" src="https://github.com/user-attachments/assets/9073fa5d-dc0e-4d18-917e-ef528fd8d208" />


<img width="914" alt="chmod" src="https://github.com/user-attachments/assets/a46916e3-bf6a-4534-94e2-a43ed06be2df" />









