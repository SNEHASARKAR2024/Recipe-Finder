🍽️ Recipe Finder App
Built with HTML, CSS & JavaScript — From Scratch!

This is a simple, clean, and responsive Recipe Finder Web App that allows users to search recipes by keyword. The app fetches live recipe data using a public API and displays dish images, ingredients, and steps in an easy-to-read card layout.

🚀 Features

✔️ Search recipes by dish name or ingredient
✔️ Fetch real-time data using a public API (TheMealDB / Edamam / Spoonacular)
✔️ Beautiful and responsive UI
✔️ Ingredient list + preparation details
✔️ Pop-up / modal for detailed recipe view
✔️ Fully developed using HTML, CSS & Vanilla JavaScript
✔️ Beginner-friendly project structure

📸 Demo Preview
Add your project GIF or screenshots here after uploading to GitHub.

🛠️ Tech Stack
HTML5 – Structure
CSS3 – Styling + Responsive Layout
JavaScript (Vanilla) – API fetching & interactivity
MealDB API (default) – Recipe data

📁 Project Structure
recipe-finder-app/
│── index.html
│── style.css
│── script.js
└── README.md

▶️ How It Works

User enters a keyword (e.g., "chicken", "pasta").
JavaScript calls the recipe API using fetch().
Results are shown in recipe cards with image + name.
Clicking “View Recipe” opens full instructions + ingredients.

📦 Installation & Usage

Clone the repository

git clone https://github.com/your-username/recipe-finder-app.git


Open the project folder

cd recipe-finder-app


Open index.html in your browser

Double-click the file

Or run using Live Server extension (VS Code recommended)

🔌 API Used
TheMealDB API

Example request:

https://www.themealdb.com/api/json/v1/1/search.php?s=chicken


You can switch to other APIs like Edamam or Spoonacular if needed.

🧩 Code Snippet (Fetch Function)
async function searchRecipe() {
    const query = document.getElementById('search-input').value;
    const url = `https://www.themealdb.com/api/json/v1/1/search.php?s=${query}`;

    const res = await fetch(url);
    const data = await res.json();
    displayRecipes(data.meals);
}

🎨 UI Highlights

Minimal, modern card-based layout

Hover effects for recipe cards

Mobile-friendly design

Clean buttons and modal view

🤝 Contributing

Contributions are welcome!
If you’d like to improve UI, add new features, or fix bugs:

Fork the repo

Create a new branch

Submit a pull request

⭐ Show Your Support

If you like this project, please star ⭐ the repository — it motivates me to build more awesome projects!

🧑‍💻 Author

Sneha Sarkar
Feel free to connect or check out more projects!
