# Frontend Application

A modern React application built with TypeScript, Vite, and SWC, optimized for performance and developer experience.

## 🚀 Tech Stack

### Core Technologies
- **Framework**: React 19
- **Language**: TypeScript 5.7
- **Build Tool**: Vite 6.3
- **Compiler**: SWC (Speedy Web Compiler)
- **Styling**: SCSS

### Development Tools
- **Linting**: ESLint 9.22
- **Type Checking**: TypeScript
- **Code Quality**: ESLint plugins
  - React Hooks
  - React Refresh
  - TypeScript ESLint

## 🏗️ Project Structure

```
Application/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/         # Page components
│   ├── assets/        # Static assets
│   ├── styles/        # SCSS styles
│   ├── utils/         # Utility functions
│   ├── hooks/         # Custom React hooks
│   ├── services/      # API services
│   ├── types/         # TypeScript types
│   ├── constants/     # Constants
│   ├── context/       # React context
│   └── layouts/       # Layout components
├── public/            # Public assets
├── node_modules/      # Dependencies
├── package.json       # Dependencies and scripts
├── vite.config.ts    # Vite configuration
├── tsconfig.json     # TypeScript configuration
└── eslint.config.js  # ESLint configuration
```

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm or yarn

## 🛠️ Installation

1. Install dependencies:
```bash
npm install
# or
yarn install
```

2. Start development server (runs on port 3001):
```bash
npm run dev
# or
yarn dev
```

## 🔧 Configuration

### Development Server
- Port: 3001 (configured in vite.config.ts)
- Hot Module Replacement (HMR)
- Fast Refresh
- TypeScript strict mode

### Build Configuration
- Code splitting
- Tree shaking
- Asset optimization
- Source maps

### TypeScript Configuration
- Strict mode enabled
- Path aliases configured
- Type checking in development

## 🧪 Testing

Run linting:
```bash
npm run lint
# or
yarn lint
```

## 🚀 Performance Features

### SWC Optimizations
- 20x faster compilation than Babel
- Zero-config TypeScript support
- Built-in JSX transform
- Automatic React Refresh
- Tree-shaking optimization
- Fast development server startup

### Code Splitting
- Route-based code splitting
- Component lazy loading
- Dynamic imports

### Asset Optimization
- Image optimization
- CSS minification
- JavaScript minification
- Source maps for debugging

## 📦 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

## 🔄 Development Workflow

1. Create feature branch
2. Implement changes
3. Run linting
4. Test changes
5. Create pull request

## 📝 Best Practices

### Code Organization
- Feature-based folder structure
- Reusable components
- Custom hooks for logic
- Type-safe API integration

### Performance
- Lazy loading
- Code splitting
- Memoization
- Virtualization for lists

### TypeScript
- Strict type checking
- Interface definitions
- Type utilities
- Generic components

## 📞 Support

For support, please open an issue in the repository.
