# Comments Dashboard & Profile Screen – React Assignment

## 📋 Project Overview

This is a frontend React-based assignment focused on building a two-screen dashboard that displays user and comment data using dummy API endpoints. The project emphasizes UI design, data handling, routing, and client-side persistence (localStorage).

---

## 🚀 Features

### 1. **Profile Screen**
- Fetches user data from the dummy users API.
- Displays only the first user's details in a non-editable format.
- Includes a button to navigate back to the comments dashboard.
- Proper routing is maintained between the Profile and Dashboard pages.

### 2. **Comments Dashboard**
- Fetches and displays 500 comment records from the dummy comments API.
- Implements **manual pagination** (10, 50, 100 items per page) without third-party libraries.
- **Partial search** functionality on Name, Email, and Phone fields.
- **Sorting** on Post ID, Name, and Email with cycling logic:
  - No Sort → Ascending → Descending → No Sort
  - Only one column can be sorted at a time.
- **State Persistence** using `localStorage` for:
  - Search query
  - Sort preferences
  - Current page
  - Page size
- Fully **responsive design** with enhanced UI for mobile and desktop.
- Works across major browsers (Chrome, Firefox, Edge).

---

## 🔗 Dummy APIs Used

- **Users API:** `https://jsonplaceholder.typicode.com/users`
- **Comments API:** `https://jsonplaceholder.typicode.com/comments`

---

## 🛠 Tech Stack

- **Frontend Framework:** React (with React Router)
- **Language:** JavaScript (TypeScript optional)
- **Styling:** CSS / Tailwind / Bootstrap (any UI library allowed)
- **State Persistence:** LocalStorage
- **No usage of third-party libraries** for pagination, sorting, or searching logic.

---

## 🧪 Running the Project

### 1. Clone the Repository

```bash
git clone <https://github.com/SahithiGurram10/SWIFT-Front-End-Internship-Assignment--main/>
cd project-folder
2. Install Dependencies
bash
npm install
3. Start the Development Server
bash
npm start
Project will be accessible at http://localhost:3000.

🧼 Before Submitting
✅ Ensure routing works properly between Profile and Dashboard

✅ Page reload retains user’s current filters (search, sort, pagination)

✅ Fully responsive and visually clean UI

✅ No third-party libraries for core logic (pagination/sorting/search)

✅ node_modules is excluded from the ZIP file

✅ Upload zipped folder to Google Drive and share the link

📝 Notes
This assignment is a critical part of the internship selection process.

All functionality must be completed within 48 hours of receiving the task.

Additional points for using TypeScript and well-structured reusable components.

👩‍💻 Developed By
Gurram Sahithi Pratyusha

Email: pratyusha6212@gmail.com

