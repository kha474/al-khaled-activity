<template>
  <div>
    <!-- Professional Header -->
    <header class="main-header">
      <div class="header-content">
        <!-- Logo area -->
        <NuxtLink to="/" class="logo-link">Al khaled</NuxtLink>
        <!-- Navigation Links -->
        <nav class="nav-links">
          <NuxtLink to="/">Home</NuxtLink>
          <NuxtLink to="/about">About</NuxtLink>
        </nav>
      </div>
    </header>

    <!-- This is where your pages will load -->
    <main class="main-content">
      <NuxtPage />
    </main>
  </div>
</template>

<style>
/* Global styles */
body {
  margin: 0;
  padding: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f4f6f8; /* Light grey background for the whole site */
}

/* Header Styling */
.main-header {
  background-color: #0b1021; /* Very dark navy blue to match your logo's background */
  padding: 0.5rem 0;
  box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  border-bottom: 2px solid #d4af37; /* Gold bottom border */
}

.header-content {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

/* Logo Image Styling */
.logo-link {
  display: flex;
  align-items: center;
}

.site-logo {
  height: 70px; /* Adjust this to make the logo bigger or smaller */
  width: auto;
  border-radius: 50%; /* This makes the image circular */
  transition: transform 0.3s ease;
}

.site-logo:hover {
  transform: scale(1.05); /* Slight zoom effect when hovering over the logo */
}

/* Navigation Links */
.nav-links {
  display: flex;
  gap: 2rem;
}

.nav-links a {
  color: #cbd5e0;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1rem;
  letter-spacing: 1px;
  transition: color 0.3s ease;
}

.nav-links a:hover {
  color: #d4af37; /* Gold hover effect */
}

/* Main Content Area */
.main-content {
  min-height: 80vh;
  padding-bottom: 2rem;
}
</style>