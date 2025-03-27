# PhoneBook-with-Call-Log-System
This C++ program implements a comprehensive Phone Book system with integrated Call Log functionality. The system allows users to manage contacts and track call history with detailed information about each call. This project demonstrates object-oriented programming principles, file I/O operations, and efficient data organization techniques in C++.

# Key Features

> Phone Book Functionality

Phone book can be Added, updated, deleted, and search contacts. Contacts are automatically sorted by name. It can Stores names, phone numbers, emails, and addresses and also find contacts by name or initial letter.

> Call Log System

It records incoming and outgoing calls. It stires details such as call duration, date, time, and type (incoming/outgoing). Call logs can bu searched by contact name and calls are sorted chronologically.

> Technical Implementation

It uses linked lists for contact management and call logs. Persists data between sessions using text files and also uses Console-based menu system with input validation

> Sorting Algorithms

Implements merge sort for efficient call log organization.

# How to Use
Run the program to access the main menu. Choose between Phone Book or Call Log operations

Follow the on-screen prompts to:

Add new contacts. Update existing contacts. View call history. Log new calls. Search for specific records.

# Project Structure
Contact Class: Handles contact information storage.
CallLog Class: Manages call history records.
PhoneBook Class: Implements core phone book functionality.
User Class: Provides the interface and menu system.

# Requirements
C++ compiler (supporting C++11 or later)
Standard Library headers: <iostream>, <fstream>, <string>, <queue>

# File Storage
The system uses two text files for data persistence:
phonebook.txt: Stores all contact information
call_log.txt: Maintains call history records
