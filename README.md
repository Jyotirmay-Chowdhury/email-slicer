# email-slicer
Email slicer

This Python code implements an "email slicer" program that takes an email
address as input, parses it, and then extracts and displays the username,
domain, and extension of the email address. Here's a step-by-step explanation
of the code:-
1) Define the main function:-

● The code starts by defining the main function. This function will handle
the core logic of the program.
2) Print a welcome message:-
This code prints a welcome message to the user, indicating that they are using
an email slicer.


3) Prompt the user for their email address:-
email_input = input("Input your email address: ")
The program uses the input function to prompt the user to input their email
address and stores the input in the email_input variable.


4) Split the email address into parts:
(username, domain) = email_input.split("@")
(domain, extension) = domain.split(".")

● The code uses the split method to break the email address into three
parts: username, domain, and extension.

● First, it splits the email address at the "@" symbol to separate the
username and the domain.

● Then, it splits the domain part at the "." symbol to separate the
domain and extension.


5) Print the parsed components:-
print("Username : ", username)
print("Domain : ", domain)
print("Extension: ", extension)

The program prints out the parsed components of the email address: the
username, domain, and extension.

6) Start an infinite loop:-
while True:
main()

The code enters an infinite loop that repeatedly calls the main function.
This allows the user to continue entering email addresses and getting them sliced
without having to restart the program each time.

So, when you run this program, it will keep asking you to input an email
address, and it will then split and display the username, domain, and
extension of that email address. 

The loop allows you to keep using the
program for multiple email addresses without needing to relaunch it each
time
