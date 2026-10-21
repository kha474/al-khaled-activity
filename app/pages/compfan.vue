<template>
  <div class="detail-container">
    <!-- Link to go back to the main page -->
    <NuxtLink to="/" class="back-link">← Back to Activities</NuxtLink>

    <!-- The Image -->
    <img src="/images/compfan.jpg" alt="Computer Fan Maintenance" class="detail-img" />

    <!-- The Details -->
    <div class="details-content">
      <h1>Computer Fan Maintenance</h1>
      <p>
        In this activity, students learn the critical skill of computer cooling maintenance. Over time, dust and debris build up inside computer cases, particularly on the CPU heatsink and cooling fans. 
      </p>
      <p>
        Using tools like compressed air, brushes, and cleaning cloths, students carefully remove the dust build-up. Proper fan maintenance is essential to prevent the computer from overheating, which can lead to sluggish performance or permanent damage to internal hardware like the processor.
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