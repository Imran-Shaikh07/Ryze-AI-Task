# 🚀 Ryze AI - AI-Powered Advertising Management Platform

<div align="center">

![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5.0.8-646CFF?logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.3.6-38B2AC?logo=tailwind-css&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

**A modern, component-driven SaaS website built with React.js**

[🌐 Live Demo](https://ryze-ai-by-imran.netlify.app/) • [📖 Documentation](#-getting-started) • [🐛 Report Bug](#-contributing)

</div>

---

## 📋 Table of Contents

- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [🎨 Design System](#-design-system)
- [📱 Pages](#-pages)
- [♿ Accessibility](#-accessibility)
- [🌐 Browser Support](#-browser-support)
- [📄 License](#-license)

---

## ✨ Features

### 🎯 Core Features

- **🎨 Modern SaaS Design** - Clean, minimalist aesthetic inspired by leading SaaS companies like OpenAI and Slack
- **🧩 Atomic Design Architecture** - Organized component structure (atoms, molecules, organisms) for scalability
- **📱 Fully Responsive** - Mobile-first design that works beautifully on all devices
- **♿ Accessible** - WCAG compliant with proper ARIA labels, focus states, and semantic HTML
- **🔧 Component-Driven** - Reusable, modular components for easy maintenance and updates

### 🎭 Design Features

- **💎 Glassmorphism Cards** - Modern crystal/glass effect cards with backdrop blur and elegant shadows
- **✨ Smooth Animations** - Subtle hover effects, transitions, and micro-interactions
- **🌈 Gradient Accents** - Beautiful gradient overlays, button effects, and text gradients
- **🎯 Professional Polish** - Senior-level design with attention to detail and pixel-perfect implementation

---

## 🛠️ Tech Stack

### Frontend Framework
- **React 18.2.0** - Modern React with hooks and functional components
- **React Router DOM 6.20.0** - Client-side routing and navigation

### Build Tools
- **Vite 5.0.8** - Next-generation frontend build tool
- **PostCSS** - CSS processing with Autoprefixer

### Styling
- **Tailwind CSS 3.3.6** - Utility-first CSS framework
- **CSS3 Custom Properties** - Design tokens and variables
- **Glassmorphism Effects** - Modern glass-like UI elements

### Development
- **TypeScript Support** - Type definitions for React
- **ESLint Ready** - Code quality and consistency

---

## 🚀 Getting Started

### Prerequisites

- Node.js 16.x or higher
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd "Roz AI Task"
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```
   The site will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `dist/` directory.

### Preview Production Build

```bash
npm run preview
```

---

## 📁 Project Structure

```
ryze-ai-website/
├── public/                 # Static assets
├── src/
│   ├── components/
│   │   ├── atoms/          # Basic building blocks
│   │   │   ├── Button.jsx
│   │   │   ├── Button.css
│   │   │   ├── Logo.jsx
│   │   │   └── Logo.css
│   │   ├── molecules/     # Simple component groups
│   │   │   ├── FeatureCard.jsx
│   │   │   ├── TestimonialCard.jsx
│   │   │   └── PricingCard.jsx
│   │   └── organisms/     # Complex components
│   │       ├── Header.jsx
│   │       ├── Footer.jsx
│   │       ├── Hero.jsx
│   │       ├── Features.jsx
│   │       ├── Testimonials.jsx
│   │       └── Pricing.jsx
│   ├── pages/             # Page components
│   │   ├── HomePage.jsx
│   │   ├── FeaturesPage.jsx
│   │   ├── PricingPage.jsx
│   │   └── ContactPage.jsx
│   ├── App.jsx            # Main app component with routing
│   ├── main.jsx           # Entry point
│   └── index.css          # Global styles and CSS variables
├── index.html
├── package.json
├── vite.config.js
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

---

## 🎨 Design System

### Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Primary | `#0066FF` | Buttons, links, accents |
| Primary Dark | `#0052CC` | Hover states |
| Primary Light | `#3385FF` | Gradients |
| Secondary | `#1A1A2E` | Headings, dark elements |
| Text Primary | `#1A1A2E` | Main text |
| Text Secondary | `#4A5568` | Secondary text |
| Background | `#FAFAFA` | Page background |
| Background White | `#FFFFFF` | Card backgrounds |

### Typography

- **Headings**: System font stack, 700-800 weight
- **Body**: System font stack, 400 weight
- **Responsive**: Font sizes using `clamp()` for fluid typography

### Spacing Scale

- Consistent spacing using CSS custom properties
- Mobile-first responsive breakpoints
- Standardized padding and margin values

---

## 📱 Pages

### Homepage (`/`)
- **Hero Section** - Compelling headline with value proposition
- **Features** - 4 key features with icons and descriptions
- **Testimonials** - Customer testimonials with metrics
- **Pricing** - Three-tier pricing plans

### Features Page (`/features`)
- Detailed feature list (8 features)
- Expanded descriptions
- Call-to-action section

### Pricing Page (`/pricing`)
- Pricing plans with feature comparison
- FAQ section
- Contact sales CTA

### Contact Page (`/contact`)
- Contact form with validation
- Contact information cards
- Social media links

---

## ♿ Accessibility

This project follows WCAG 2.1 Level AA guidelines:

- ✅ **Semantic HTML5** elements throughout
- ✅ **ARIA labels** for interactive elements
- ✅ **Keyboard navigation** support
- ✅ **Focus visible** states on all interactive elements
- ✅ **Proper heading hierarchy** (h1 → h2 → h3)
- ✅ **Color contrast ratios** meet WCAG AA standards (4.5:1 minimum)
- ✅ **Alt text** ready for images
- ✅ **Screen reader** friendly

---

## 🌐 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | Latest |
| Firefox | Latest |
| Safari | Latest |
| Edge | Latest |
| iOS Safari | Latest |
| Chrome Mobile | Latest |

---

## 🎯 Key Highlights

- ⚡ **Fast Performance** - Optimized build with Vite
- 🎨 **Beautiful UI** - Glassmorphism and modern design patterns
- 📱 **Mobile-First** - Responsive design for all screen sizes
- ♿ **Accessible** - WCAG compliant and keyboard navigable
- 🔧 **Maintainable** - Atomic design architecture
- 🚀 **Production Ready** - Optimized for deployment

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👨‍💻 Developer

**Imran**

- 🌐 [Live Website](https://ryze-ai-by-imran.netlify.app/)
- 📧 Email: support@ryzeai.com
- 📍 Location: Bangalore, Karnataka, India

---

<div align="center">

**Built with ❤️ using React and Vite**

⭐ Star this repo if you find it helpful!

</div>
