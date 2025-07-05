# URL Shortener Application

This is a full-featured **React + Material UI** based URL Shortener application developed as part of the campus recruitment challenge.

Check out the Live Site : [https://221401080.vercel.app/](https://221401080.vercel.app/)
---
## Tech Stack

- **React** (Functional components, Hooks)
- **Material UI (MUI)** for styling (no external CSS libraries used)
- **Axios** for API communication
- `localStorage` for storing auth, stats, and links

---
## How to Run Locally

1. Clone the repo  
   ```bash
   git clone https://github.com/Sakthisree-26/221401080.git
   cd 221401080
   ```

2. Install dependencies  
   ```bash
   npm install
   ```

3. Start the app  
   ```bash
   npm start
   ```

4. Navigate to:
   - `/register` for registration + authentication
   - `/` for URL shortener
   - `/stats` for statistics dashboard

## Navigation 

Visit the following routes after running the project:

- **Registration & Auth:** [http://localhost:3000/register](http://localhost:3000/register)
  - Register with your email, roll number, and access code , Automatically retrieves `clientID`, `clientSecret`, and `access_token`
  
- **URL Shortener (Home):** [http://localhost:3000/](http://localhost:3000/)
  - Shorten up to 5 URLs with optional custom code and expiry

- **Statistics Dashboard:** [http://localhost:3000/stats](http://localhost:3000/stats)
  - View short link history, click analytics, and expiry info


---

## Features

- Shorten up to **5 URLs concurrently**
- Supports **custom shortcodes** (optional)
- Allows setting **validity period** in minutes (optional)
- Displays shortened links with:
  - Original URL
  - Short URL
  - Expiry time
- Complete **client-side validation** and error handling
- Dedicated **Statistics Page** showing:
  - Total click count per short link
  - Click timestamp, referrer, and location (simulated)
-  All data persisted in `localStorage` for demonstration

---



## Project Structure

```
src/
├── components/
│   ├── RegisterAndAuth.jsx
│   ├── StatisticsPage.jsx
│   └── [Other UI Components]
├── App.js / index.js
```

---







