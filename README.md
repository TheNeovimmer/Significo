# 🎬 Significo

A modern, high-performance website featuring smooth animations, scroll-triggered effects, and an immersive user experience. Built with cutting-edge web technologies and animation libraries.

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.2.0-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.3-38B2AC?logo=tailwind-css&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP-3.12.5-88CE02?logo=greensock&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-11.0.24-0055FF?logo=framer&logoColor=white)

---

## ✨ Features

- 🎨 **Smooth Scrolling** - Powered by Locomotive Scroll for buttery-smooth page navigation
- 🎬 **Advanced Animations** - GSAP ScrollTrigger animations with custom timelines
- 🎭 **Framer Motion** - React-based motion library for component animations
- 🎥 **Video Backgrounds** - Immersive full-screen video hero sections
- 🎯 **Scroll-Triggered Effects** - Dynamic animations that respond to scroll position
- 🌈 **Theme Switching** - Dynamic theme changes based on scroll sections
- 📱 **Responsive Design** - Mobile-first approach with Tailwind CSS
- ⚡ **Lightning Fast** - Optimized with Vite for instant hot module replacement

---

## 🛠️ Tech Stack

### Core Framework
- **React 18.2.0** - Modern UI library with hooks
- **Vite 5.2.0** - Next-generation frontend build tool

### Styling
- **Tailwind CSS 3.4.3** - Utility-first CSS framework
- **CSS Modules** - Component-scoped styling
- **PostCSS** - CSS processing with Autoprefixer

### Animation Libraries
- **GSAP 3.12.5** - Professional-grade animation library
  - ScrollTrigger plugin for scroll-based animations
  - Timeline animations for complex sequences
- **Framer Motion 11.0.24** - Production-ready motion library for React
- **Locomotive Scroll 5.0.0** - Smooth scrolling with parallax effects
- **Shery.js 1.0.0** - 3D effects and advanced visual enhancements

### Additional Tools
- **React Icons 5.0.1** - Popular icon library
- **ESLint** - Code quality and consistency

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/TheNeovimmer/significo.git
cd significo
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

---

## 📁 Project Structure

```
significo/
├── public/              # Static assets
├── src/
│   ├── assets/         # Images, fonts, videos
│   │   ├── fonts/      # Custom font files
│   │   ├── images/     # Image assets
│   │   └── video/      # Video files
│   ├── components/     # React components
│   │   ├── Home/       # Hero section with video
│   │   ├── Craft/      # Craft section
│   │   ├── Real/       # Real section
│   │   ├── Team/       # Team showcase
│   │   ├── Paragraph/  # Text sections
│   │   ├── Capsule/    # Capsule component
│   │   └── Footer/     # Footer component
│   ├── App.jsx         # Main app component
│   ├── main.jsx        # Entry point
│   └── index.css       # Global styles
├── index.html          # HTML template
├── vite.config.js      # Vite configuration
├── tailwind.config.js  # Tailwind configuration
└── package.json        # Dependencies
```

---

## 🎯 Key Components

### Home Component
- Full-screen video background
- Animated text reveal on scroll
- Smooth scroll-triggered animations
- Responsive navigation with hide/show on scroll

### Animation Features
- **GSAP ScrollTrigger**: Complex scroll-based animations
- **Framer Motion**: Component-level animations and transitions
- **Locomotive Scroll**: Smooth scrolling experience
- **Theme Switching**: Dynamic color themes per section

---

## 🎨 Customization

### Theme Colors
Modify theme colors by updating the `data-color` attributes in section components and corresponding CSS variables.

### Animations
Adjust animation timings and effects in component files:
- GSAP animations: `src/components/Home/Index.jsx`
- Framer Motion: Component-level `motion` props
- ScrollTrigger: Configure in `App.jsx`

### Styling
- Global styles: `src/index.css`
- Component styles: `src/components/*/Style.module.css`
- Tailwind config: `tailwind.config.js`

---

## 📝 Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

---

## 🌟 Highlights

This project demonstrates:
- Advanced scroll-based animations
- Performance-optimized React components
- Modern CSS with Tailwind
- Smooth user experience with multiple animation libraries
- Responsive design patterns
- Video integration and optimization

---

## 👤 Author

**TheNeovimmer**

- GitHub: [@TheNeovimmer](https://github.com/TheNeovimmer)

---

## 📄 License

This project is private and proprietary.

---

## 🙏 Acknowledgments

- GSAP team for the powerful animation library
- Framer team for Framer Motion
- Locomotive Scroll for smooth scrolling
- All contributors to the open-source libraries used

---

<div align="center">

**Built with ❤️ using React, Vite, and modern web technologies**

⭐ Star this repo if you find it interesting!

</div>
