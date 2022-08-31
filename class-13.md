# Class 13 Reading notes

# Local storage

1 - It is important and useful to store information locally as it makes the page able to remember and restore the last state it was in after the user input instead of having to refresh every time.

2 - because it is easy for maliciouse coders to get cookies and other localy stored data you shouldn't store anything on local that could contain sensitive information such as passwords.

3 - Unfortunatly you can only store strings in the local storage. There are work arounds however by useing `JSON.stringify()` and `JSON.parse()`