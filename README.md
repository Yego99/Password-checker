# Password-checker
This code taps in to the API of pwned passwords (a website that has a leaked password database) and checks to see if the password you give it via the command line has ever been leaked or hacked. To do this in the most secure fashion; how the code  works is it hashes the password you give it and breaks the hashed password into 2 parts: the first 5 characters and the rest of the hash. Next the first 5 characters of the hashed password are sent to the website and all hashes that match are returned. Then the program compares the tails and if any match the tail of your hashed password then it prints that out along with the count of how many times that password has been leaked

To use this program:
1)	Open the command prompt and run the code followed by the password you want to check. 
