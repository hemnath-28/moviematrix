MoVie MaTRiX
MoVie MaTRiX is a web application that recreates a simplified version of IMDb using basic HTML, CSS, and JavaScript. It leverages The Movie Database (TMDb) API for fetching movie and TV show data and integrates Firebase for user authentication and watchlist management.

Overview
MoVie MaTRiX provides a responsive and modern interface featuring a fixed top navigation bar and a left sidebar. Users can browse various movie categories, search for their favorite films, and explore popular TV shows. This project is designed to demonstrate basic web development skills along with API integration and real-time data fetching.

Features
Responsive Design: Basic HTML and CSS for a clean, adaptable user interface.
Navigation: A fixed top bar and a left sidebar for quick access to different sections.
Movie Listings: View top-rated, popular, and now-playing movies.
TV Show Listings: Browse 30 popular TV shows fetched from TMDb.
Search Functionality: Dynamic search for movies.
User Authentication: Firebase integration for login, registration, and watchlist management.
Theme Toggle: Switch between dark and light modes for a personalized experience.
Technology Stack
Frontend: HTML, CSS, JavaScript
Backend/API: TMDb API (The Movie Database)
Authentication & Database: Firebase (Authentication and Firestore)
Fonts: Poppins from Google Fonts
Installation & Setup
Clone the Repository:

bash
Copy
Edit
git clone <repository_url>
cd moviematrix
Firebase Configuration:

Create a new project in the Firebase Console.
Enable Firebase Authentication and Firestore for your project.
Replace the Firebase configuration object in your HTML files (e.g., index.html, tvshows.html) with your project's configuration details.
TMDb API Key:

Sign up for an API key at The Movie Database (TMDb).
Update the API key in your JavaScript code (look for the API_KEY variable) with your TMDb API key.
Running the Project:

Open the HTML files (e.g., index.html, tvshows.html) directly in your web browser.
Alternatively, use a local development server (like the Live Server extension for VSCode) to serve the files.
File Structure
bash
Copy
Edit
moviematrix/
├── index.html         # Main landing page for movies
├── tvshows.html       # Page displaying popular TV shows
├── css/               # (Optional) Folder for external CSS files
├── js/                # (Optional) Folder for external JavaScript files
└── README.md          # This file
Customization
Styling: The project uses basic CSS. Feel free to modify or extend the CSS to suit your design preferences.
Components: The HTML structure is modular, allowing you to add or remove sections as needed.
API Endpoints: Explore additional endpoints from TMDb to display trending movies, upcoming films, or other categories.
Contributing
Contributions are welcome! If you'd like to improve the project or add new features, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for further details.

Acknowledgements
TMDb API for providing movie and TV show data.
Firebase for authentication and database services.
Google Fonts for the Poppins font.
This README file provides a comprehensive overview of the project, detailed setup instructions, and key information needed to work with the MoVie MaTRiX codebase
