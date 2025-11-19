# GameHaven Backend

Backend for the GameHaven game library application.

## Setup

1. Clone the repository and go to the backend folder:
```bash
git clone <repository-url>
cd backend

2. Install dependencies:
npm install

3. Create a .env file with your MongoDB connection string:
MONGODB_URI=mongodb+srv://jani:nico@gamehaven-cluster.q5fgbly.mongodb.net/?retryWrites=true&w=majority&appName=GameHaven-Cluster
PORT=3001

4. Run the server:
npm run dev
The backend runs on http://localhost:3001.

API Endpoints

GET /games – fetch all games

POST /games – add a new game

PUT /games/:id – update a game

DELETE /games/:id – delete a game