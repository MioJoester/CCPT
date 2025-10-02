
## CCPT - Bitcoin Tracker

Overview

CCPT is a lightweight, real-time Bitcoin price tracker that leverages the Binance public API. It provides live price updates, a leaderboard showcasing the top 10 cryptocurrencies by market cap, and interactive charts for visualizing price trends. Built as a static web app, it’s ideal for crypto enthusiasts or developers exploring API-driven projects.


## Features





Live Price Updates: Real-time Bitcoin price tracking via Binance API.



Market Leaderboard: Displays top 10 cryptocurrencies by market capitalization.



Interactive Charts: Dynamic visualizations for analyzing price trends.



Responsive Design: Modern, user-friendly UI optimized for desktop and mobile.

Tech Stack





Frontend: HTML5, CSS3, JavaScript (vanilla or lightweight libraries)



API: Binance Spot API (public endpoints, no authentication required)



Styling: Custom CSS with flexbox/grid layouts and dark mode support



Deployment: Static hosting (e.g., Vercel, Netlify, GitHub Pages)

 
## Getting Started

Prerequisites





Modern web browser (Chrome, Firefox, Edge, etc.)



Internet connection for API calls



No external dependencies or build tools required

Running Locally





Clone the repository:

```
git clone https://github.com/MioJoester/CCPT.git
```


Navigate to the project folder:

```
cd CCPT
```


Open index.html in a browser:





Double-click index.html, or



Use a local server: ```npx serve``` for live reload.



The app fetches live data from Binance API automatically.

## Deployment





Deploy to Vercel, Netlify, or GitHub Pages by uploading the repo.



No server-side setup needed—static files work out-of-the-box.

File Structure


```
CCPT/
├── index.html   # Main page with UI and API logic
├── style.css    # Custom styles for layout and visuals

```
## Notes





API Limits: Binance public API allows 1,200 requests/min. Monitor for heavy usage.



Extensibility: Add multi-currency support or WebSocket streaming for enhanced real-time updates.



Check out the project demo [here](miojoester.github.io/CCPT/)



Contact

Created by MioJoester. For questions or feedback, open a GitHub Issue.
