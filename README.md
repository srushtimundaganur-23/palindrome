# palindrome
palindrome.py 

text = input("Enter a string: ")

normalized = "".join(char.casefold() for char in text if char.isalnum())

if normalized == normalized[::-1]:
    print("It is a palindrome.")
else:
    print("It is not a palindrome.")
    
