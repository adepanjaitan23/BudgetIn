🚀 BudgetIn: Modern Budgeting Web App (Powered by Google Sheets)

A sleek, responsive, and modern personal finance dashboard that uses Google Sheets as its database. Built with Google Apps Script, HTML, Tailwind CSS, and Chart.js.

BudgetIn transforms a standard, boring spreadsheet into a beautiful Fintech-style web application. It allows you to track expenses, manage budgets, and visualize your financial data in real-time, all while keeping your data 100% private and secure within your own Google Drive.

Tip: Take a screenshot of your web app and replace the image link above.

✨ Key Features

No-Database Setup: Uses Google Sheets as a free, easily accessible, and editable backend database.

Real-time Synchronization: Edits made on the web app (like changing allocations or adding new expenses) are automatically saved to your Google Sheet without page reloads.

Interactive Dashboard: Features a modern Bar Chart and Doughnut Chart powered by Chart.js that update instantly as you type.

Mobile Responsive: The desktop table transforms into a beautiful, touch-friendly card layout when viewed on mobile devices.

Dynamic Customization: Add new Wallets/Accounts or Expense Categories directly from the Web App modal. The UI automatically generates new colors and updates the dropdowns.

Progress Tracking: Check off paid expenses to see a visual "strikethrough" effect and watch your monthly realization progress bar grow.

Smart Month Filtering: Data is saved in a single sheet but can be filtered dynamically by month and year.

Auto-Greeting: Greets the user using their Google account name.

🛠️ Tech Stack

Frontend: HTML5, JavaScript (Vanilla), Tailwind CSS (via CDN)

Data Visualization: Chart.js

Icons: FontAwesome 6

Backend & API: Google Apps Script (GAS)

Database: Google Sheets

📂 File Structure

Code.gs: The Google Apps Script backend. Handles reading/writing data to the spreadsheet, fetching dynamic dropdown rules, and storing monthly income data via PropertiesService.

Index.html: The single-file frontend containing structure, styling (Tailwind classes + custom CSS), and frontend logic (fetching data, rendering charts, auto-saving).

🚀 How to Install & Use (Setup Guide)

You can easily deploy your own instance of BudgetIn in less than 5 minutes. No server hosting required!

Step 1: Copy the Database Template

Make sure you are logged into your Google Account.

Click this link to copy the required database structure:

👉 Click Here to Copy the BudgetIn Template

Click "Make a copy".

Step 2: Clean the Dummy Data (Important!)

In your new Google Sheet, select the sample rows from row 2 downwards.

Press Delete or Backspace to clear them out.

Note: Keep Row 1 (Status, Account, Expenses List, etc.) intact.

Step 3: Add the Code

In your new Google Sheet, go to the top menu and click Extensions > Apps Script.

A new tab will open. Delete any existing code in the Code.gs file and paste the contents of the Code.gs from this repository.

Click the [+] icon on the left panel, select HTML, and name it Index (capital 'I').

Delete the default HTML code and paste the contents of Index.html from this repository.

Click the Save icon (💾).

Step 4: Deploy as a Web App

In the Apps Script editor, click the blue Deploy button at the top right, then select New deployment.

Click the gear icon (⚙️) next to "Select type" and choose Web app.

Fill in the configuration:

Description: BudgetIn v1 (or anything you like)

Execute as: Me (This ensures you can access it on your phone without logging in repeatedly).

Who has access: Anyone (Only those with the long, secret link can open it).

Click Deploy.

Note: Google will ask for Authorization. Click "Authorize access" > choose your email > click "Advanced" > click "Go to Untitled project (unsafe)" > click "Allow".

Done! Copy the Web app URL. This is the link to your personal finance app.

💡 Pro Tip: Open the Web app URL on your smartphone's browser (Safari/Chrome) and select "Add to Home Screen". BudgetIn will look and feel like a native mobile app!

🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📝 License

This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as you see fit.

Built with ❤️ using BudgetIn
