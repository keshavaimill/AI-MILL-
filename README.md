# AI Mill - Accelerating Intelligence for Every Business

AI Mill is a boutique AI consulting firm that transforms complex workflows into accessible, powerful tools for businesses. We specialize in delivering enterprise-grade AI solutions that drive measurable results and accelerate digital transformation.

## 🌟 About AI Mill

Our mission is to democratize advanced artificial intelligence by transforming complex workflows into accessible, powerful tools for individuals and teams. We empower creators, businesses, and innovators to build, automate, and scale AI-driven solutions with speed, clarity, and confidence.

## 🚀 Our Solutions

### 1. Boutique AI Consulting
Custom AI strategies and solutions tailored to your unique business challenges. We provide strategic planning, custom solutions, and expert guidance to help you navigate your AI transformation journey.

### 2. AI Marketing Platform
Automated marketing campaigns powered by intelligent AI across all channels. Features include multi-channel automation, advanced analytics, and real-time optimization to maximize your marketing ROI.

### 3. AI Claims Assistant
Streamline insurance claims processing with our intelligent automation system. Achieve 60-80% time reduction in claims processing while maintaining high accuracy and significant cost savings.

### 4. AI Legal & Tax Assistant
Intelligent automation for legal research and tax compliance. Our platform provides powerful research tools, compliance monitoring, and advanced document analysis capabilities.

## 🛠️ Technology Stack

This website is built with modern web technologies:

- **Vite** - Next-generation frontend build tool
- **React 18** - UI library for building interactive interfaces
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn-ui** - High-quality React component library
- **Framer Motion** - Animation library for React
- **React Router** - Client-side routing

## 📦 Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <YOUR_GIT_URL>
cd ai-mill-visions-main
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables (optional):
```bash
cp env.example .env
```

For the contact form to work, configure EmailJS credentials in your `.env` file:
- `VITE_EMAILJS_SERVICE_ID`
- `VITE_EMAILJS_TEMPLATE_ID`
- `VITE_EMAILJS_PUBLIC_KEY`

4. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the port shown in your terminal).

### Build for Production

```bash
npm run build
```

The production-ready files will be in the `dist` directory.

### Preview Production Build

```bash
npm run preview
```

## 📁 Project Structure

```
├── src/
│   ├── components/      # Reusable React components
│   │   ├── ui/         # shadcn-ui components
│   │   ├── Hero.tsx    # Hero section component
│   │   ├── Navigation.tsx
│   │   ├── Footer.tsx
│   │   └── ...
│   ├── pages/          # Page components
│   │   ├── Index.tsx   # Home page
│   │   ├── About.tsx   # About page
│   │   ├── Contact.tsx # Contact page
│   │   └── solutions/  # Solution pages
│   ├── assets/         # Images and static assets
│   ├── hooks/          # Custom React hooks
│   ├── lib/            # Utility functions
│   └── services/       # API and service integrations
├── public/             # Public static files
└── ...
```

## 🎨 Features

- **Responsive Design** - Fully responsive across all devices
- **Modern UI/UX** - Beautiful, intuitive interface with smooth animations
- **Performance Optimized** - Fast loading times and optimized bundle size
- **SEO Friendly** - Proper meta tags and semantic HTML
- **Accessible** - Built with accessibility best practices
- **Contact Form** - Integrated EmailJS for contact form submissions

## 📝 Development

### Linting

```bash
npm run lint
```

### Code Style

The project uses ESLint for code quality. Make sure to follow the existing code style and conventions.

## 🚢 Deployment

This project can be deployed to any static hosting service:

- **Vercel** - Recommended for React applications
- **Netlify** - Easy deployment with continuous integration
- **GitHub Pages** - Free hosting for public repositories
- **AWS S3 + CloudFront** - Enterprise-grade hosting

For deployment, simply run `npm run build` and upload the `dist` directory to your hosting provider.

## 📧 Contact

For inquiries about our services or to discuss your AI transformation needs, please visit our [Contact Page](https://your-domain.com/contact) or reach out through the contact form on the website.

## 📄 License

This project is proprietary software. All rights reserved.

---

**AI Mill** - Transforming businesses through intelligent automation and AI innovation.
