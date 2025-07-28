🏏 Hand Cricket Game with Streamlit 🎮
A classic Hand Cricket game brought to life as an interactive web application using Python and Streamlit.

<p align="center">
<a href="https://handcricket.streamlit.app/" style="text-decoration:none;">
<img src="https://img.shields.io/badge/Play%20it-Live!-brightgreen?style=for-the-badge&logo=streamlit" alt="Play it Live!">
</a>
&nbsp;&nbsp;&nbsp;
<a href="https://github.com/sharma987piyush/handcricket.git" style="text-decoration:none;">
<img src="https://img.shields.io/github/stars/sharma987piyush/handcricket?style=for-the-badge&logo=github&label=Star%20on%20GitHub" alt="Star on GitHub">
</a>
</p>

✨ Features
🌐 Web-Based Interface: Play a clean, interactive game of Hand Cricket on a web app built with Streamlit.

🤖 Smart AI Opponent: The computer makes random, unpredictable choices, making every match unique.

🏆 Full Game Logic: Includes a complete toss sequence (Even/Odd), batting, and bowling phases.

📊 Real-Time Scoreboard: Keep track of your score, the computer's score, and the target in real-time.

🚀 Easy to Run: Get the game running locally with just a few simple commands.

📖 Clean Codebase: The backend logic and frontend UI are separated for easy understanding and future development.

📋 Prerequisites
Before you begin, ensure you have the necessary tools installed on your system.

🐍 Python 3.x

📦 pip (Python's package installer)

🌿 Git (For cloning the repository)

🚀 How to Play
Getting the game up and running is quick and easy. Just follow these steps in your terminal:

Clone the repository to your local machine

git clone https://github.com/sharma987piyush/handcricket.git

Navigate into the project directory

cd handcricket

Install the required Python library

pip install streamlit

Run the Streamlit application

streamlit run app.py

Your web browser will automatically open a new tab with the game ready to play!

🏛️ Project Structure
The project is organized into two main components, separating the core game logic from the user interface.

1. handcricket.ipynb (The Game's Brain)
Purpose: Contains the original backend logic for the Hand Cricket game.

This Jupyter Notebook file holds the fundamental rules of the game: how the toss works, how runs are scored, and the conditions for a player being "out". It was the foundation for building the interactive web application.

2. app.py (The Interactive Frontend)
Purpose: Creates the web-based user interface using Streamlit.

This Python script takes the logic from the notebook and brings it to life. It handles everything the user sees and interacts with: the buttons, the scoreboard, the game-stage transitions (toss, batting, game over), and the real-time updates. It uses Streamlit's session_state to remember scores and game progress.

🤝 Contributing & Future Ideas
Contributions, issues, and feature requests are welcome! Feel free to check the issues page. Some ideas for the future include:

🎨 Adding more visual flairs and animations.

👥 Implementing a two-player mode.

📈 Storing high scores.

🏏 Adding different game formats (e.g., 5-wicket matches).

📜 License
This project is licensed under the MIT License.

<p align="center">
<em>Crafted with ❤️ and ☕ in India.</em>
</p>
