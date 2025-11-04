# InfoHub – Full-Stack Web Application
A single-page productivity application built for the **ByteXL Full-Stack Coding Challenge**.  
InfoHub brings three everyday utilities into one clean interface:

- **Real-Time Weather Information**
- **Currency Converter (INR → USD & EUR)**
- **Motivational Quote Generator**

This project demonstrates full-stack development skills including frontend UI, backend API creation, async data fetching, error handling, and deployment.

##  Features

| Module | Description |
|--------|------------|
Weather | Fetch live weather based on city (temperature, condition, icon) |
Currency Converter | Convert INR to USD & EUR in real-time |
Quotes | Generate a new motivational quote on demand |
SPA Navigation | Tab-based UI without page reload |
Error Handling | Friendly error messages for failed API calls |
Loading States | Visual loading indicators |

## Tech Stack

### Frontend
- React (Vite)
- Axios / Fetch API
- CSS (or Tailwind, if used)

### Backend
- Node.js + Express
- Axios for upstream API calls

### External APIs
- **OpenWeather API** (weather)
- **Frankfurter API** (currency rates)
- **Quotable API** (quotes) / or local quote array

### Deployment
- Frontend: **Vercel**
- Backend: **Render** (or Vercel Serverless)

### Folder Structure
InfoHub/
├── client/            # React Frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── WeatherModule.jsx
│   │   │   ├── CurrencyConverter.jsx
│   │   │   └── QuoteGenerator.jsx
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
└── server/            # Node/Express Backend
    ├── server.js
    ├── .env
    └── package.json
