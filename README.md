```
# Pool Game Tracker Web Application

A simple web app to help pool players record game results, track their statistics, find nearby pool halls, and manage user profiles. Built with HTML, CSS, JavaScript, Chart.js, and Google Maps API for location services. User data is stored locally for demo purposes.

---

## Features Implemented

- **User Registration & Login:** Create accounts and sign in to manage personal data.
- **Profile Management:** View and update user profile info.
- **Game Recording:** Input details of each game (opponent, win/loss).
- **Statistics Dashboard:** Visualize wins/losses and winning percentage with charts.
- **Location Services:** Find nearby pool halls using Google Maps API.
- **Basic Navigation:** Switch between dashboard, record, stats, and location views.
- **Local Data Storage:** User data persists across sessions via localStorage.

---

## How to Use

1. **Register or Login:**
   - Click "Register" to create a new user.
   - Enter your username and submit.
   - Or, click "Login" and enter your existing username.

2. **Dashboard:**
   - View your overall stats and profile info.
   - Recorded game results update your stats and charts.

3. **Record a Game:**
   - Fill in opponent's name and whether you won.
   - Submit to save results and update stats.

4. **View Statistics:**
   - See pie chart of wins vs losses.
   - See bar chart of winning percentage.

5. **Find Nearby Pool Halls:**
   - Enter your location.
   - Click "Find Halls" to see nearby pool halls on the map.

6. **Logout:**
   - Click "Logout" to end your session.

---

## Technologies & APIs Used

- **HTML & CSS** for layout and styling
- **JavaScript** for logic and interactivity
- **Chart.js** for data visualization
- **Google Maps JavaScript API** for location search and nearby place search
- **localStorage** for demo user data persistence

---

## Setup Instructions

1. **Get a Google Maps API Key:**
   - Visit [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project and enable "Maps JavaScript API" and "Places API."
   - Generate an API key.
   - Replace `'YOUR_API_KEY'` in the HTML with your key.

2. **Run the app:**
   - Copy the provided HTML, CSS, and JS code into [CodePen](https://codepen.io/), or run locally by creating `.html`, `.css`, and `.js` files and opening the HTML in your browser.

---

## Limitations & Next Steps

- **Data Storage:** Uses localStorage; data will be lost if browser cache is cleared.
- **Security:** No real authentication; suitable just for demo.
- **Features:** Basic version; can be expanded with user profiles, match scheduling, chat, leaderboards, and more.
- **API Key:** Remember to restrict your Google API key for security.

---

## Future Enhancements

- Implement user registration with backend database.
- Add real-time chat/messaging.
- Create match scheduling and calendar features.
- Integrate payment gateway for premium features.
- Add social sharing and community forums.
- Implement advanced analytics and performance tracking.
- Support multiple languages and themes.

---

## License

This project is a demo application for educational purposes. Feel free to fork, modify, and expand!

---
---

Would you like me to generate a markdown version you can directly copy, or customize it further?
