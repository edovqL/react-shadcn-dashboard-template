<div align="center">
  <h1>🚀 React Shadcn Dashboard Template</h1>
  <p><strong>A modern, responsive dashboard template crafted with Shadcn/ui and Vite</strong></p>
  <p><em>Built with accessibility, responsiveness, and developer experience in mind</em></p>
  <p>
    <img src="https://img.shields.io/badge/React-18.2-61DAFB?style=flat-square&logo=react" alt="React">
    <img src="https://img.shields.io/badge/TypeScript-5.4-blue?style=flat-square&logo=typescript" alt="TypeScript">
    <img src="https://img.shields.io/badge/Vite-5.2-646CFF?style=flat-square&logo=vite" alt="Vite">
    <img src="https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=flat-square&logo=tailwindcss" alt="Tailwind CSS">
    <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">
  </p>
</div>

## ✨ Features

- **🎗️ Modern UI** - Built with Shadcn/ui components for beautiful, consistent design
- **🌙 Dark/Light Mode** - Built-in theme switching with system preference detection
- **📱 Fully Responsive** - Mobile-first design that works on all screen sizes
- **♿ Accessible** - WCAG compliant with proper ARIA labels and keyboard navigation
- **🏗️ Multiple Layouts** - Sidebar and header layouts with collapsible navigation
- **🗺️ 15+ Pages** - Pre-built pages including dashboard, auth, settings, and more
- **🧩 Custom Components** - Extended components beyond the base Shadcn/ui library
- **📨 Form Validation** - React Hook Form with Zod schema validation
- **📈 Data Visualization** - Charts and graphs with Recharts integration
- **🔍 Advanced Search** - Command palette with fuzzy search capabilities
- **🎯 Type Safe** - Full TypeScript support with strict type checking
- **⚡ Fast Development** - Vite for lightning-fast development and builds

## 🏗️ Tech Stack

