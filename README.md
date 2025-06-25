Phishnet Dark Guard
Phishnet Dark Guard is a web-based cybersecurity tool designed to detect phishing URLs by analyzing their structure and content. Built with HTML5, CSS3, and JavaScript, it features a sleek, animated user interface and real-time URL analysis to help users stay safe online. Whether you're checking a suspicious link or learning about phishing, this tool provides an intuitive and engaging experience.

Features

URL Analysis: Validates URLs and flags suspicious ones based on keywords (e.g., "login", "free gift card"), HTTP usage, and URL shorteners.
Trusted Domains: Recognizes trusted domains like facebook.com and paypal.com to avoid false positives.
Voice Input: Supports voice recognition for URL entry using the Web Speech API (available in supported browsers).
Responsive Design: Optimized for desktop and mobile devices with smooth animations and transitions.
Interactive UI: Includes canvas-based background animations, a typewriter effect, and a newsletter carousel.
Newsletter Subscription: Allows users to subscribe to stay updated on cybersecurity news.
Educational Content: Provides insights on phishing techniques and prevention tips.
Live Demo
Check out the live demo hosted on GitHub Pages: Phishnet Dark Guard Demo

Getting Started

Follow these steps to set up and run the project locally or deploy it on GitHub Pages.

Prerequisites
A modern web browser (e.g., Chrome, Firefox, Edge)
Git installed on your machine
A GitHub account
Installation

Clone the Repository:

git clone https://github.com/nguopman/phishnet-dark-guard.git
cd phishnet-dark-guard


Open the Project:


Open index.html in a web browser to view the website locally.
Alternatively, use a local server (e.g., with VS Code's Live Server extension) for a better development experience.
Deploy to GitHub Pages (Optional):

Push your code to a GitHub repository.
Go to your repository on GitHub and navigate to Settings > Pages.
Set the Source to the main branch (or the branch containing your code) and the root folder (/).
Save and wait for GitHub to provide a URL (e.g., https://your-username.github.io/phishnet-dark-guard/).

Project Structure

phishnet-dark-guard/
├── index.html        # Main HTML file
├── script.js         # JavaScript for functionality and animations
├── style.css         # CSS for styling and responsive design
├── assets/           # Folder for images, videos, or other media (create if needed)
└── README.md         # This file

Usage





Analyze a URL:

Enter a URL in the search bar (e.g., http://free-giftcard-paypal-login.com).

Click the search button or press Enter to analyze.
View the result: "Safe", "Suspicious", "Dangerous", or "Invalid", along with detailed issues (if any).
Voice Input:

Click the microphone button (if supported by your browser).
Speak the URL clearly and confirm the transcript to analyze it.



Explore Sections:

How It Works: Learn about phishing techniques and prevention tips.
Newsletter: Browse recent cybersecurity news and subscribe for updates.
WhoAMI: Meet the developer and view social links.



Test URLs:

Safe: facebook.com/login, paypal.com
Suspicious: http://login-free.com, bit.ly/offer
Dangerous: http://free-giftcard-paypal-login.com, tinyurl.com/paypal-login
Invalid: not-a-url, ftp://invalid.com

Contributing

Contributions are welcome! If you'd like to improve Phishnet Dark Guard, please follow these steps:





Fork the repository.



Create a new branch (git checkout -b feature/your-feature).



Make your changes and commit them (git commit -m "Add your feature").
Push to your branch (git push origin feature/your-feature).
Open a Pull Request with a clear description of your changes.

Please report any issues or bugs via the Issues tab.

Credits

Developed by: Syed Mohsin Abbas Naqvi

Special Thanks: Miss Anila Saghir (Instructor)



Libraries:

Font Awesome for icons
Inter Font for typography
Poppins Font for newsletter cards

License

This project is licensed under the MIT License. See the LICENSE file for details.


Contact
Feel free to reach out for questions or feedback:
GitHub: @nguopman
LinkedIn: inkedin.com/in/thenguopman
Email: mailsyedmanofficial@gmail.com
⭐️ If you find this project useful, please give it a star on GitHub! ⭐️
