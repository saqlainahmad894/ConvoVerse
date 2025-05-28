1. Clone the repository:
git clone [https://github.com/sofiyasiddique119/ConvoVerse.git](https://github.com/saqlainahmad894/ConvoVerse.git)
2. Create .env files in both backend/ and frontend/ as per the provided configuration:
▪ backend/.env
• PORT=5001
• MONGO_URI=your_mongo_uri
• STEAM_API_KEY=your_steam_api_key
• STEAM_API_SECRET=your_steam_api_secret
• JWT_SECRET_KEY=your_jwt_secret
• NODE_ENV=development
▪ frontend/.env
• VITE_STREAM_API_KEY=your_stream_api_key
3. Run the backend server:
• cd backend
• npm install
• npm run dev
4. Run the frontend application:
• cd ../frontend
• npm run dev
5. The application will now be available at:
http://localhost:5173
Make sure MongoDB and internet access (for Stream API) are properly configured before
running the app.
