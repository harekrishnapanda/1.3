# 1.3
#Assignment 3
'''
A Python program to accept the user's first and last name and then getting them
printed in the the reverse order with a space between first name and last name.
'''

First_Name = input('what is your First Name: ')
Last_Name = input('what is your Last Name: ')
name = (First_Name + " " + Last_Name)
rev =(Last_Name + " " + First_Name)
print(rev)
print(name[::-1])
