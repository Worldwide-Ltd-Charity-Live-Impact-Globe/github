# 🌍 Worldwide Ltd Charity Live Impact Globe  
**Innovation. Hope. Global Change.**

![Worldwide Ltd Charity Live Impact Globe Logo](https://github.com/Worldwide-Ltd-Charity-Live-Impact-Globe/github/blob/main/logo.png)

[![🏆 Winners Registered](https://img.shields.io/badge/Winners%20Registered-Live%20Feed-success?style=for-the-badge&logo=github)](https://ngo-worldwide.org/winners-dashboard)
[![🌐 Visit Website](https://img.shields.io/badge/Visit%20Website-ngo--worldwide.org-blue?style=for-the-badge&logo=google-chrome)](https://ngo-worldwide.org)

---

## 💫 Our Mission  
To create a world of equal opportunity by supporting humanitarian projects, encouraging innovation, and inspiring hope for vulnerable populations across the globe.

---

## 🌐 What We Do  
- 🤝 Humanitarian aid and global relief  
- 📚 Educational empowerment for youth  
- 🌱 Environmental and sustainability initiatives  
- 💡 Technology-driven charity innovation  

---

## 🕊️ Vision  
A connected world where innovation fuels humanitarian progress, education eliminates inequality, and sustainability ensures a healthy planet for all.

---

## 🎥 Dynamic Testimonial Videos  
**Rotating every 5 minutes**  

<div align="center">

<video id="testimonialVideo" width="480" height="270" autoplay muted loop playsinline>
  <source src="https://ngo-worldwide.org/testimonials/testimonial1.mp4" type="video/mp4">
</video>

</div>

<script>
const videos = [
  "https://ngo-worldwide.org/testimonials/testimonial1.mp4",
  "https://ngo-worldwide.org/testimonials/testimonial2.mp4",
  "https://ngo-worldwide.org/testimonials/testimonial3.mp4",
  "https://ngo-worldwide.org/testimonials/testimonial4.mp4"
];
let index = 0;
setInterval(() => {
  index = (index + 1) % videos.length;
  document.getElementById("testimonialVideo").src = videos[index];
}, 300000); // every 5 minutes
</script>

---

## 🏆 Live Winner Spotlight (Auto-Updating)

<div align="center" style="background-color:#001f3f; color:#ffffff; padding:10px; border-radius:10px; font-size:16px; font-weight:bold; overflow:hidden; white-space:nowrap;">
  <marquee id="winnerMarquee" behavior="scroll" direction="left" scrollamount="5">
    Loading latest winners...
  </marquee>
</div>

<script>
async function loadWinners() {
  try {
    const res = await fetch("https://ngo-worldwide.org/api/winners.json"); // Example live endpoint
    const data = await res.json();
    const marquee = document.getElementById("winnerMarquee");
    marquee.textContent = data.map(
      w => `🏅 ${w.name} – ${w.country} | ${w.project}`
    ).join("   •   ");
  } catch (e) {
    console.error("Failed to load winners:", e);
  }
}
loadWinners();
setInterval(loadWinners, 300000); // refresh every 5 min
</script>

> 🕓 Live feed updates automatically when new winners are verified.

---

## 📡 Transparency & Tracking  
Monitor project funding and results in real-time.  

🔗 [ngo-worldwide.org/tracker](https://ngo-worldwide.org/tracker)  
🎯 [ngo-worldwide.org/winners-dashboard](https://ngo-worldwide.org/winners-dashboard)

---

## 💻 Join or Register as a Winner  

<a href="https://ngo-worldwide.org/winners-dashboard" target="_blank">
  <img src="https://img.shields.io/badge/Register%20Now-Click%20Here-blue?style=for-the-badge&logo=github" alt="Register Button">
</a>

---

## 💬 Connect With Us  
- 🌐 [Website](https://ngo-worldwide.org)  
- 💌 contact@ngo-worldwide.org  
- 🔵 [Facebook](https://facebook.com/ngoworldwideltd)  
- 🟣 [Instagram](https://instagram.com/ngoworldwideltd)  
- 🐦 [Twitter/X](https://twitter.com/ngoworldwideltd)  
- 💼 [LinkedIn](https://linkedin.com/company/ngo-worldwide-ltd)  
- 🔴 [YouTube](https://youtube.com/@ngoworldwideltd)

---

**© 2025 Worldwide Ltd Charity Live Impact Globe**  
Registered under **NGO Worldwide Ltd** • All rights reserved.
