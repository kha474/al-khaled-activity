<template>
  <div class="detail-container">
    <!-- Link to go back to the main page -->
    <NuxtLink to="/" class="back-link">← Back to Activities</NuxtLink>

    <!-- The Image -->
    <img src="/images/networkicons.jpg" alt="Network Icons Reference Guide" class="detail-img" />

    <!-- The Details -->
    <div class="details-content">
      <h1>Network Icon Reference Guide</h1>
      <p>
        A crucial part of networking and cybersecurity is being able to read and understand network topology diagrams. This activity focuses on learning the standard symbols used to represent different network devices.
      </p>
      <p>
        Students study this reference chart to identify key components such as routers, switches, firewalls, load balancers, and security appliances like Intrusion Detection Systems (IDS). Mastering these icons allows technicians to quickly interpret how a network is structured and how data flows securely from one point to another.
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
  max-height: 600px;
  object-fit: contain; /* 'contain' ensures the diagram is not cropped */
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