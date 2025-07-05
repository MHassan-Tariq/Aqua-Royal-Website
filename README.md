# 💧 Aqua Royal – Premium Drinking Water Website

A beautiful and modern animated website for **Aqua Royal**, a premium drinking water brand. This site is developed using **HTML**, **CSS**, **JavaScript**, **Tailwind CSS**, and **GSAP (GreenSock Animation Platform)** to create smooth, professional animations and user experiences.

---

## 🌟 Overview

**Aqua Royal** is a premium water supplier, and this website represents the brand with:
- Smooth animations using GSAP
- Clean and responsive layout
- Eye-catching scroll and entrance animations
- Sections like Home, About, Products, Contact

---

## ⚙️ Tech Stack

| Technology     | Usage                              |
|----------------|-------------------------------------|
| HTML5          | Web structure                       |
| Tailwind CSS   | Utility-first styling               |
| JavaScript     | DOM logic & interactivity           |
| GSAP           | Advanced animations                 |
| ScrollTrigger  | Scroll-based animation effects      |

---

## 🎯 Key Features

- ✨ GSAP-powered animated sections and transitions
- 📱 Fully responsive design for all devices
- 🚀 Fast loading and optimized assets
- 💧 Brand-focused design (colors, fonts, water effects)
- 📷 Product highlight cards
- 📬 Contact form section (can be connected to backend later)

---

## 📁 Folder Structure

/aqua-royal
┣ /assets # Images, logos, icons
┣ /css # Tailwind styles / custom styles
┣ /js # GSAP animation logic
┣ index.html # Main landing page
┗ contact.html # Optional contact page


---

## 📸 Demo Preview


## Aqua Royal Homepage
<img width="959" alt="first" src="https://github.com/user-attachments/assets/46c1eb4f-0068-41bb-a64e-bcf3e76e96ae" />

## Animated Sections
<img width="959" alt="last" src="https://github.com/user-attachments/assets/a3a00e22-95f1-49fa-a229-1f94f1189969" />


---

## 🛠️ How to Use Locally

```bash
git clone https://github.com/your-username/aqua-royal-website.git
cd aqua-royal-website
open index.html OR live server
-------------------------------------------------------------------

npm install -D tailwindcss
npx tailwindcss -i ./css/input.css -o ./css/output.css --watch
------------------
## 🔄 GSAP Animation Examples

javascript
Copy
Edit
// Example animation with GSAP
gsap.from(".hero-text", {
  y: 50,
  opacity: 0,
  duration: 1,
  ease: "power3.out"
});

gsap.to(".water-bottle", {
  scale: 1.1,
  yoyo: true,
  repeat: -1,
  duration: 1.5
});


💼 About Aqua Royal
Aqua Royal – Sip the Royal Standard
We deliver fresh, clean, and safe drinking water to homes and businesses. Our brand focuses on trust, health, and quality.

🙋‍♂️ Author
Hassan Tariq
Founder & Developer
GitHub
LinkedIn
Portfolio

📄 License
This project is licensed under the MIT License.

