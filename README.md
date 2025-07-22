# 3D Shirt Showcase 👕  
*A reactive, immersive display of a 3D shirt model using React and Three.js*

---

### Table of Contents  
- [🎨 Overview ](#-overview)  
- [🧰 Tech Stack ](#-tech-stack)  
- [🚀 Getting Started](#-getting-started)  
- [🎯 Features  ](#-features)  
- [🧩 Project Structure](#-project-structure)  
- [📤 Deployment](#-deployment)  
- [📄 License ](#-license)  
- [👤 Credits  ](#-credits)

---

## 🎨 Overview  
This project is a single-page web app that renders a **rotatable, interactively viewable 3D shirt model**. Built using **React**, with **Three.js** for 3D visualization, along with standard **HTML** and **CSS** for layout and styling, it delivers a seamless and engaging user experience.
🔗 **Live Demo**: [https://avatarparzival.github.io/3d/](https://avatarparzival.github.io/3d/)

---

## 🧰 Tech Stack  
- **HTML5** – page structure  
- **CSS3** – basic styling and layout  
- **JavaScript** – interactivity and logic  
- **Three.js** – 3D rendering of the `.glb` shirt model  
- **GLTFLoader** – for loading `.glb` files into the scene

---

## 🚀 Getting Started

### Prerequisites  
Ensure you have **Node.js (v14+)** and **npm** installed.

### Installation  
1. Clone the repo:  
   ```bash
   git clone https://github.com/AvatarParzival/3d.git
   ```  
2. Navigate into the directory:  
   ```bash
   cd 3d
   ```  
3. Install dependencies:  
   ```bash
   npm install
   ```  

### Run Locally  
Start the development server:  
```bash
npm start
```  
Visit `http://localhost:3000` to view the interactive 3D shirt in your browser.

---


## 🎯 Features  
- 🧥 **3D shirt model**: Rendered in real time using `shirt.glb`  
- 🎨 **High-resolution textures**: Includes styled product images like:
  - `Dupatta1.png`  
  - `Radiance in Beige and Blooms.png`  
  - `Serene Elegance in Traditional Wear.png`  
- 🖱️ **Basic orbit control** for rotation and zoom (if enabled)  
- 📱 **Responsive layout** for desktop and mobile

---

## 🧩 Project Structure

```
├── index.html                 # Main webpage with embedded Three.js viewer
├── Models/
│   └── shirt.glb              # 3D model file
├── Dupatta1.png
├── Radiance in Beige and Blooms.png
├── Serene Elegance in Traditional Wear.png
├── package.json              # Optional Three.js or tooling dependency
└── package-lock.json
```

---

## 📤 Deployment

This site is currently deployed and publicly available at:  
🔗 **[https://avatarparzival.github.io/3d/](https://avatarparzival.github.io/3d/)**

You can also deploy it using:
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- GitHub Pages (like shown above)

---


## 📄 License  
This project is open-source and available under the [MIT License](./LICENSE). Feel free to use, modify, and build upon it.

---

## 👤 Credits  
**Author**: AvatarParzival  
- GitHub: [@AvatarParzival](https://github.com/AvatarParzival)


