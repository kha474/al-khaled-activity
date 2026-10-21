<template>
  <div class="detail-container">
    <!-- Link to go back to the main page -->
    <NuxtLink to="/" class="back-link">← Back to Activities</NuxtLink>

    <!-- The Image -->
    <img src="/images/classroom.jpg" alt="Classroom & Instruction" class="detail-img" />

    <!-- The Details -->
    <div class="details-content">
      <h1>Classroom & Instruction</h1>
      <p>
        In this practical session, students gather around the workbench to get hands-on experience with computer hardware. 
        Under the guidance of the instructor, they are learning how to safely open a computer case, identify internal components, 
        and understand how the various parts work together. This practical approach ensures students are ready for real-world IT maintenance.
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
}
</style>