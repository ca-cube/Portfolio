<p align="center">
  <img src="public/banner.png" width="100%" alt="ACube Banner" />
</p>

# 💎 ACube — AI Systems Studio

[![Vite](https://img.shields.io/badge/Vite-747bff?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_4.0-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![TanStack](https://img.shields.io/badge/TanStack_Start-FF4154?style=for-the-badge&logo=tanstack&logoColor=white)](https://tanstack.com/)
[![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)](https://bun.sh/)

ACube is a premium, high-performance portfolio studio website designed for an AI agency. Built with a cutting-edge React stack, it focuses on delivering a "Production AI" brand identity through sophisticated animations, glassmorphism, and a dark-only aesthetic.

---

## ✨ Features

- **🚀 Performance-First**: Built on **TanStack Start** for ultra-fast SSR/Full-stack capabilities.
- **🎨 Premium Design**: 
  - Implementation of **Tailwind CSS 4.0** with custom OKLCH design tokens.
  - Custom glassmorphism, neon glow effects, and micro-animations.
  - Dark-only theme designed for high-end AI branding.
- **⚡ Interactive UI**:
  - Floating 3D-like code previews.
  - Smooth scroll-linked animations.
  - Interactive project showcase and service sections.
- **🔍 SEO & Metadata**: Fully optimized search engine presence via TanStack Router's head management.
- **📱 Fully Responsive**: Seamless experience across mobile, tablet, and desktop.

---

## 🛠️ Tech Stack

- **Framework**: [TanStack Start](https://tanstack.com/router/v1/docs/guide/start/overview) (Full-stack React)
- **Styling**: [Tailwind CSS 4.0](https://tailwindcss.com/) (using the new lightning CSS engine)
- **Type Safety**: [TypeScript](https://www.typescriptlang.org/)
- **State & Data**: [TanStack Query](https://tanstack.com/query)
- **Validation**: [Zod](https://zod.dev/) + [React Hook Form](https://react-hook-form.com/)
- **Icons**: [Lucide React](https://lucide.dev/)
- **Components**: Radix UI Radix UI primitives
- **Deploy**: Cloudflare Pages / Wrangler

---

## 🚀 Getting Started

### Prerequisites

You will need [Bun](https://bun.sh/) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Portfolio.git
   cd Portfolio
   ```

2. **Install dependencies:**
   ```bash
   bun install
   ```

3. **Start the development server:**
   ```bash
   bun dev
   ```

4. **Build for production:**
   ```bash
   bun build
   ```

---

## 📁 Project Structure

```text
src/
├── components/       # Reusable UI sections and Atomic components
├── hooks/            # Custom React hooks for business logic
├── lib/              # Shared utility functions (clsx, tailwind-merge)
├── routes/           # File-based routing (TanStack Router)
├── styles.css        # Tailwind 4 configuration & custom design tokens
└── router.tsx        # Global router configuration
```

---

## 🌐 Deployment

### Cloudflare Pages (Recommended)
This project is optimized for **Cloudflare Pages**.
```bash
bun wrangler pages deploy dist
```

### Vercel
If you prefer deploying to **Vercel**, follow these steps for a successful build:

1. **Environmental Variables**: Set `ENABLE_BUN=1` in your Vercel Project Settings to ensure the build uses Bun.
2. **Build Configuration**:
   - Build Command: `bun build`
   - Install Command: `bun install`
3. **Clean Build**: Ensure `package-lock.json` is deleted from your repository to avoid NPM/Bun conflicts.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Built with ❤️ by <b>ACube</b>
</p>
