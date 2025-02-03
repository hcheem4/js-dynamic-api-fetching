# JavaScript Dynamic API Fetching & Routing

🚀 This project demonstrates dynamic API fetching, async/await, JSON 
handling, localStorage for data persistence, and JavaScript-based routing.

## 🔹 Features
- Fetches user posts dynamically using `fetch()` and `async/await`
- Stores user IDs in `localStorage` to persist data across pages
- Routes to `user.html` dynamically on user selection
- Updates the UI in real-time when a new user ID is entered
- Uses `.map()` and `.join("")` to generate HTML dynamically

## 🛠 Tech Stack
- HTML, CSS, JavaScript
- JSONPlaceholder API
- LocalStorage for data persistence

## 📂 How It Works
1. Click on a user → Saves their ID in `localStorage` and redirects to 
`user.html`.
2. On `user.html`, it fetches and displays posts for the stored user ID.
3. Changing the input field dynamically fetches posts for a new user.

