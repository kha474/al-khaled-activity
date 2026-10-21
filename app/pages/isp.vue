<template>
  <div class="detail-container">
    <!-- Link to go back to the main page -->
    <NuxtLink to="/" class="back-link">← Back to Activities</NuxtLink>

    <!-- The Image -->
    <img src="/images/isp.jpg" alt="What is IPS?" class="detail-img" />

    <!-- The Details -->
    <div class="details-content">
      <h1>Understanding IPS (Intrusion Prevention Systems)</h1>
      <p>
        In this networking and cybersecurity activity, students study the architecture of an Intrusion Prevention System (IPS). The diagram illustrates how an IPS is deployed within a network to actively monitor and block malicious traffic.
      </p>
      <p>
        As shown in the network topology, the IPS sits inline between the internet router/firewall and the internal network switches. This strategic placement allows it to inspect incoming and outgoing data packets in real-time. If it detects suspicious activity or a known attack signature, it can immediately drop the malicious packets, protecting the internal subnets and servers behind it.
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
  object-fit: contain; /* Using 'contain' here because it's a diagram, so it doesn't get cropped */
  background-color: #f0f0f0; /* Optional: adds a background for the diagram */
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