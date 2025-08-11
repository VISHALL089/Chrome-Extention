ReactJS Productivity Chrome Extension
A React-based Chrome extension that tracks the time you spend on different websites to help boost productivity.
If you exceed your configured time limit for a site, the extension will gently remind you by replacing the site’s content with a cute cat image 🐱.

✨ Features
Time Tracking — Tracks time spent on active websites.

Tab-Aware — Automatically pauses timing when you switch to another tab.

Time Limit Alerts — Shows a cat image when you exceed the set time limit for a site.

Configurable Limits — Set how long you want to spend per website.

Gentle Reminders — Replace distracting sites after limit is reached.

📦 Installation & Setup
Follow these steps to set up the extension locally:

Clone the repository

bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
Install dependencies

bash
npm install
Build the extension

bash
npm run build
This generates the production build in the build directory.

Load the extension in Chrome

Open Google Chrome and go to:

text
chrome://extensions/
Enable Developer Mode (top-right toggle).

Click Load unpacked and select the build folder from your project.

Start using the extension

Open any website and click the extension icon to see time spent.

Switching tabs will pause the timer for the inactive tab.

If time exceeds your limit, the website is replaced with a cat image reminder.

🛠 Tech Stack
Frontend: ReactJS

Chrome APIs: Tabs, Storage, Runtime

Build Tool: Create React App (CRA) / Webpack (custom for Chrome MV3 compatibility)

