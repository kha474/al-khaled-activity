<template>
  <div class="container">
    <h1 class="title">Al Khaled Activities</h1>
    <p class="subtitle">Click on an image to learn more.</p>

    <div class="grid">
      <!-- 1. Classroom -->
      <NuxtLink to="/classroom" class="card">
        <img src="/images/classroom.jpg" alt="Classroom" />
        <h2>Classroom & Instruction</h2>
      </NuxtLink>

      <!-- 2. Computer Fan -->
      <NuxtLink to="/compfan" class="card">
        <img src="/images/compfan.jpg" alt="Computer Fan" />
        <h2>Computer Fan Maintenance</h2>
      </NuxtLink>

      <!-- 3. Computer Hardware -->
      <NuxtLink to="/comphardware" class="card">
        <img src="/images/comphardware.jpg" alt="Computer Hardware" />
        <h2>Computer Hardware</h2>
      </NuxtLink>

      <!-- 4. Hardware -->
      <NuxtLink to="/hardware" class="card">
        <img src="/images/hardware.jpg" alt="Hardware" />
        <h2>Hardware Assembly</h2>
      </NuxtLink>

      <!-- 5. Installation -->
      <NuxtLink to="/installation" class="card">
        <img src="/images/installation.jpg" alt="Installation" />
        <h2>Software Installation</h2>
      </NuxtLink>

      <!-- 6. ISP -->
      <NuxtLink to="/isp" class="card">
        <img src="/images/isp.jpg" alt="ISP" />
        <h2>Internet Service Provider Setup</h2>
      </NuxtLink>

      <!-- 7. Maintenance -->
      <NuxtLink to="/maintenance" class="card">
        <img src="/images/maintenance.jpg" alt="Maintenance" />
        <h2>System Maintenance</h2>
      </NuxtLink>

      <!-- 8. Network Icons -->
      <NuxtLink to="/networkicons" class="card">
        <img src="/images/networkicons.jpg" alt="Network Icons" />
        <h2>Network Diagramming</h2>
      </NuxtLink>

      <!-- 9. Networking -->
      <NuxtLink to="/networking" class="card">
        <img src="/images/networking.jpg" alt="Networking" />
        <h2>Networking & Cabling</h2>
      </NuxtLink>

      <!-- 10. Networking 2 -->
      <NuxtLink to="/networking2" class="card">
        <img src="/images/networking2.jpg" alt="Networking 2" />
        <h2>Advanced Networking</h2>
      </NuxtLink>

      <!-- 11. Switch -->
      <NuxtLink to="/switch" class="card">
        <img src="/images/switch.jpg" alt="Switch" />
        <h2>Network Switch Configuration</h2>
      </NuxtLink>
      <!-- 12.logo -->
      <NuxtLink to="/installation" class="card">
        <img src="/images/logo.png" alt="logo" />
        <h2>logo</h2>
      </NuxtLink>
    </div>
  </div>
</template>
<style scoped>
.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
  font-family: system-ui, sans-serif;
}
.title {
  text-align: center;
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
  color: #333;
}
.subtitle {
  text-align: center;
  color: #666;
  margin-bottom: 3rem;
}
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}
.card {
  text-decoration: none;
  color: inherit;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  display: block;
  background: white;
}
.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 15px rgba(0,0,0,0.2);
}
.card img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  display: block;
}
.card h2 {
  text-align: center;
  padding: 1.5rem 1rem;
  margin: 0;
  font-size: 1.2rem;
  background-color: #f8f9fa;
  color: #333;
}
</style>