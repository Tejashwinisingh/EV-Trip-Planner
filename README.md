🚀 Step 1: Start MongoDB

Make sure MongoDB is running.

If you're using MongoDB Atlas:

Check that your connection string in .env is correct.

If you're using local MongoDB:

mongod
🚀 Step 2: Run Backend

Open a terminal in the backend folder:

cd backend
npm install
npm start

or if your package.json uses nodemon:

npm run dev

You should see something like:

Server running on port 5000
MongoDB Connected
🚀 Step 3: Run Frontend

Open another terminal:

cd frontend
npm install
npm start

or

npm run dev

Depending on whether you use:

Create React App → npm start
Vite → npm run dev
🚀 Step 4: Open Browser

Usually:

Frontend: http://localhost:3000

or

Frontend: http://localhost:5173

Backend:

http://localhost:5000
