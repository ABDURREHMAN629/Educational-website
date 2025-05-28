⚠️ Important Note for Accessing Component-Based Pages
This project uses fetch() to dynamically load reusable HTML components (like navbar.html, footer.html, etc.).

🛑 If you open the HTML files directly using file://, the components will not load due to browser security restrictions.

✅ To properly view and test the pages:
You must run the project using a local development server. Here are some simple options:

💡 Option 1: Using Live Server (VS Code Extension)
Install the Live Server extension in VS Code.

Right-click on index.html (or any HTML file) and select "Open with Live Server".

Your browser will open the file correctly at http://localhost:5500.

💡 Option 2: Using Python (if installed)
bash
Copy
Edit
# In your project directory:
python3 -m http.server
# Then visit: http://localhost:8000
💡 Option 3: Using Node.js (if installed)
bash
Copy
Edit
# First install the serve package:
npm install -g serve

# Run it in the project directory:
serve .
