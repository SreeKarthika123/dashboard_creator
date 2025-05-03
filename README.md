Project Implemenatation:
 1. User Authentication System (JWT-based)
Implemented user register/login functionality using JSON Web Tokens.
Used role-based access (User/Admin).
Stored user data in MongoDB using Mongoose models.
2.Credit System
Users earn credits by logging in daily.
Users earn credits by interacting with the feed (save/share/report).
Created an admin route to view and update credits manually.
3.Feed Aggregator
Integrated public APIs (e.g., Reddit, simulated Twitter) to fetch feed posts.
Parsed and displayed posts on the frontend in a scrollable UI.
Enabled users to:
Save posts to their profile.
Share posts (simulate with copy link).
Report posts (flag as inappropriate).
4.Dashboards
User Dashboard: shows profile info, earned credits, saved posts, and recent activity.
Admin Dashboard:
Shows list of users and their credits.
Displays system-wide engagement stats (e.g., number of reports or saved posts).
Ability to edit user credits and Delete  User.
Tech Stack
Frontend: React.js (with Axios, Context API for auth, React Router)
Backend: Node.js + Express.js
Database: MongoDB with Mongoose ODM
Authentication: JWT-based token system

Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/creator-dashboard.git
cd creator-dashboard
2.Backend Setup
cd backend
npm install
PORT=5000
MONGODB_URI=mongodb://localhost:27017/creatorDashboard------------>.env file
JWT_SECRET=your_jwt_secret
Start Backend Server
node server.js
Frontend Setup
cd ../frontend
npm install
npm start


