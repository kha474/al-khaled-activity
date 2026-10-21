<template>
  <div class="detail-container">
    <!-- Link to go back to the main page -->
    <NuxtLink to="/" class="back-link">← Back to Activities</NuxtLink>

    <!-- The Image -->
    <img src="/images/maintenance.jpg" alt="PC Maintenance" class="detail-img" />

    <!-- The Details -->
    <div class="details-content">
      <h1>PC Maintenance & Repair</h1>
      <p>
        In this hands-on activity, students gather around an open computer chassis to diagnose and repair hardware issues. Working closely together, they inspect internal components, check cable connections, and replace faulty parts.
      </p>
      <p>
        Regular maintenance and troubleshooting are vital skills for any IT professional. This collaborative environment allows students to share knowledge, learn from one another, and gain confidence in safely handling sensitive internal electronics.
      </p>
    </div>
  </div>
</template>

<style scoped>
.detail-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
  font-family: system-ui, sans-serif;
}

.back-link {
  display: inline-block;
  margin-bottom: 1.5rem;
  color: #0066cc;
  text-decoration: none;
  font-weight: bold;
}

.back-link:hover {
  text-decoration: underline;
}

.detail-img {
  width: 100%;
  max-height: 500px;
  object-fit: contain; /* 'contain' ensures the whole image is visible without cropping */
  background-color: #f0f0f0; 
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  margin-bottom: 2rem;
}

.details-content h1 {
  font-size: 2.2rem;
  color: #333;
  margin-bottom: 1rem;
}

.details-content p {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #555;
  margin-bottom: 1rem;
}
</style>