<div align="center">

# 🌌 SPHEREx Explorer

**Turning NASA's space telescope data into an interactive experience in your browser.**

[![NASA](https://img.shields.io/badge/Data-NASA%20SPHEREx-0B3D91?style=for-the-badge&logo=nasa)](https://spherex.caltech.edu/)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-online-00d4ff?style=for-the-badge&logo=vercel)](https://spherex-explorer.up.railway.app)
[![Video](https://img.shields.io/badge/Watch-Demo%20Video-red?style=for-the-badge&logo=youtube)](https://youtube.com/shorts/tPYF8bW6FDM?si=8_bMxg_uRfIlaeP3)

[**🚀 Live Demo**](https://spherex-explorer.up.railway.app) · [**🎥 Intro Video**](https://youtube.com/shorts/tPYF8bW6FDM?si=8_bMxg_uRfIlaeP3) · [**🏆 Challenge**](https://www.spaceappschallenge.org/2026/challenges/planet-x-and-spherex/) · [**👥 Team**](https://www.spaceappschallenge.org/2026/find-a-team/tlon-9/)

</div>

---

## 🌟 What is SPHEREx Explorer?

**SPHEREx Explorer** is a web platform that transforms raw data from NASA's SPHEREx space telescope into **beautiful, interactive, and analyzable images** — no installation, no command line, no PhD required.

The SPHEREx mission (launched in 2025) scans the entire sky in **102 infrared wavelengths**, producing an unprecedented spectral map of the cosmos. Until now, exploring this data required professional astronomy software. We made it accessible in a browser tab.

> _"Hubble made space beautiful. We make the spectrum visible."_

## ✨ Key Features

### 🌈 Spectral images like you've never seen
We convert raw spectral data into an image where **color represents wavelength** and **brightness represents intensity**. Each colored band is a different slice of the infrared spectrum, painted for human eyes.

![Spectral composite](./assets/gifs/composite.gif)

---

### ⏱️ Time comparison between observations
The sky is not static. Compare the **same region of the sky at two different moments** and automatically highlight what changed: moving asteroids, variable stars, crossing satellites.

![Difference view](./assets/gifs/difference.gif)

---

### 🪐 Asteroid detector with NASA JPL validation
Each field is automatically cross-referenced with the **NASA JPL Small-Body Database**. The app shows which bright spots are **already-cataloged asteroids** (with name and magnitude) and which are not — revealing **candidates for new discoveries**.

![Asteroid overlay](./assets/gifs/asteroids.gif)

---

### 🔭 3D stellar visualizer
Click on any star and the app generates a **procedural 3D model** based on the object's real temperature:
- **Bright glowing spheres** for hot stars (O/B/A type)
- **Textured rocky spheres** for cold objects
- **Mysterious wireframes** for unclassified sources

![3D visualizer](./assets/gifs/3d-visualizer.gif)

---

### 🌡️ Star temperature in one click
Select a source and the app calculates its **color temperature** by comparing two infrared bands using blackbody physics — presented as a friendly visual gauge, not formulas.

![Temperature gauge](./assets/gifs/temperature.gif)

---

### 📅 Timeline of observations
The same region has been photographed multiple times. A **horizontal slider** lets you navigate between different visits of the same field — showing how the cosmos changes across time.

![Timeline slider](./assets/gifs/timeline.gif)

---

## 🎯 Who is this for?

| Audience | Value |
|----------|-------|
| **Curious minds** | Explore the universe without a telescope |
| **Students & educators** | Free astronomy lab in the browser |
| **Researchers** | Fast exploratory analysis of SPHEREx data |
| **Citizen scientists** | Potential new object discoveries |

---

## 🧪 Demo Sectors

Three regions of the sky are ready to explore:

| Sector | Highlights |
|--------|------------|
| 🌌 **Orion Nebula (M42)** | Iconic star-forming region · rich in hot O/B/A stars |
| ☁️ **Rho Ophiuchi Complex** | Nearby molecular cloud · ice and dust analysis |
| 🌠 **Southern Test Field** | Validation field · no known asteroids (perfect for testing) |

---

## ⚙️ How it works (in plain words)

1. **Data comes from NASA** — we fetch FITS files (astronomical data format) from the official SPHEREx archive.
2. **The backend processes them** — applies scientific stretch, removes instrument artifacts, and assigns colors based on wavelength.
3. **Asteroids are matched against NASA JPL** — every bright source is checked against the Small-Body Database.
4. **The frontend makes it interactive** — zoom, pan, click, analyze, and visualize in 3D.

No prior knowledge of astronomy or programming needed — the science is under the hood.

---

## 🏗️ Tech Stack

<div align="center">

**Backend**
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Astropy](https://img.shields.io/badge/Astropy-FF6B6B?logo=python&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?logo=three.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white)

**Infrastructure**
![Railway](https://img.shields.io/badge/Railway-0B0D0E?logo=railway&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

</div>

---