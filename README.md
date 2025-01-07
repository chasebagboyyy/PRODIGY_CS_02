# PRODIGY_CS_02
# CAESAR CIPHER PROGRAM 

Hi there! This is a simple Python program I created as part of an assignment to demonstrate how the Caesar Cipher works. The Caesar Cipher is one of the oldest and simplest encryption methods, where you shift letters in the alphabet by a certain number of steps (called the shift value).

This program allows you to:

	•	Encrypt a message by shifting its letters forward.
 
•	Decrypt a message by shifting its letters backward to its original form.


**How It Works**
When you run the program:
	1.	It asks if you want to **encrypt** or **decrypt** a message.
 
	2.	You enter the message you want to process.
 
	3.	You provide a shift value (this is just a number that determines how far each letter is shifted).
 
	4.	The program then processes your input and gives you the result.

**Steps to Run the Program**
Here’s how you can use it:

	1.	Make sure you have Python 3 installed on your computer.
 
	2.	Open the program in your favorite editor (I used VS Code for this).
 
	3.	Run the program by typing:
 
python caesar_cipher.py

	4.	Follow the prompts:
 
	•	Choose whether you want to **encrypt** or **decrypt**.
 
	•	Type in your message.
 
	•	Enter the shift value (e.g., 3 or 5).
 
	5.	The program will print the result for you.

**Example**
Let’s say you want to encrypt the message Hello World with a shift of 3:

	•	Input:
 
Message: Hello World
Shift: 3

	•	Output:
 
Khoor Zruog

If you want to decrypt Khoor Zruog back to its original message:

	•	Input:
 
Message: Khoor Zruog
Shift: 3

	•	Output:
 
Hello World

**Why I Made This**

I worked on this project to better understand how simple encryption works and to practice Python programming. It’s a fun way to see how cryptography started and how even basic ciphers can make text unreadable without the right key.

**Things to Note**

	•	If you enter a non-integer for the shift value, the program will remind you to try again with a valid number.
 
	•	The program keeps non-alphabetic characters (like punctuation, spaces, and numbers) as they are, so your message structure doesn’t change.

