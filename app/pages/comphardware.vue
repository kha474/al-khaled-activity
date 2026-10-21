<template>
  <div class="detail-container">
    <!-- Link to go back to the main page -->
    <NuxtLink to="/" class="back-link">← Back to Activities</NuxtLink>

    <!-- The Image -->
    <img src="/images/comphardware.jpg" alt="Computer Hardware" class="detail-img" />

    <!-- The Details -->
    <div class="details-content">
      <h1>Computer Hardware</h1>
      <p>
        In this activity, students explore the internal components that make up a desktop computer. By opening the case, they get a firsthand look at how the motherboard, processor, memory (RAM), and power supply are connected.
      </p>
      <p>
        Understanding the layout of internal hardware is essential for troubleshooting, upgrading, and building computers. Students learn to identify different types of cables, understand how power is distributed, and see how the cooling system keeps the components running efficiently.
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
  object-fit: cover;
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