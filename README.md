# Instructions

1. `npm install` && `npm run dev`
2. Navigate to `http://localhost:5173/main.js`
3. Notice the lack of env var handling
4. Navigate to `http://localhost:5173`, then back to `http://localhost:5173/main.js`
5. Notice the inserted env var handling
6. Navigate to `http://localhost:5173//main.js`
7. Notice the lack of env var handling, despite resolving to the same asset
