# Password Cracker

This is a simple password cracker in python, using a dictionary attack

How to use:

1. Clone the repo: `git clone https://github.com/EdArdolino/Password-Cracker.git`
2. Open a terminal and navigate to the directory: `cd Password-Cracker`
3. To run the password cracker enter: `python Cracker.py`
4. Example: `'C:\Users\Admin\Documents\Python\Password Cracker' python Cracker.py`
5. You will be prompted to enter an MD5 hash\
	i. I have provided some examples for you to use in the `hashes.txt` file
6. Next, you will be asked to enter the name of the password dictionary file.\
	i. I have provided `passwords.txt` which contains roughly 10 million of the most common passwords
7. Enter `passwords.txt`
8. The program will proceed, you will be notified if the password is found in the file
9. If the password is found, the password will be printed out in plaintext, along with the number of passwords that were analyzed before the true password was found
