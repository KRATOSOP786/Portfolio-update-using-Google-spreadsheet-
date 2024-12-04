# Portfolio-update-using-Google-spreadsheet-
# React Portfolio Viewer

A simple portfolio viewer built with React.js that fetches data from a Google Sheets API. The project demonstrates how to use React with external APIs to dynamically render data for a portfolio website.

## Features

- Fetches data from a Google Sheet using a NoCode API.
- Displays portfolio items, including titles, descriptions, images, and videos.
- Responsive and visually appealing grid layout for portfolio items.


Code Overview
- The project uses the following tools and libraries:

- React.js: For building the UI.
- Axios: For making API requests.
- Google Sheets API (via NoCode): To store and fetch portfolio data.

Key File: Portfolio.js
This component:Fetches data from the API using axios in a useEffect hook.
Maps the data to render a grid of portfolio items.
Dynamically supports images and embedded videos (YouTube/Vimeo).

- Deployment
- To deploy this project:
Build the project:
bash
Copy code
npm run build
Deploy the build folder to any static hosting platform like Vercel, Netlify, or GitHub Pages.
Contributions are welcome! Feel free to submit a pull request or open an issue.
