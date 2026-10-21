<template>
  <div class="detail-container">
    <!-- Link to go back to the main page -->
    <NuxtLink to="/" class="back-link">← Back to Activities</NuxtLink>

    <!-- The Image -->
    <img src="/images/switch.jpg" alt="Network Switch Configuration" class="detail-img" />

    <!-- The Details -->
    <div class="details-content">
      <h1>Network Switch Configuration</h1>
      <p>
        In this networking lab activity, students get hands-on experience connecting devices to a network switch. The image shows a switch populated with multiple Ethernet cables, simulating a real-world Local Area Network (LAN) environment.
      </p>
      <p>
        Students practice plugging in cables, observing the indicator lights (LEDs) to verify connectivity, and learning how a switch intelligently forwards data packets to the correct destination device. Understanding how to physically connect and manage a switch is a core skill for network administration and IT support.
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
  object-fit: contain; /* 'contain' ensures the whole image is visible */
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