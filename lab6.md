Lab Number 11-12

Problem:- Create the operator user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator users. Set their passwords as well. Run the usermod -c command to update the comments of the operatori user account. Remove
the operator user from the system.

Solution:

         sudo useradd operator1

         id operator1

         sudo passwd operator1

         sudo useradd operator2
         
         sudo passwd operator2
         
         sudo useradd operator3
         
         sudo passwd operator3

         sudo usermod -c "Consulting Operator" operator1

         getent passwd operator1

         sudo userdel -r operator3

         id operator3

Implementation:-

 sudo useradd operator1

 id operator1
 
 sudo passwd operator1

<img width="935" alt="operator" src="https://github.com/user-attachments/assets/54c0e88b-6302-433c-9c45-e422cefac556" />

sudo useradd operator2
         
sudo passwd operator2
         
sudo useradd operator3
         
sudo passwd operator3

<img width="656" alt="other" src="https://github.com/user-attachments/assets/6ca37f2e-afa3-4794-b83d-431df2e8f356" />

sudo usermod -c "Consulting Operator" operator1

getent passwd operator1

sudo userdel -r operator3

id operator3


<img width="861" alt="del" src="https://github.com/user-attachments/assets/ae0c8728-d309-4312-94c2-d3334eeedb0e" />


