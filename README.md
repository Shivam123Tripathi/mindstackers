mindstackers
here I am going to share a web application of skill swap 
KaryaX

Problem Statement 1:-   
Skill Swap Platform 
Overview: 
Develop a Skill Swap Platform — a mini application that enables users to list their skills and 
request others in return 
Features: 
Basic info: Name, location (optional), profile photo (optional) 
List of skills offered 
List of skills wanted 
Availability (e.g., weekends, evenings) 
User can make their profile public or private. 
Users can browse or search others by skill (e.g., “Photoshop” or “Excel”) 
Request & Accept Swaps: 
○ Accept or reject swap offers 
○ Show current and pending swap requests 
Ratings or feedback after a swap 
The user is also able to delete the swap request if it is not accepted. 
Admin Role 
● Reject inappropriate or spammy skill descriptions. 
● Ban users who violate platform policies. 
● Monitor pending, accepted, or cancelled swaps. 
● Send platform-wide messages (e.g., feature updates, downtime alerts). 
● Download reports of user activity, feedback logs, and swap stats. 
Mockup - https://link.excalidraw.com/l/65VNwvy7c4X/8bM86GXnnUN

Tech Stack Used

🔧 Frontend (React.js)
React.js – for building UI components (screens 1–6)

React Router – for navigation between pages (/login, /profile, etc.)

CSS – for styling (normal CSS, not Tailwind)

React Icons – for adding icons (like star, user, search)

🖥️ Backend (Node.js + Express.js)
Express.js – for creating REST APIs (/api/users, /api/login, etc.)

CORS & dotenv – to handle cross-origin and environment config

Nodemon – for live backend reload during development

🗄️ Database (MongoDB + Mongoose)
MongoDB – to store user profiles, requests, login data

Mongoose – for schema design and interacting with MongoDB easily

📦 Other Tools
Postman – to test backend APIs (GET, POST, etc.)

MongoDB Atlas – if using cloud database

VS Code – for writing and managing code
