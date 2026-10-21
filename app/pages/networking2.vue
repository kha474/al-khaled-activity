<template>
  <div class="detail-container">
    <!-- Link to go back to the main page -->
    <NuxtLink to="/" class="back-link">← Back to Activities</NuxtLink>

    <!-- The Image -->
    <img src="/images/networking.jpg" alt="Networking & Cabling" class="detail-img" />

    <!-- The Details -->
    <div class="details-content">
      <h1>Networking & Cabling</h1>
      <p>
        In this hands-on activity, students focus on the physical layer of computer networking. They learn how to properly handle, terminate, and test network cables (such as Cat5e or Cat6 Ethernet cables).
      </p>
      <p>
        Working in pairs, students practice crimping connectors onto cables and ensuring the correct wiring standard (like T568A or T568B) is followed. This practical skill is fundamental for setting up Local Area Networks (LANs) and ensuring reliable data transmission between devices.
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
  object-fit: contain; /* Keeps the whole image visible */
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