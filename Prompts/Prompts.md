#  MobiVault – AI Code Generation Prompts

This document contains prompts written for tools like Copilot, Cursor, or GPT-based code generators. Each prompt is designed to produce a usable component or logic block from MobiVault’s planned architecture.



### 🧩 Prompt 1: Login / Sign Up Screen

**What I want to build:**  
A login and sign-up screen for a mobile app that supports both email/password authentication and biometric login.

**Tech stack:**  
Flutter using Firebase Authentication and SharedPreferences (for biometric toggle)

**Prompt:**  
“Create a Flutter login screen with email and password fields, and a switch to enable biometric login. On successful login, navigate to the Dashboard screen. Use Firebase Authentication for email login and SharedPreferences to remember biometric preference.”

**Expected Output:**  
- A login form with validation  
- Firebase integration  
- Navigation logic to dashboard  
- SharedPreferences code for biometric toggle



### 🧩 Prompt 2: File Upload Feature

**What I want to build:**  
A screen where the user uploads a file, chooses to store it either locally or in the cloud, and optionally enables encryption.

**Tech stack:**  
Flutter with `file_picker`, Firebase Storage, and `encrypt` package

**Prompt:**  
“Generate a Flutter UI where the user selects a file using file_picker, chooses ‘local’ or ‘cloud’ as the storage destination, and can toggle encryption on/off. If cloud is selected, upload to Firebase Storage with metadata.”

**Expected Output:**  
- UI for file selection  
- Radio buttons for storage type  
- Toggle switch for encryption  
- Firebase upload logic with metadata tags



### 🧩 Prompt 3: Access Log Viewer

**What I want to build:**  
A screen that shows a list of access events for the user’s files, including timestamps and device info.

**Tech stack:**  
Flutter with a local database (Isar)

**Prompt:**  
“Build a Flutter screen that displays a scrollable list of access logs. Each item should show file name, date/time accessed, device type, and access location. Use Isar to fetch data from a local database.”

**Expected Output:**  
- ListView with styled rows  
- Async fetch from local DB  
- Optional filter or search field  
- Layout ready for integration into settings tab

