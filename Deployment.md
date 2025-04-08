🛠 Deployment Document for Provincial Wars
📄 Project Overview
Provincial Wars is a web-based strategy game where players and AI opponents expand territories on a grid map. It is built using vanilla HTML, CSS, and JavaScript, rendered on an HTML5 canvas element.

✅ Requirements
Local Development Environment
A modern browser (Chrome, Firefox, Edge)

A text/code editor (e.g., VS Code)

Optional: Local server (for testing with file access, e.g., Live Server)

Hosting Options
GitHub Pages

Netlify

Vercel

Any static file server or shared hosting service

📦 Project Structure
graphql
Copy
Edit
provincial-wars/
│
├── index.html        # Main game file with embedded CSS and JS
└── README.md         # Optional: add gameplay instructions or credits
Currently, all logic and styles are embedded inside index.html.

💻 Local Deployment Instructions
Clone or Download the Project:

bash
Copy
Edit
git clone https://github.com/your-username/provincial-wars.git
cd provincial-wars
Open in Browser:

Just double-click index.html to open it in your browser.
Or use a local server:

With VS Code:

Install the Live Server extension.

Right-click index.html → Open with Live Server.

🚀 Production Deployment
Option 1: GitHub Pages
Push your code to GitHub.

Go to your repository → Settings → Pages.

Under Source, choose the branch (e.g., main) and root (/).

Click Save.

Your game will be live at:
https://your-username.github.io/provincial-wars/

Option 2: Netlify
Go to https://netlify.com.

Log in and click New site from Git.

Connect your GitHub repository.

Set the build settings as:

Build command: (leave blank, static site)

Publish directory: /

Click Deploy Site.

Your site will get a random .netlify.app domain (you can customize it).

Option 3: Vercel
Go to https://vercel.com.

Import your project from GitHub.

Select Framework Preset: Other (since it's plain HTML/JS).

Click Deploy.

You'll get a .vercel.app link.

INSTRUCTIONS

Type https://kprmodi.github.io/provincial-wars/ in browser to play game
