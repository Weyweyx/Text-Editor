J.A.T.E. (Just Another Text Editor)

Description
J.A.T.E. (Just Another Text Editor) is a Progressive Web Application (PWA) that allows users to create and save notes or code snippets, even without an internet connection. Built with a simple, user-friendly interface, this app is designed to function offline and can be installed directly on your device for seamless access.

The application utilizes modern web technologies such as IndexedDB for data persistence, Webpack for bundling, and Workbox for service worker integration, making it a robust, scalable, and offline-capable solution.

Features
Offline Functionality: Automatically saves and retrieves content using IndexedDB.
PWA Installation: Installable as a PWA for easy desktop or mobile access.
Modern JavaScript: Uses ES6+ features and Babel for compatibility.
Service Workers: Caches static assets for offline access.
Data Persistence: Saves data automatically when the DOM loses focus.

Usage
Open the application in your browser or install it as a PWA.
Create and edit notes or code snippets.
Your content will be saved automatically when you leave the editor or close the application.
Reopen the application to retrieve your saved content, even offline.


Technologies Used
Frontend:
HTML5
CSS3 (with CSS loaders for Webpack)
JavaScript (ES6+)
Backend:
Node.js
Express.js
Build Tools:
Webpack
Babel
Other:
IndexedDB (idb library)
Workbox for service worker and caching
WebpackPwaManifest for PWA manifest generation


Screenshots

[App Screenshot](client/src/images/Screenshot%202024-12-14%20at%202.23.03 PM.png)
[Screenshot](client/src/images/Screenshot%202024-12-14%20at%202.23.56 PM.png)

Link

https://text-editor-5ras.onrender.com


