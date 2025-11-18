# StreamSavvy – Online Streaming Platform

StreamSavvy is a web-based OTT streaming application that allows users to browse movies, view details, manage a personal watchlist, and explore content using search and category filters. The project uses JSON-Server as a temporary backend and is designed for future expansion with Node.js and MongoDB.


## Features

- **Dynamic Content Browsing:** Carousels, banners, detailed pages, and interactive UI elements.
- **Watchlist Management:** Add, update, and remove titles using JSON-Server.
- **Search & Filtering:** Explore movies by title or genre.
- **Client-Side Routing:** Smooth page transitions and navigation.
- **Responsive UI:** Optimized layout for mobile and desktop.
- **Future Backend Integration:** Planned migration to Node.js and MongoDB.

## Tech Stack

**Frontend**
- React  
- Vite  
- JavaScript (ES6+)  
- CSS  

**Backend (Temporary)**
- JSON-Server

**Future Backend**
- Node.js  
- Express  
- MongoDB  

## Project Structure

```bash
StreamSavvy/
│── public/
│── src/
│ ├── components/
│ ├── pages/
│ ├── services/
│ ├── utils/
│ ├── App.jsx
│ ├── main.jsx
│── db.json
│── index.html
│── package.json
│── vite.config.js
```

## Environment Variables

To use APIs like TMDB, create a `.env` file:

``
VITE_TMDB_API_KEY=your_api_key
``


## Future Improvements

Backend integration (Node.js + MongoDB)

User authentication with JWT

API-driven dynamic content

Watch history & recommendations

Production deployment (Vercel/Netlify)

