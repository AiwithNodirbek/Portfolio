# 🚀 3D Developer Portfolio

A modern, interactive, and visually stunning developer portfolio built with React, Three.js, and cutting-edge web technologies. This portfolio showcases professional skills, projects, and experience through an immersive 3D experience and smooth animations.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![React](https://img.shields.io/badge/React-18.3.1-blue)
![Three.js](https://img.shields.io/badge/Three.js-0.160.0-green)
![Vite](https://img.shields.io/badge/Vite-5.2.10-purple)

## ✨ Features

- **🎮 Interactive 3D Experience**: Immersive 3D canvas with React Three Fiber
- **🎨 Smooth Animations**: Framer Motion powered transitions and micro-interactions
- **📱 Fully Responsive**: Mobile-first design with Tailwind CSS
- **⚡ Performance Optimized**: Vite-powered development and production builds
- **🎯 Professional Sections**: Hero, About, Experience, Projects, Skills, Contact
- **🌌 Dynamic Backgrounds**: Animated stars and 3D elements
- **📧 Contact Integration**: EmailJS powered contact form
- **🎭 Modern UI/UX**: Clean, professional design with gradient accents

## 🛠️ Tech Stack

### Frontend
- **React 18.3.1** - Modern React with hooks and functional components
- **Vite 5.2.10** - Lightning-fast build tool and dev server
- **Tailwind CSS 3.4.3** - Utility-first CSS framework

### 3D & Graphics
- **Three.js 0.160.0** - 3D graphics library
- **@react-three/fiber 8.15.15** - React renderer for Three.js
- **@react-three/drei 9.88.15** - Useful helpers for React Three Fiber
- **Maath 0.7.0** - Mathematical utilities for 3D

### Animation & UX
- **Framer Motion 11.0.17** - Production-ready motion library
- **React Parallax Tilt 1.7.301** - Interactive tilt effects
- **React Vertical Timeline Component 3.6.0** - Professional timeline display

### Utilities
- **EmailJS Browser 4.0.0** - Email service integration
- **React Router DOM 6.23.1** - Client-side routing

## 🎨 Color Palette

### Primary Colors
- **Primary**: `#050816` - Deep navy/purple background
- **Secondary**: `#aaa6c3` - Muted gray-purple for text
- **Tertiary**: `#151030` - Card/surface background
- **Accent**: `#915EFF` - Vibrant purple for highlights

### Gradients
- **Violet Gradient**: `#804dee` to transparent
- **Green-Pink Gradient**: `#00cea8` to `#bf61ff`
- **Text Gradients**: Blue, green, pink, and orange variants

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/3d-developer-portfolio.git
   cd 3d-developer-portfolio
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
   Navigate to `http://localhost:5173`

### Build for Production

```bash
npm run build
npm run preview
```

## 📁 Project Structure

```
src/
├── assets/                 # Images, icons, and 3D models
├── components/            # React components
│   ├── canvas/           # 3D canvas components
│   │   ├── Ball.jsx      # Interactive ball canvas
│   │   ├── Computers.jsx # Hero 3D computer model
│   │   ├── Earth.jsx     # 3D earth visualization
│   │   └── Stars.jsx     # Animated starfield
│   ├── About.jsx         # About section component
│   ├── Contact.jsx       # Contact form component
│   ├── Experience.jsx    # Timeline component
│   ├── Feedbacks.jsx     # Testimonials component
│   ├── Hero.jsx          # Hero section component
│   ├── Navbar.jsx        # Navigation component
│   ├── Tech.jsx          # Skills/technologies component
│   └── Works.jsx         # Projects showcase component
├── constants/             # Data and configuration
│   └── index.js          # Projects, skills, experience data
├── hoc/                  # Higher-order components
├── utils/                # Utility functions and animations
├── App.jsx               # Main application component
├── index.css             # Global styles and custom CSS
└── main.jsx              # Application entry point
```

## 🎯 Key Components

### Hero Section
- Interactive 3D computer canvas
- Animated text and scroll indicator
- Professional introduction

### About Section
- Service cards with hover effects
- Skills overview
- Professional summary

### Experience Timeline
- Vertical timeline with company logos
- Role descriptions and achievements
- Smooth scroll animations

### Projects Showcase
- Project cards with images
- Technology tags
- GitHub links and descriptions

### 3D Canvas Elements
- **ComputersCanvas**: Hero background 3D model
- **StarsCanvas**: Animated starfield background
- **EarthCanvas**: Interactive 3D earth
- **BallCanvas**: Interactive floating ball

## 🔧 Customization

### Adding New Projects
Edit `src/constants/index.js`:

```javascript
const projects = [
  {
    name: "Your Project",
    description: "Project description...",
    tags: [
      { name: "react", color: "blue-text-gradient" },
      { name: "nodejs", color: "green-text-gradient" }
    ],
    image: projectImage,
    source_code_link: "https://github.com/yourusername/project"
  }
];
```

### Modifying Colors
Update `tailwind.config.cjs`:

```javascript
colors: {
  primary: "#your-color",
  secondary: "#your-color",
  // ... other colors
}
```

### Adding New Sections
1. Create component in `src/components/`
2. Add to `src/components/index.js`
3. Import and use in `App.jsx`

## 📱 Responsive Design

- **Mobile First**: Optimized for mobile devices
- **Breakpoints**: xs (450px), sm, md, lg
- **Touch Friendly**: Optimized for touch interactions
- **Performance**: Optimized 3D rendering for mobile

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository
2. Build command: `npm run build`
3. Output directory: `dist`
4. Deploy automatically on push

### Netlify
1. Connect repository
2. Build command: `npm run build`
3. Publish directory: `dist`
4. Deploy automatically

### GitHub Pages
1. Build the project: `npm run build`
2. Push `dist` folder to `gh-pages` branch
3. Enable GitHub Pages in repository settings

## 🔑 Environment Variables

Create `.env` file for EmailJS configuration:

```env
VITE_EMAILJS_PUBLIC_KEY=your_public_key
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_ID=your_template_id
```

## 📊 Performance Optimization

- **Lazy Loading**: 3D components load on demand
- **Image Optimization**: Optimized images and SVGs
- **Code Splitting**: Vite automatic code splitting
- **3D Optimization**: Efficient Three.js rendering
- **Animation Performance**: Optimized Framer Motion

## 🎨 Design System

### Typography
- **Font**: Poppins (Google Fonts)
- **Weights**: 100-900
- **Responsive**: Fluid typography scaling

### Spacing
- **Padding**: Consistent spacing system
- **Margins**: Responsive margin utilities
- **Gaps**: Flexible gap system for layouts

### Animations
- **Duration**: 0.1s to 1.5s
- **Easing**: Spring and ease functions
- **Stagger**: Sequential animation delays

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Three.js Community** - 3D graphics library
- **Framer Motion** - Animation library
- **Tailwind CSS** - Utility-first CSS framework
- **Vite** - Build tool and dev server
- **React Three Fiber** - React Three.js integration

## 📞 Contact

- **Portfolio**: [https://portfolio-six-xi-l3x8881u9a.vercel.app/]
- **GitHub**: [@yourusername](https://github.com/yourusername)
- **LinkedIn**: [www.linkedin.com/in/nodirbek-kamoldinov-a4916534a]

---

⭐ **Star this repository if you found it helpful!**

Made with ❤️ by AcemeNodirbek
