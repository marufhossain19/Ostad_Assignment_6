<p align="center">
  <span style="font-size:20px; color:red;"><b>Md. Maruf Hossen</b></span><br>
  <span style="font-size:18px; color:green;"><b>Ostad Assignment 6</b></span>
</p>

# Assignment 6 - Contact List Flutter App

## Overview
A Flutter application that implements a dynamic Contact List where users can add contacts using input fields and an Add button. The app uses a **StatefulWidget** so that when the user enters a name and phone number and clicks the **Add** button, the new contact is displayed in the list below.

## Project Structure
```
assignment_6/
├── lib/
│   └── main.dart                  # Main application code
├── contact_list_output.png        # Application output screenshot
├── contact_list_full_output.png   # Full UI output screenshot with code
├── pubspec.yaml                   # Flutter project dependencies
└── README.md                      # This file
```

## Features Implemented

### Widgets Used
✅ **TextFormField** — Two input fields for entering contact name and phone number (Lines 77–93)  
✅ **ElevatedButton** — Add button to submit the contact to the list (Lines 99–110)  
✅ **Card** — Each contact is wrapped in a Card widget for clean styling (Line 120)  
✅ **ListTile** — Displays contact name, phone number, and icons inside each Card (Lines 121–132)  

### Core Concepts Applied
✅ **StatefulWidget** — `ContactListScreen` uses StatefulWidget to manage dynamic contact list state (Lines 23–28)  
✅ **setState()** — Used to update the UI when a new contact is added (Lines 53–55)  
✅ **TextEditingController** — Controllers for name and phone input fields (Lines 31–32)  
✅ **ListView.builder** — Dynamically builds the contact list from the contacts data (Lines 116–135)  
✅ **Input Validation** — Both name and phone fields must be non-empty to add a contact (Line 52)  
✅ **dispose()** — Properly disposes TextEditingControllers to prevent memory leaks (Lines 41–46)  

### Additional Features
✅ Material Design Components  
✅ Custom Styling and Theming  
✅ Icon Usage (person & phone icons)  
✅ Layout Management (Column, Padding, Expanded)  
✅ AppBar with centered title  

## How It Works
1. User enters a **name** in the first TextFormField
2. User enters a **phone number** in the second TextFormField
3. User clicks the **Add** button
4. The new contact appears in the list below with a person icon and phone icon
5. Input fields are cleared after adding

## Output

### Screenshots
- **contact_list_output.png**: Application output on emulator

  ![Output](contact_list_output.png)

- **contact_list_full_output.png**: Full UI output with code and emulator

  ![Full Output](contact_list_full_output.png)

## Author
**Maruf Hossain**

---

*This is Assignment 6 - A Flutter Contact List application project.*
