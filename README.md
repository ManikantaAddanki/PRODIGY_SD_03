# PRODIGY_SD_03

Develop a program that allows users to store and manage contact information. The program should provide options to add a new contact by entering their name, phone number, and email address. It should also allow users to view their contact list, edit existing contacts, and delete contacts if needed. The program should store the contacts in memory or in a file for persistent storage.  

Explanation:
Contact Class: Represents a contact with attributes for name, phone number, and email. Implements Serializable for file storage.
ContactManager Class: Manages a list of contacts, providing methods to add, view, edit, and delete contacts. Handles saving and loading contacts to and from a file using serialization.
Main Class: Provides a user interface with a menu to interact with the ContactManager. Users can add, view, edit, and delete contacts based on their input.
