# Tiation React Template

<div align="center">
  <img src="https://github.com/tiation/tiation-react-template/blob/main/public/tiation-logo.png?raw=true" alt="Tiation React Template" width="200"/>
  
  [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://tiation.github.io/tiation-react-template)
  [![Enterprise Grade](https://img.shields.io/badge/Enterprise-Grade-blue)](https://github.com/tiation/tiation-react-template)
  [![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue)](https://www.typescriptlang.org/)
  [![React](https://img.shields.io/badge/React-18.3.1-blue)](https://reactjs.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-3.4.11-blue)](https://tailwindcss.com/)
  [![Template](https://img.shields.io/badge/Template-Ready-green)](https://github.com/new?template_name=tiation-react-template&template_owner=tiation)
</div>

## 🚀 Enterprise-Grade React Template

A production-ready React template with modern tooling, enterprise-grade architecture, and dark neon theme. Perfect for building scalable web applications with TypeScript, Tailwind CSS, and automated CI/CD.

### ✨ Features

- **🏗️ Modern Architecture**: React 18.3.1 + TypeScript 5.5.3 + Vite 5.4.1
- **🎨 Beautiful Design**: Dark neon theme with cyan/magenta gradients
- **📱 Responsive**: Mobile-first design with Tailwind CSS
- **🔧 Developer Experience**: Hot reload, ESLint, Prettier, and TypeScript
- **🧪 Testing Ready**: Jest setup with testing utilities
- **🚀 CI/CD**: GitHub Actions for automated deployment
- **📊 Performance**: Lighthouse CI for performance monitoring
- **🔒 Security**: HTTPS, CSP headers, and security best practices
- **📚 Documentation**: Comprehensive docs and architecture diagrams
- **🌟 Components**: shadcn/ui component library integrated

## 🛠️ Technology Stack

### Core
- **React 18.3.1** - Modern React with concurrent features
- **TypeScript 5.5.3** - Type-safe JavaScript development
- **Vite 5.4.1** - Lightning-fast build tool
- **Tailwind CSS 3.4.11** - Utility-first CSS framework

### UI & Components
- **shadcn/ui** - High-quality React components
- **Lucide React** - Beautiful SVG icons
- **Radix UI** - Accessible component primitives
- **Tailwind Animate** - Smooth animations

### State & Forms
- **TanStack Query** - Server state management
- **React Hook Form** - Form handling
- **Zod** - Schema validation
- **React Router** - Client-side routing

### Development
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Husky** - Git hooks
- **TypeScript** - Static typing

## 🚀 Quick Start

### 1. Use This Template

Click the "Use this template" button or:

```bash
gh repo create your-project-name --template tiation/tiation-react-template
```

### 2. Clone & Setup

```bash
git clone https://github.com/your-username/your-project-name.git
cd your-project-name
npm install
```

### 3. Customize Your Project

Edit the following files to customize for your project:

- `package.json` - Update name, description, and repository URLs
- `README.md` - Replace with your project's README
- `index.html` - Update title and meta tags
- `src/components/` - Replace with your components
- `vite.config.ts` - Update base path for GitHub Pages

### 4. Start Development

```bash
npm run dev
```

Visit `http://localhost:8080` to see your app.

## 📁 Project Structure

```
your-project/
├── .github/
│   └── workflows/
│       └── deploy.yml        # GitHub Actions CI/CD
├── docs/
│   ├── architecture/         # Architecture documentation
│   ├── screenshots/          # Application screenshots
│   └── api/                  # API documentation
├── public/
│   ├── images/              # Static images
│   └── favicon.ico          # Favicon
├── src/
│   ├── components/
│   │   ├── ui/              # shadcn/ui components
│   │   ├── layout/          # Layout components
│   │   └── features/        # Feature components
│   ├── pages/               # Route pages
│   ├── hooks/               # Custom React hooks
│   ├── lib/                 # Utility functions
│   ├── types/               # TypeScript types
│   └── styles/              # Global styles
├── package.json             # Dependencies and scripts
├── tailwind.config.ts       # Tailwind configuration
├── vite.config.ts           # Vite configuration
├── tsconfig.json            # TypeScript configuration
└── README.md                # This file
```

## 🎨 Design System

### Color Palette
- **Primary**: Cyan (#00FFFF) - Main brand color
- **Secondary**: Magenta (#FF00FF) - Accent color
- **Background**: Dark (#0A0A0A) - Primary background
- **Surface**: Dark Gray (#1A1A1A) - Card backgrounds
- **Text**: White (#FFFFFF) - Primary text
- **Muted**: Gray (#6B7280) - Secondary text

### Typography
- **Primary**: Inter - Clean, modern sans-serif
- **Display**: Playfair Display - Elegant serif for headings
- **Monospace**: JetBrains Mono - Code and technical content

### Components
All components follow the [shadcn/ui design system](https://ui.shadcn.com/) with custom Tiation branding.

## 🔧 Available Scripts

```bash
# Development
npm run dev              # Start development server
npm run dev:host         # Start dev server with network access

# Production
npm run build            # Build for production
npm run preview          # Preview production build

# Code Quality
npm run lint             # Run ESLint
npm run lint:fix         # Fix ESLint issues
npm run type-check       # Run TypeScript checks

# Testing
npm run test             # Run tests
npm run test:watch       # Run tests in watch mode
npm run test:coverage    # Run tests with coverage

# Deployment
npm run deploy           # Deploy to GitHub Pages
```

## 🚀 Deployment

### GitHub Pages (Automatic)
1. Push to `main` branch
2. GitHub Actions automatically builds and deploys
3. Site available at `https://username.github.io/repository-name`

### Manual Deployment
```bash
npm run build
npm run deploy
```

### Other Platforms
- **Vercel**: Import from GitHub, zero config
- **Netlify**: Drag & drop `dist` folder
- **AWS S3**: Upload `dist` folder contents

## 📊 Performance

### Optimizations
- **Code Splitting**: Route-based lazy loading
- **Tree Shaking**: Dead code elimination
- **Bundle Analysis**: Optimized chunk sizes
- **Asset Optimization**: Compressed images and fonts

### Core Web Vitals Targets
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **First Input Delay**: < 100ms

## 🔒 Security

### Built-in Security
- **HTTPS**: Enforced secure connections
- **CSP**: Content Security Policy headers
- **XSS Protection**: React's built-in protections
- **Input Validation**: Zod schema validation

### Security Headers
```
Content-Security-Policy: default-src 'self'
X-Content-Type-Options: nosniff
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
```

## 📚 Documentation

### Template Guides
- **[Customization Guide](docs/customization.md)** - How to customize the template
- **[Component Guide](docs/components.md)** - Using and creating components
- **[Deployment Guide](docs/deployment.md)** - Deployment instructions
- **[Contributing Guide](CONTRIBUTING.md)** - How to contribute

### Architecture
- **[System Architecture](docs/architecture/system-overview.md)** - High-level architecture
- **[Component Architecture](docs/architecture/components.md)** - Component structure
- **[State Management](docs/architecture/state.md)** - State patterns

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

### Development Workflow
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run tests and linting
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [shadcn/ui](https://ui.shadcn.com/) for the amazing component library
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [React](https://reactjs.org/) for the powerful UI library
- [Vite](https://vitejs.dev/) for the lightning-fast build tool
- [TypeScript](https://www.typescriptlang.org/) for type safety

## 📞 Support

### Community Support
- **GitHub Issues**: [Report issues](https://github.com/tiation/tiation-react-template/issues)
- **Discussions**: [Join discussions](https://github.com/tiation/tiation-react-template/discussions)
- **Email**: [tiatheone@protonmail.com](mailto:tiatheone@protonmail.com)

### Enterprise Support
For enterprise support, custom implementations, or consulting:
- **Email**: [tiatheone@protonmail.com](mailto:tiatheone@protonmail.com)
- **Subject**: "Enterprise Template Support"

---

<div align="center">
  <p>Built with ❤️ by the Tiation Team</p>
  <p>
    <a href="https://github.com/tiation/tiation-react-template/generate">🚀 Use This Template</a> •
    <a href="https://tiation.github.io/tiation-react-template">🌐 Live Demo</a> •
    <a href="https://github.com/tiation/tiation-react-template/issues">🐛 Report Bug</a> •
    <a href="https://github.com/tiation/tiation-react-template/discussions">💬 Discussions</a>
  </p>
</div>

## 🌟 Star History

⭐ **Star this repository** if you find it useful!

[![Star History Chart](https://api.star-history.com/svg?repos=tiation/tiation-react-template&type=Date)](https://star-history.com/#tiation/tiation-react-template&Date)

