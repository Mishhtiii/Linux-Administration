Lab Number 7-8

Problem:-Create the /home/consultants directory.
Add write permission to the consultants group. Use the
symbolic method for setting the appropriate permissions.
Forbid others from accessing files in
the /home/consultants directory. Use the octal method for
setting the appropriate permissions.
Change the default umask for the operator1 user. The new
umask prohibits all access for users that are not in their
group. Confirm that the umask is changed.

Solution:

sudo mkdir /home/consultants

sudo groupadd consultants

sudo chown :consultants /home/consultants

sudo chmod g+w /home/consultants

sudo chmod 770 /home/consultants

sudo useradd operator1

sudo nano /home/operator1/.bashrc

sudo su - operator1

umask

touch testfile

ls -l testfile

exit

Implementation:-

<img width="963" alt="mkdir" src="https://github.com/user-attachments/assets/6c6a5b75-31c0-4b21-adb9-0cc56e6fb8e3" />


