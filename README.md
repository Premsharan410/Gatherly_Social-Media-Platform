<h1 align="center">✨ Gatherly</h1>
<h3 align="center">A Modern Full-Stack Social Media Platform</h3>

<div align="center">
  <p><strong>Create. Connect. Chat. Explore.</strong></p>
  <p>Built with 
    <code>React</code> · <code>Node.js</code> · <code>Express</code> · 
    <code>PostgreSQL</code> · <code>Supabase</code> · <code>Socket.IO</code>
  </p>
  <br/>
  <p>🔗 <strong>Live Demo:</strong> <a href="https://gatherly-lemon.vercel.app/">https://gatherly-lemon.vercel.app/</a></p>
  <p>🔗 <strong>Backend API:</strong> <a href="https://gatherly-backend-6kfc.onrender.com/">https://gatherly-backend-6kfc.onrender.com/</a></p>
</div>

<hr/>

<h2>⭐ Overview</h2>
<p>
Gatherly is a complete social media platform featuring user authentication, posting with images,
followers, real-time chat, notifications, and profile management.  
Images are stored securely using <strong>Supabase Storage</strong> and real-time features run on <strong>Socket.IO</strong>.
<br/>Frontend is deployed on <strong>Vercel</strong> and backend on <strong>Render</strong>.
</p>

<hr/>

<h2>🚀 Features</h2>

<h3>👤 User Accounts</h3>
<ul>
  <li>Signup / Login with JWT</li>
  <li>Secure password hashing (bcrypt)</li>
  <li>Edit profile info (name, username, bio)</li>
  <li>Upload profile & cover photos</li>
  <li>Public profiles via username pages</li>
</ul>

<h3>📝 Posts & Feed</h3>
<ul>
  <li>Create posts with <strong>text + image</strong></li>
  <li>Images uploaded to Supabase Storage</li>
  <li>View personal feed & user feed</li>
</ul>

<h3>👥 Followers & Explore</h3>
<ul>
  <li>Follow / Unfollow users</li>
  <li>Suggested users list</li>
  <li>Followers & Following list</li>
  <li>Follow status checks</li>
</ul>

<h3>🔔 Notifications</h3>
<ul>
  <li>Instant follow notifications</li>
  <li>Unread notification count</li>
  <li>Mark all as read</li>
  <li>Delete single or all notifications</li>
  <li>Real-time updates (Socket.IO)</li>
</ul>

<h3>💬 Real-Time Chat</h3>
<ul>
  <li>1-to-1 real time messaging</li>
  <li>Delivered instantly via Socket.IO</li>
  <li>No page reload required</li>
  <li>Auto-update chat list</li>
</ul>

<h3>🔍 Search</h3>
<ul>
  <li>Search users by username or name</li>
  <li>Profile photos inside search results</li>
</ul>

<h3>🎨 UI / UX</h3>
<ul>
  <li>Fully responsive layout</li>
  <li>Modern and clean design</li>
  <li>Light/Dark theme support</li>
</ul>

<hr/>

<h2>🛠️ Tech Stack</h2>

<h3>Frontend</h3>
<ul>
  <li>React.js</li>
  <li>React Router</li>
  <li>Axios</li>
  <li>Context API (Theme, Notifications, Chat, Toast)</li>
  <li>Vite</li>
  <li>Vercel Deployment</li>
</ul>

<h3>Backend</h3>
<ul>
  <li>Node.js + Express</li>
  <li>PostgreSQL (Supabase)</li>
  <li>Supabase Storage</li>
  <li>JWT Authentication</li>
  <li>Multer (Memory Uploads)</li>
  <li>Socket.IO</li>
  <li>Render Deployment</li>
</ul>

<hr/>

<h2>📁 Project Structure</h2>

<pre>
Gatherly/
│
├── Frontend/
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
└── Backend/
    ├── routes/
    ├── middleware/
    ├── supabaseClient.js
    ├── db.js
    └── server.js
</pre>

<hr/>

<h2>⚙️ Environment Variables</h2>

<h3>Frontend (.env)</h3>
<pre>
VITE_BACKEND_URL=https://your-backend-url.onrender.com
</pre>

<h3>Backend (.env)</h3>
<pre>
DATABASE_URL=postgresql://...
JWT_SECRET=your_jwt_secret
SUPABASE_URL=https://xxxx.supabase.co
SUPABASE_ANON_KEY=xxxx
SUPABASE_SERVICE_ROLE_KEY=xxxx
FRONTEND_URL=https://your-frontend-url.vercel.app
</pre>

<hr/>

<h2>▶️ Run Locally</h2>

<h3>Backend</h3>
<pre>
cd Backend
npm install
npm start
</pre>

<h3>Frontend</h3>
<pre>
cd Frontend
npm install
npm run dev
</pre>

<hr/>

<h2>🚀 Deployment</h2>

<h3>Frontend – Vercel</h3>
<ul>
  <li>Framework: Vite</li>
  <li>Build: <code>npm run build</code></li>
  <li>Output: <code>dist</code></li>
</ul>

<h3>Backend – Render</h3>
<ul>
  <li>Build: <code>npm install</code></li>
  <li>Start: <code>node server.js</code></li>
  <li>Add environment variables in Render Dashboard</li>
</ul>

<hr/>

<h2>🧪 Quick Test Routes</h2>
<pre>
GET /apitest
GET /db-test
</pre>

<hr/>

<h2>📜 License</h2>
<p>This project is licensed under the <strong>MIT License</strong>.</p>
