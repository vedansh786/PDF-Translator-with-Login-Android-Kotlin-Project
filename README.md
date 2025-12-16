# PDF-Translator-with-Login-Android-Kotlin-Project
PDF Translator with Login – Android Kotlin Project  

A lightweight yet full‑featured PDF translation application built using Android (Kotlin), designed to let users securely log in, pick any PDF, extract its text, and translate it into their chosen language.

🔐 Key Features  

- User Registration & Login:  
  Local account system using SQLite so each user registers, logs in, and accesses the app through their own credentials.  
- PDF Translation Screen:  
  Users select a PDF from device storage, the app extracts text and translates it into the target language, showing progress for large files.  
- Sidebar Navigation Drawer:  
  A left slide‑out menu provides quick access to core sections: Translate, Profile, and About.  
- Profile Activity:  
  Dedicated screen that displays stored user details (like name/email) pulled from the SQLite database.  
- About Page:  
  Clean “About this project” screen explaining the app’s purpose, tech stack, and credits (Prepared by Vedansh Arya, BCA).

⚙️ Core Functions  

- Register a new user and log in with local SQLite‑backed credentials.  
- Open a PDF file, extract its readable text, and translate it into the selected language.  
- Handle long PDFs by splitting text into chunks and translating them sequentially.  
- View and manage basic profile information in the Profile activity.  
- Navigate between Translate, Profile, and About using the navigation drawer.

💡 Tech Stack  

- Android (Kotlin, Android SDK)  
- PDF processing via PDFBox (or similar library)  
- SQLite for local user data persistence  
- Coroutines (Dispatchers.IO/Main) for background PDF parsing and network calls  
- OkHttp + translation API (e.g., DeepL API Free) for HTTP requests and JSON handling  

🎯 Purpose  

Created as a mini‑project to demonstrate practical Android app development: multi‑screen navigation with a DrawerLayout, secure-ish local login using SQLite, robust PDF text extraction, and real‑world API integration for translation. Ideal for showcasing skills in Kotlin, UI design, local data storage, and asynchronous networking in a complete, user‑friendly mobile application.