### **Frontend Framework**
- **[React 18.2](https://react.dev)** - Modern React with concurrent features
- **[TypeScript 5.4](https://www.typescriptlang.org)** - Static type checking
- **[Vite 5.2](https://vitejs.dev)** - Next generation build tool

### **UI & Styling**
- **[Shadcn/ui](https://ui.shadcn.com)** - Re-usable components built with Radix UI
- **[Tailwind CSS 3.4](https://tailwindcss.com)** - Utility-first CSS framework
- **[Radix UI](https://radix-ui.com)** - Unstyled, accessible components
- **[Tabler Icons](https://tabler.io/icons)** - Beautiful SVG icons

### **Routing & Forms**
- **[React Router 6.22](https://reactrouter.com)** - Declarative routing
- **[React Hook Form 7.51](https://react-hook-form.com)** - Performant forms
- **[Zod 3.22](https://zod.dev)** - TypeScript-first schema validation

### **Data & Visualization**
- **[TanStack Table 8.16](https://tanstack.com/table)** - Powerful data tables
- **[Recharts 2.12](https://recharts.org)** - Chart library for React
- **[Day.js 1.11](https://day.js.org)** - Lightweight date library

### **Development Tools**
- **[ESLint 8.55](https://eslint.org)** - JavaScript/TypeScript linting
- **[Prettier 3.2](https://prettier.io)** - Code formatting
- **[PostCSS 8.4](https://postcss.org)** - CSS transformation

## 📋 Prerequisites

- **Node.js** 18.0 or later
- **pnpm** (recommended), npm, or yarn package manager
- **Git** for version control

## 🚀 Quick Start

### 1. Clone Repository

```bash
git clone https://github.com/alpredovandy/react-shadcn-dashboard-template.git
cd react-shadcn-dashboard-template
```

### 2. Install Dependencies

```bash
pnpm install
# or
npm install
# or
yarn install
```

### 3. Start Development Server

```bash
pnpm dev
# or
npm run dev
# or
yarn dev
```

### 4. Open in Browser

Visit [http://localhost:5173](http://localhost:5173) to view the application.

## 📜 Available Scripts

| Script | Description | Usage |
|--------|-------------|-------|
| `dev` | Start development server | `pnpm dev` |
| `build` | Build for production | `pnpm build` |
| `preview` | Preview production build | `pnpm preview` |
| `lint` | Run ESLint | `pnpm lint` |
| `format` | Format code with Prettier | `pnpm format` |
| `format:check` | Check code formatting | `pnpm format:check` |

## 🗺️ Pages & Routes

### **Dashboard Pages**
- **Dashboard** (`/`) - Overview with charts and metrics
- **Tasks** (`/tasks`) - Task management interface
- **Chats** (`/chats`) - Chat/messaging interface
- **Apps** (`/apps`) - Application management
- **Settings** (`/settings`) - User preferences and configuration

### **Authentication Pages**
- **Sign In** (`/sign-in`) - User login
- **Sign In Alt** (`/sign-in-2`) - Alternative sign in design
- **Sign Up** (`/sign-up`) - User registration
- **Forgot Password** (`/forgot-password`) - Password recovery
- **OTP Verification** (`/otp`) - Two-factor authentication

### **Error Pages**
- **404 Not Found** (`/404`) - Page not found
- **General Error** (`/500`) - Server error
- **Maintenance** (`/maintenance`) - Under maintenance
- **Unauthorized** (`/401`) - Access denied

### **Utility Pages**
- **Extra Components** (`/extra-components`) - Component showcase
- **Coming Soon** - Placeholder for future features

## 🏗️ Project Structure

```
react-shadcn-dashboard-template/
├── src/
│   ├── components/           # Reusable components
│   │   ├── ui/               # Shadcn/ui components
│   │   ├── custom/           # Custom extended components
│   │   ├── app-shell.tsx     # Application shell
│   │   ├── nav.tsx           # Navigation components
│   │   ├── sidebar.tsx       # Sidebar navigation
│   │   ├── theme-provider.tsx # Theme context
│   │   └── theme-switch.tsx  # Theme toggle
│   ├── pages/               # Page components
│   │   ├── dashboard/        # Dashboard pages
│   │   ├── auth/             # Authentication pages
│   │   ├── errors/           # Error pages
│   │   ├── tasks/            # Task management
│   │   ├── chats/            # Chat interface
│   │   ├── apps/             # Applications
│   │   └── settings/         # Settings pages
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utility functions
│   ├── types/              # TypeScript type definitions
│   ├── assets/             # Static assets
│   ├── router.tsx          # React Router configuration
│   ├── main.tsx            # Application entry point
│   └── App.tsx             # Root component
├── public/               # Public static files
├── components.json       # Shadcn/ui configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── vite.config.ts        # Vite configuration
├── tsconfig.json         # TypeScript configuration
└── package.json          # Project dependencies
```

## 🎯 Key Components

### **Layout Components**
- **AppShell** - Main application wrapper with navigation
- **Sidebar** - Collapsible sidebar navigation
- **TopNav** - Header navigation with user menu
- **Breadcrumb** - Navigation breadcrumbs

### **Custom Components**
- **PasswordInput** - Enhanced password input with visibility toggle
- **PinInput** - PIN/OTP input component
- **Layout** - Flexible layout wrapper
- **Button** - Extended button component with variants

### **UI Components**
- All Shadcn/ui components (Avatar, Badge, Calendar, Card, etc.)
- Form components with validation
- Data table with sorting and filtering
- Command palette for search
- Toast notifications

## 🌍 Browser Support

| Browser | Version |
|---------|--------|
| Chrome | ≥ 90 |
| Firefox | ≥ 88 |
| Safari | ≥ 14 |
| Edge | ≥ 90 |

## 🎨 Customization

### **Theme Configuration**

Modify `tailwind.config.js` to customize colors, fonts, and spacing:

```js
module.exports = {
  theme: {
    extend: {
      colors: {
        primary: {
          50: '#eff6ff',
          500: '#3b82f6',
          900: '#1e3a8a',
        },
      },
    },
  },
}
```

### **Adding New Components**

```bash
# Add new Shadcn/ui components
npx shadcn-ui@latest add [component-name]

# Example: Add sheet component
npx shadcn-ui@latest add sheet
```

### **Component Variants**

Use `class-variance-authority` for creating component variants:

```tsx
import { cva } from 'class-variance-authority'

const buttonVariants = cva(
  'inline-flex items-center justify-center',
  {
    variants: {
      variant: {
        default: 'bg-primary text-primary-foreground',
        outline: 'border border-input',
      },
      size: {
        default: 'h-10 px-4 py-2',
        sm: 'h-9 px-3',
        lg: 'h-11 px-8',
      },
    },
  }
)
```

## 🚢 Deployment

### **Static Hosting (Recommended)**

**Netlify:**
```bash
# Build command: pnpm build
# Publish directory: dist

# Deploy to Netlify
npm i -g netlify-cli
netlify deploy --prod --dir=dist
```

**Vercel:**
```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel --prod
```

**GitHub Pages:**
```bash
# Install gh-pages
npm install --save-dev gh-pages

# Add to package.json scripts
"homepage": "https://yourusername.github.io/repo-name",
"predeploy": "pnpm build",
"deploy": "gh-pages -d dist"

# Deploy
npm run deploy
```

### **Docker Deployment**

```dockerfile
FROM node:18-alpine AS builder
WORKDIR /app
COPY package*.json ./
RUN npm ci --only=production
COPY . .
RUN npm run build

FROM nginx:alpine
COPY --from=builder /app/dist /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```

## 🔧 Development Guidelines

### **Code Style**
- Use TypeScript for type safety
- Follow ESLint and Prettier configurations
- Use meaningful component and variable names
- Keep components focused and reusable

### **Component Best Practices**
- Use forwardRef for components that need ref forwarding
- Implement proper TypeScript interfaces
- Use className merging with `cn()` utility
- Add JSDoc comments for complex components

### **Performance**
- Use React.lazy() for code splitting
- Implement proper memoization with useMemo/useCallback
- Optimize bundle size with tree shaking
- Use proper image optimization

## 🤝 Contributing

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### **Development Setup**

```bash
# Clone the repository
git clone https://github.com/your-username/react-shadcn-dashboard-template.git
cd react-shadcn-dashboard-template

# Install dependencies
pnpm install

# Start development server
pnpm dev

# Run linting
pnpm lint

# Format code
pnpm format
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **[Shadcn](https://github.com/shadcn)** - For the incredible component library
- **[Radix UI](https://www.radix-ui.com)** - For accessible, unstyled components
- **[Tailwind CSS](https://tailwindcss.com)** - For the utility-first CSS framework
- **[Vite Team](https://vitejs.dev)** - For the blazing fast build tool
- **[React Team](https://react.dev)** - For the amazing framework
- **[Tabler Icons](https://tabler.io)** - For beautiful, consistent icons
