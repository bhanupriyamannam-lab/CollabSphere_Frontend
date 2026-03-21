<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sidebar Menu</title>
  <link rel="stylesheet" href="homepage.css">
  
</head>
<body>

<nav class="sidebar close">
  <header>
    <div class="image-text">
      <span class="name">Dashboard</span>
    </div>

    <i class="toggle">☰</i>
  </header>

  <div class="menu-bar">
    <ul class="menu">
      <li><a href="#">🏠 Home</a></li>
      <li><a href="#">👤 Profile</a></li>
      <li><a href="#">🔔 Notifications</a></li>
      <li><a href="#">🌐 My Network</a></li>
      <li><a href="#">👥 Team</a></li>
      <li><a href="#">📁 Projects</a></li>
      <li><a href="#">📋 Tasks</a></li>
      <li><a href="#">💬 Chat</a></li>
      <li><a href="#">📅 Calendar</a></li>
      <li><a href="#">📄 Files</a></li>
      <li><a href="#">📊 Analytics</a></li>
      <li><a href="#">⚙️ Settings</a></li>
    </ul>

    <div class="bottom-content">
    </div>
  </div>
</nav>

<button class="top-right-logout">Logout</button>

<div class="mode-switch-fixed">
  <span class="mode-text">Dark mode</span>
  <div class="toggle-switch"></div>
</div>

<section class="home">
  <h1>Collaboration Dashboard</h1>

  <div class="dashboard-content">
    <div class="portfolio-section">
      <h2>Portfolio Overview</h2>
      <p>Track your key projects, partners, and showcase your team’s achievements in CollabSphere.</p>
      <div class="portfolio-cards">
        <div class="portfolio-card">
          <img src="https://image.shutterstock.com/image-illustration/abstract-blue-technology-background-digital-260nw-2620170795.jpg" alt="Major Projects">
          <h3>Major Projects</h3>
          <p>24 Active</p>
        </div>
        <div class="portfolio-card">
          <img src="https://images.unsplash.com/photo-1518779578993-ec3579fee39f?auto=format&fit=crop&w=400&q=80" alt="Top Clients">
          <h3>Top Clients</h3>
          <p>12 Engagements</p>
        </div>
        <div class="portfolio-card">
          <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?auto=format&fit=crop&w=400&q=80" alt="Delivered Value">
          <h3>Delivered Value</h3>
          <p>76 Reports</p>
        </div>
        <div class="portfolio-card">
          <img src="">
          <h3>Milestones</h3>
          <p>18 Achieved</p>
        </div>
      </div>
    </div>
  </div>
</section>

<script src="homepage.js"></script>

</body>
</html>
