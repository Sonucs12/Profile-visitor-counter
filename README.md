# Portfolio Visitor Counter

A simple, elegant visitor counter for your portfolio website, powered by Firebase Firestore. This project tracks the number of visitors to your portfolio and displays the count in real-time.

---

## **Features**
```markdown
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
```markdown
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
Copy code
git clone https://github.com/your-username/portfolio-visitor-counter.git
cd portfolio-visitor-counter


2. Add Firebase Configuration
markdown
Copy code
Go to the Firebase Console and create a new project. Set up Firestore Database: Navigate to Build > Firestore Database and create a database. Use Production Mode for real-time access. Create a collection named counters and add a document: Document ID: visitorCount Field Name: count Field Type: Number Field Value: 0 Copy your Firebase configuration from Project Settings > General > Your Apps.
3. Replace Firebase Config in Code
javascript
Copy code
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
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
Error: Visitor count not loading
json
Copy code
{
  "rules": {
    ".read": "true",
    ".write": "true"
  }
}
markdown
Copy code
Go to Firebase Console > Firestore Database > Rules and ensure the read and write rules are set to true:
Save and publish the changes.

Still facing issues? Check the browser console for error messages using Inspect > Console.
Demo
markdown
Copy code
Check out the live demo of this project here.
Resources
markdown
Copy code
YouTube Tutorial: CodingSuno YouTube Channel
GitHub Profile: Sonu Kumar GitHub
LinkedIn Profile: Sonu Kumar LinkedIn
Portfolio: Portfolio Website
License
markdown
Copy code
This project is open-source under the MIT License.
Contribute
markdown
Copy code
If you find any bugs or have suggestions, feel free to open an issue or make a pull request.
markdown
Copy code
Happy Coding! 😊
