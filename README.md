# Trie-based Contact Search Application

This C++ program is a simple contact search application that uses a Trie data structure to efficiently find and display contact suggestions based on user input. The program allows users to save contact details and then search for contacts by entering partial names.

## How to Run:

1. **Compile and Run:**
   - Compile the program using a C++ compiler (e.g., g++):
     ```bash
     g++ contact_search.cpp -o contact_search
     ```
   - Run the compiled program:
     ```bash
     ./contact_search
     ```

2. **Enter Contact Details:**
   - Enter the number of contact details you want to save.
   - Input the contact details as prompted.

3. **Search for Contacts:**
   - Enter the contact details you want to search for.
   - The program will display contact suggestions based on the entered query.

## Application Logic:

- The program uses a Trie data structure to efficiently store and retrieve contact details.
- Contacts are inserted into the Trie during initialization.
- Users can enter partial names, and the program displays contact suggestions based on the entered prefix.

## User Interaction:

- The user first inputs the number of contact details they want to save and then enters each contact's details.
- After saving contacts, the user enters a query string to search for contacts.
- The program displays contact suggestions based on the entered query.

## Notes:

- The application assumes that contact details are alphanumeric strings.
- Trie data structure is used to optimize contact search operations.
- Suggestions are displayed dynamically as the user enters characters.

## Developer:

- This contact search application was developed by an anonymous contributor.
