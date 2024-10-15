<video width="600" controls>
  <source src="https://drive.google.com/file/d/180e9Ut3oh40jQFUlU_pIieuvyBZ43APo/view?usp=sharing" type="video/mp4">
  Your browser does not support the video tag.
</video>


Overview:
This project is a comprehensive web-based platform designed for gamers to explore, rate, and discuss video games. Users can search for games, add them to their personal game library, rate them, and participate in discussions in forum topics. The platform integrates with the RAWG.io API to provide detailed game information, and it features a custom user authentication system with PostgreSQL for storing user data.

Features:
User Authentication: Secure user login and registration system with unique username and email validation. User sessions are maintained to personalize the experience.

Game Search: Users can search for games using the RAWG.io API. The search results include game titles, background images, ratings, and other relevant details.

Game Library: Logged-in users can maintain a personalized game library, including:

Liked Games: Games the user has liked.
Played Games: Games the user has played, including playtime and completion date.
To Play Games: Games the user wants to play in the future.
Game Details: Detailed information about each game, including title, description, background image, rating, system requirements, and more.

Game Interaction:

Rate Games: Users can rate games out of 10.
Comment on Games: Users can leave comments on game pages.
Add/Remove from Library: Users can add games to their library (Liked, Played, To Play) and remove them as needed.
Forum: A community-driven forum where users can create and discuss topics related to gaming.

Comment on Topics: Users can participate in discussions by commenting on topics.
Responsive Design: The platform is designed to be accessible and user-friendly across various devices.

Technical Details:
Frontend: HTML, CSS, JavaScript (with integration of AJAX for dynamic data fetching).
Backend: Node.js with Express.js framework.
Database: PostgreSQL for storing user data, game library, and forum topics.
API Integration: RAWG.io API for fetching game data.
Session Management: Handled via express-session for maintaining user login states.
Security: Passwords are securely encrypted before storing in the database.
Setup Instructions
Clone the Repository:

