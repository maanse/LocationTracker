# LocationTracker

Work Journey Tracker

A lightweight, mobile-first web application designed to help you easily record your daily locations for work-related travel expenses. Built as a single-file application, it requires no backend or third-party database, keeping your data fast, local, and completely private.
✨ Features

    One-Tap Location Logging: Uses your device's built-in GPS to accurately fetch coordinates and log stops with a single click.

    Project & Custom Tags: Organize stops by custom projects (e.g., Client Work, Internal, Travel) to make submitting expense claims seamless.

    Interactive Journey Maps: Built-in history map view using Leaflet and OpenStreetMap to visualize your daily travel paths—no billing or Google Maps API keys required.

    Instant CSV Export: Download all history and today's active logs instantly as a neatly formatted CSV spreadsheet, ready to upload or attach to your company expense tool.

    100% Privacy & Offline-Ready: All journey data is kept entirely within your mobile browser’s local storage (localStorage). No tracking, no external servers.

🛠️ Built With

    HTML5 / CSS3: Mobile-responsive interface featuring custom CSS variables, responsive grids, and strict safe-area styling for seamless viewing on iPhone and Android devices.

    Vanilla JavaScript: Fast, lightweight execution utilizing standard native APIs (like Geolocation and crypto.randomUUID).

    Leaflet & OpenStreetMap: Free, high-performance mapping engine for loading interactive routing visuals.

🚀 Quick Start & Hosting

Because mobile browsers require a secure connection (HTTPS) to grant location permissions, you must host this script on an HTTPS-enabled domain. Here are the two quickest ways to host it for free:
Option A: Netlify Drop (Fastest — < 1 Minute)

    Place the index.html file into an empty folder on your computer.

    Drag and drop that folder onto Netlify Drop.

    Open the generated https://... link on your phone.

Option B: GitHub Pages (Permanent — 2 Minutes)

    Create a Public repository on GitHub.

    Upload the index.html file to the main branch.

    Head to repository Settings -> Pages, choose the main branch as your build source, and hit Save.

📱 Mobile Configuration Tip

When you open the app for the first time on your phone, you must Allow Location Access when prompted by Safari or Chrome.

    💡 Pro-Tip: On iOS (Safari) or Android (Chrome), tap the Share / Menu button and select "Add to Home Screen". This installs the app as a Progressive Web App (PWA), removing the browser URL bar and giving you a distraction-free, native app experience on your phone.

📂 Exported Data Structure

When you export your data to a CSV file, it is structured as follows for easy parsing by accounting systems or Microsoft Excel:
Date	Stop #	Stop Name	Time	Latitude	Longitude	Tags	Status
2026-06-21	1	Head Office	09:00 AM	51.5074	-0.1278	Internal; Admin	Finalised
2026-06-21	2	Client Site A	11:30 AM	51.5152	-0.1419	Client Work; Travel	Finalised
🛡️ License

This project is open-source and free to adapt for personal or internal corporate use.
