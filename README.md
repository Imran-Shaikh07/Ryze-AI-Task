# Ryze AI Website

A modern, component-driven React.js website for Ryze AI - an AI-powered advertising management platform.

## Features

- **Modern SaaS Design**: Clean, minimalist aesthetic inspired by leading SaaS companies
- **Atomic Design Architecture**: Organized component structure (atoms, molecules, organisms, templates)
- **Fully Responsive**: Mobile-first design that works beautifully on all devices
- **Accessible**: WCAG compliant with proper ARIA labels, focus states, and semantic HTML
- **Component-Driven**: Reusable, modular components for easy maintenance

## Tech Stack

- React 18
- React Router DOM
- Vite
- Tailwind CSS
- CSS3 (Custom Properties + Glassmorphism)

## Getting Started

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The site will be available at `http://localhost:5173`

### Build

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
src/
├── components/
│   ├── atoms/          # Basic building blocks (Button, Logo)
│   ├── molecules/      # Simple component groups (FeatureCard, TestimonialCard, PricingCard)
│   └── organisms/      # Complex components (Header, Footer, Hero, Features, Testimonials, Pricing)
├── pages/              # Page components (HomePage, FeaturesPage, PricingPage)
├── App.jsx             # Main app component with routing
├── main.jsx            # Entry point
└── index.css           # Global styles and CSS variables
```

## Design System

### Colors
- Primary: `#0066FF` (Blue)
- Secondary: `#1A1A2E` (Dark Navy)
- Background: `#FAFAFA` (Off-white)
- Text Primary: `#1A1A2E`
- Text Secondary: `#4A5568`

### Typography
- Headings: System font stack, 700-800 weight
- Body: System font stack, 400 weight
- Responsive font sizes using `clamp()`

### Spacing
- Consistent spacing scale using CSS custom properties
- Mobile-first responsive breakpoints

## Pages

- **Homepage** (`/`): Hero, Features, Testimonials, Pricing
- **Features** (`/features`): Detailed feature list
- **Pricing** (`/pricing`): Pricing plans and FAQ
- **Contact** (`/contact`): Contact form and information

## Design Features

- **Glassmorphism Cards**: Modern crystal/glass effect cards with backdrop blur
- **Smooth Animations**: Subtle hover effects and transitions
- **Gradient Accents**: Beautiful gradient overlays and button effects
- **Professional Polish**: Senior-level design with attention to detail

## Accessibility

- Semantic HTML5 elements
- ARIA labels for interactive elements
- Keyboard navigation support
- Focus visible states
- Proper heading hierarchy
- Alt text for images (when added)
- Color contrast ratios meet WCAG AA standards

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

MIT
