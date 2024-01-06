- Contacts.py is a simple application made using Python which is capable of storing contact information.

- This application can fo the following tasks:
 1. Add a new Contact i.e Name and Contact Number
 2. Add additional contact information including E-Mail and address.
 3. Remove a Contacts from the available list of contacts.
 4. Update a contact and its information like adding a replacing a old number with a new number.
 5. Find the rrquired contact details providing either Name or Number.
 6. Viewing all available details of a contact.

- All the information is stired in a book.csv file.
It consists of rows with four columns for Name, Number, Email and Address.

This application is made using - Python standard library "TKunter".
It is a python Graphical User Interface (GUI) library.
Also 'csv' package is imported to read and write book.csv file 

- It basic GUI consisys of a Listbox in which available contact name and their number  are displayed. A scrollbar a right of the Listbox.
At the bottom. group of five buttons which are Add, View, Update, Remove and Find.

Clicking on Add, Update, and Find buttons opens up a new window in which the the necessary actions can be performed. 

View opens up a messagbix displaying contact information.

Remove button asks for confirmation to delete the contact. If Yes, the contact along with its details are removed from the book.csv file.
