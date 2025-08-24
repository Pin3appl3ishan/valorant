# Valorant - Interactive Gaming Experience

A modern, interactive landing page showcasing the world of Valorant with stunning animations, video content, and immersive user experience.

## 🎮 Overview

This project brings the gaming world to life through interactive video content, smooth animations, and modern web technologies. The project features a dynamic hero section with video transitions, interactive features showcase, and a complete gaming experience presentation.

## ✨ Features

### 🎥 Interactive Video Experience

- **Dynamic Hero Section**: Multiple video backgrounds with smooth transitions
- **Video Loading System**: Intelligent preloading with loading animations
- **Interactive Video Controls**: Click-to-switch between different video backgrounds
- **Custom Video Masking**: Unique clip-path animations for video frames

### 🎨 Advanced Animations

- **GSAP Integration**: Professional-grade animations using GreenSock
- **Scroll-Triggered Animations**: Smooth parallax and reveal effects
- **Custom Loading Animations**: Three-body loading system
- **Hover Effects**: Interactive tilt and hover animations on cards

### 📱 Modern UI/UX

- **Responsive Design**: Optimized for all device sizes
- **Custom Typography**: Multiple font families for visual hierarchy
- **Bento Grid Layout**: Modern card-based feature showcase
- **Smooth Scrolling**: Enhanced navigation experience

### 🎯 Key Sections

- **Hero Section**: Dynamic video backgrounds with interactive controls
- **About Section**: Game introduction with animated text and imagery
- **Features Showcase**: Interactive bento grid with video content
- **Story Section**: Narrative presentation of the gaming world
- **Contact Section**: User engagement and communication
- **Footer**: Complete site information and links

## 🛠️ Technologies Used

### Frontend Framework

- **React 18.3.1** - Modern React with latest features
- **Vite 5.4.10** - Fast build tool and development server

### Animation & Effects

- **GSAP 3.12.5** - Professional animation library
- **@gsap/react 2.1.1** - React integration for GSAP
- **ScrollTrigger** - Scroll-based animations

### Styling & UI

- **Tailwind CSS 3.4.15** - Utility-first CSS framework
- **PostCSS 8.4.49** - CSS processing
- **Autoprefixer 10.4.20** - CSS vendor prefixing

### Utilities & Icons

- **React Icons 5.3.0** - Comprehensive icon library
- **React Use 17.5.1** - Collection of useful React hooks
- **CLSX 2.1.1** - Conditional className utility

### Development Tools

- **ESLint 9.13.0** - Code linting and formatting
- **TypeScript Support** - Type definitions for React

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd valorant
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
   Navigate to `http://localhost:5173` to view the application

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint for code quality

## 📁 Project Structure

```
valorant/
├── public/                 # Static assets
│   ├── audio/             # Audio files
│   ├── fonts/             # Custom font files
│   ├── img/               # Image assets
│   └── videos/            # Video content
├── src/
│   ├── components/        # React components
│   │   ├── About.jsx      # About section
│   │   ├── AnimatedTitle.jsx # Animated text component
│   │   ├── Button.jsx     # Reusable button component
│   │   ├── Contact.jsx    # Contact section
│   │   ├── Features.jsx   # Features showcase
│   │   ├── Footer.jsx     # Footer component
│   │   ├── Hero.jsx       # Hero section with videos
│   │   ├── Navbar.jsx     # Navigation component
│   │   ├── RoundedCorners.jsx # UI utility component
│   │   └── Story.jsx      # Story section
│   ├── App.jsx            # Main application component
│   ├── main.jsx           # Application entry point
│   └── index.css          # Global styles
├── package.json           # Dependencies and scripts
├── vite.config.js         # Vite configuration
├── tailwind.config.js     # Tailwind CSS configuration
└── eslint.config.js       # ESLint configuration
```

## 🎨 Design Features

### Custom Animations

- **Video Transitions**: Smooth scaling and clipping animations
- **Scroll Effects**: Parallax and reveal animations on scroll
- **Loading States**: Custom three-body loading animation
- **Hover Interactions**: Tilt effects and radial gradient hover states

### Typography System

- **Custom Fonts**: Multiple font families for different purposes
- **Animated Text**: GSAP-powered text animations
- **Responsive Typography**: Scales appropriately across devices

### Video Integration

- **Multiple Video Sources**: 4 different hero videos
- **Preloading System**: Intelligent video loading with progress tracking
- **Custom Masking**: Unique clip-path animations for video frames
- **Interactive Controls**: Click-to-switch video functionality

## 🔧 Customization

### Adding New Videos

1. Place video files in `public/videos/`
2. Update the `getVideoSrc` function in `Hero.jsx`
3. Adjust the `totalVideos` constant

### Modifying Animations

- GSAP animations are configured in individual components
- ScrollTrigger configurations can be adjusted for timing and effects
- Custom CSS animations are defined in `index.css`

### Styling Changes

- Tailwind classes are used throughout the application
- Custom CSS variables and utilities are defined in `index.css`
- Component-specific styles are co-located with components

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- **GSAP** for powerful animation capabilities
- **Tailwind CSS** for utility-first styling
- **React Icons** for comprehensive icon library
- **Vite** for fast development experience

---

**Note**: This is a showcase project demonstrating modern web development techniques with React, GSAP animations, and interactive video content. The project is designed to provide an immersive gaming experience presentation.
