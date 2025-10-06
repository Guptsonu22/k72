# K72 Creative Agency Website

A modern, high-end creative agency website built with React, featuring sophisticated animations and immersive user experiences.

## 🎯 Overview

K72 is a French creative agency specializing in digital experiences, branding, and visual storytelling. This website showcases their portfolio with advanced animations, modern design, and seamless user interactions.

## ✨ Features

- **Immersive Video Backgrounds** - Full-screen looping videos for visual impact
- **Advanced Animations** - GSAP-powered smooth transitions and scroll effects
- **Responsive Design** - Optimized for all devices and screen sizes
- **Interactive Navigation** - Full-screen animated navigation overlay
- **Portfolio Showcase** - Dynamic project cards with hover effects
- **French Language Support** - Localized content and typography
- **Modern Typography** - Custom Lausanne font family
- **Performance Optimized** - Fast loading with Vite build system

## 🛠️ Technology Stack

### Core Technologies
- **React 18** - Modern React with hooks and functional components
- **Vite** - Lightning-fast build tool and development server
- **React Router DOM** - Client-side routing and navigation
- **Tailwind CSS 4** - Utility-first CSS framework

### Animation & Effects
- **GSAP (GreenSock)** - Professional-grade animation library
- **@gsap/react** - React integration for GSAP
- **ScrollTrigger** - Scroll-based animation triggers

### Development Tools
- **ESLint** - Code linting and quality assurance
- **TypeScript Support** - Type definitions for React
- **Hot Module Replacement** - Instant development feedback

## 🚀 Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd k72
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the port shown in terminal)

### Available Scripts

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Run linting
npm run lint
```

## 📁 Project Structure

```
k72/
├── public/
│   ├── fonts/           # Custom Lausanne fonts
│   ├── video.mp4        # Background video
│   └── vite.svg         # Vite logo
├── src/
│   ├── components/
│   │   ├── common/      # Shared components
│   │   │   └── Stairs.jsx
│   │   ├── home/        # Home page components
│   │   │   ├── Video.jsx
│   │   │   ├── HomeHeroText.jsx
│   │   │   └── HomeBottomText.jsx
│   │   ├── Navigation/  # Navigation components
│   │   │   ├── Navbar.jsx
│   │   │   └── FullScreenNav.jsx
│   │   └── projects/    # Project showcase
│   │       └── ProjectCard.jsx
│   ├── context/         # React Context
│   │   └── NavContext.jsx
│   ├── pages/           # Page components
│   │   ├── Home.jsx
│   │   ├── Projects.jsx
│   │   └── Agence.jsx
│   ├── App.jsx          # Main app component
│   ├── main.jsx         # App entry point
│   └── index.css        # Global styles
├── package.json
├── vite.config.js
└── README.md
```

## 🎨 Design System

### Color Palette
- **Primary Black** - `#000000` - Main background and text
- **Accent Green** - `#D3FD50` - Interactive elements and highlights
- **Pure White** - `#FFFFFF` - Text and contrast elements

### Typography
- **Font Family**: Lausanne (300, 500 weights)
- **Responsive Sizing**: Fluid typography using viewport units
- **Hierarchy**: Clear visual hierarchy with different font weights

### Layout Principles
- **Full-Screen Design** - Immersive, edge-to-edge layouts
- **Mobile-First** - Responsive design starting from mobile
- **Grid System** - Flexible grid layouts for content organization

## 🎭 Pages & Features

### Home Page (`/`)
- **Hero Section** - Full-screen video background
- **Animated Text** - "L'étincelle qui génère la créativité"
- **Video Integration** - Embedded video within text elements
- **Call-to-Action** - Navigation to projects and agency info

### Projects Page (`/projects`)
- **Portfolio Grid** - 6 project cards in responsive layout
- **Hover Effects** - Smooth transitions and overlay text
- **Scroll Animations** - GSAP-powered entrance effects
- **Interactive Cards** - "Vior le projet" hover states

### Agency Page (`/agence`)
- **Company Information** - About the agency
- **Team Details** - Staff and expertise showcase
- **Brand Story** - Mission and values presentation

## 🎬 Animation System

### GSAP Integration
- **Timeline Animations** - Complex animation sequences
- **Scroll Triggers** - Elements animate based on scroll position
- **Stagger Effects** - Sequential element animations
- **3D Transforms** - Depth and perspective effects

### Interactive States
- **Hover Animations** - Smooth transitions on user interaction
- **Loading States** - Elegant loading animations
- **Navigation Transitions** - Seamless page transitions

## 📱 Responsive Design

### Breakpoints
- **Mobile**: Default styles (320px+)
- **Desktop**: `lg:` prefix (1024px+)

### Adaptive Features
- **Flexible Typography** - Scales with viewport size
- **Responsive Images** - Optimized for different screen sizes
- **Touch Interactions** - Mobile-friendly hover states
- **Performance** - Optimized for mobile devices

## 🔧 Development Guidelines

### Code Organization
- **Component-Based Architecture** - Modular, reusable components
- **Context API** - Global state management for navigation
- **Custom Hooks** - Reusable logic and effects
- **Clean File Structure** - Organized by feature and functionality

### Styling Approach
- **Tailwind CSS** - Utility-first styling methodology
- **Custom Classes** - Brand-specific styling extensions
- **Responsive Design** - Mobile-first responsive approach
- **Animation Integration** - GSAP and CSS transitions

## 🚀 Deployment

### Production Build
```bash
npm run build
```

### Preview Production
```bash
npm run preview
```

### Deployment Options
- **Static Hosting** - Netlify, Vercel, GitHub Pages
- **CDN Integration** - For global content delivery
- **Performance Optimization** - Image and video optimization

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- **Creative Direction** - K72 Creative Agency
- **Development** - React & GSAP Implementation
- **Design** - Modern Web Design Principles

## 🔗 Links

- **Live Website** - [k72.ca](https://k72.ca)
- **Portfolio** - [Projects Showcase](https://k72.ca/projects)
- **Contact** - [Agency Information](https://k72.ca/agence)

---

**Built with ❤️ by K72 Creative Agency**