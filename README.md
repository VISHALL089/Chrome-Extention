ReactJS Productivity Chrome Extension — Setup & Guide

A step-by-step guide to creating and running a React-based Chrome extension that tracks user activity on websites to help improve productivity.

Installation & Setup

Clone the repository from your version control system.

Run npm install to install all dependencies.

Run npm run build to generate the production build inside the build directory.

Open your browser and navigate to chrome://extensions.

Enable Developer mode (toggle in the top right corner).

Click Load unpacked and select the build folder from your project.

The extension will now appear in your Chrome extensions list.

Open any website, then click the extension icon to see time spent on each site.

Switching tabs automatically pauses the timer for the inactive tab.

If the time spent exceeds your configured limit, the extension replaces the website’s content with a cat image as a gentle reminder.

Suggested Improvements

Automatic Daily Reset: Reset tracked time automatically at midnight.

Manual Reset Button: Allow users to reset the timer manually from the popup interface.

Stop Timing After Limit: When the time limit for a domain is exceeded, stop incrementing the timer until the next reset.

