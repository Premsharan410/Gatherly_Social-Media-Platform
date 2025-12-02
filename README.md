<h1 align="center">✨ Gatherly</h1>
<h3 align="center">A Modern Full-Stack Social Media Platform</h3>

<div align="center">
  <p><strong>Where People Come Together</strong></p>
  <p>Built with 
    <code>React</code> · <code>Node.js</code> · <code>Express</code> · 
    <code>PostgreSQL</code> · <code>Supabase</code> · <code>Socket.IO</code>
  </p>
  <br/>
  <p>🔗 <strong>Live Demo:</strong> <a href="https://gatherly-lemon.vercel.app/">https://gatherly-lemon.vercel.app/</a></p>
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
  <li>Images uploaded </li>
  <li>View personal feed </li>
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
  <li>Real-time updates </li>
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
  <li>PostgreSQL </li>
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
    ├── middleware/
    ├── db.js
    └── server.js
</pre>

<hr/>


<h2>📜 License</h2>
<p>This project is licensed under the <strong>MIT License</strong>.</p
