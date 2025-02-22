# Portfolio Visitor Counter

A simple, elegant visitor counter for your portfolio website, powered by Firebase Firestore. This project tracks the number of visitors to your portfolio and displays the count in real-time.

---

Features
markdown
- Tracks and updates visitor count in real-time.
- Displays visitor count on the webpage.
- Easy integration with Firebase Firestore.


How It Works
markdown
Copy code
- Each time a visitor loads your portfolio, the counter updates in the Firebase Firestore database.
- The counter value is retrieved and displayed dynamically on your webpage.


You're right! If you want to keep everything consistently inside code blocks, I should format everything in the markdown as code blocks (with proper syntax highlighting where necessary). Here's the updated content with all sections inside code blocks:

markdown
Copy code
# Portfolio Visitor Counter

A simple, elegant visitor counter for your portfolio website, powered by Firebase Firestore. This project tracks the number of visitors to your portfolio and displays the count in real-time.

---

## **Features**
- Tracks and updates visitor count in real-time.
- Displays visitor count on the webpage.
- Easy integration with Firebase Firestore.
How It Works
markdown
Copy code
- Each time a visitor loads your portfolio, the counter updates in the Firebase Firestore database.
- The counter value is retrieved and displayed dynamically on your webpage.
Setup Instructions
1. Clone the Repository
bash

git clone https://github.com/your-username/portfolio-visitor-counter.git
cd portfolio-visitor-counter


2. Add Firebase Configuration

Go to the Firebase Console and create a new project. Set up Firestore Database: Navigate to Build > Firestore Database and create a database. Use Production Mode for real-time access. Create a collection named counters and add a document: Document ID: visitorCount Field Name: count Field Type: Number Field Value: 0 Copy your Firebase configuration from Project Settings > General > Your Apps.
3. Replace Firebase Config in Code


![Screenshot 2025-01-05 142629](https://github.com/user-attachments/assets/b2cb7d08-737d-4796-8d7f-240674d7e139)

4. Run the Project
markdown
Copy code
Open index.html in your favorite code editor. Use a live server to preview the project: For VS Code: Install and use the "Live Server" extension. Open the file in a browser directly.
How to Test
markdown
Copy code
- Open the webpage in your browser.
- Refresh the page and observe the counter incrementing.
- Check the Firestore Database to verify the count updates.
Troubleshooting

Go to Firebase Console > Firestore Database > Rules and ensure the read and write rules are set to true:
Save and publish the changes.

Still facing issues? Check the browser console for error messages using Inspect > Console.

