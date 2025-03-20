Lab NUmber 15-16

Problem:- Write shell scripts to print system information.
Write shell script to perform basic mathematical calculation.
Use redirection operators to store the output of commands.

Solution: 

          nano system_info.sh

          chmod +x system_info.sh

          ./system_info.sh

          nano calculate.sh

          chmod +x calculate.sh

          ./calculate.sh

          ls -l > file_list.txt

          uname -a > kernel_info.txt

          whoami >> user_info.txt

          ls non_existent_file 2> error_log.txt

          find / -name "some_file" 2>&1 > find_output.txt

Implementation:

nano system_info.sh

<img width="867" alt="script" src="https://github.com/user-attachments/assets/2e90de87-5612-49f9-9af9-2d7912eec4fa" />


chmod +x system_info.sh

./system_info.sh

<img width="820" alt="system" src="https://github.com/user-attachments/assets/a9d430c3-f5a3-4d85-b53c-42ced307c6b3" />


nano calculate.sh


<img width="822" alt="calculate" src="https://github.com/user-attachments/assets/8f0f8e39-ebd5-48bf-8ef7-cdbd93bb0226" />


 chmod +x calculate.sh

 ./calculate.sh

 ls -l > file_list.txt

 uname -a > kernel_info.txt

 whoami >> user_info.txt

 ls non_existent_file 2> error_log.txt

 find / -name "some_file" 2>&1 > find_output.txt

 <img width="853" alt="Sfind" src="https://github.com/user-attachments/assets/227375af-515a-448b-a1b3-4b8ad5e24818" />

 










