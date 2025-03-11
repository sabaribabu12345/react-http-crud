🚀 User Management App
A simple React application that allows users to view, add, update, and delete users using jsonplaceholder.typicode.com as a mock API.

✨ Features
Fetches user data from an API (https://jsonplaceholder.typicode.com/users).
Allows adding new users.
Enables editing user details (email, website).
Supports updating user information via API.
Allows deleting users with instant UI updates.
🛠 Setup Instructions
1️⃣ Clone the repository
sh
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2️⃣ Install dependencies
sh
Copy
Edit
npm install
3️⃣ Start the development server
sh
Copy
Edit
npm start
Your app should now be running at http://localhost:3000/ 🚀.

🔧 How It Works
Fetching Users
When the app loads, it fetches user data from jsonplaceholder.typicode.com and displays it in a table.

Adding a User
Enter Name, Email, and Website in the input fields.
Click the "Add User" button.
The user gets added to the list and stored in the API.
Editing a User
Click on the email or website field to edit it.
Click "Update" to save changes.
Deleting a User
Click the "Delete" button next to a user.
The user is removed from the list and deleted from the API.
📌 Technologies Used
React (useState, useEffect)
BlueprintJS (UI components)
JSONPlaceholder API (Mock API for users)
