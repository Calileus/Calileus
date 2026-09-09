# Calileus | Software Architect

**Visit my professional portfolio:** https://calileus.github.io/Calileus

---

**M.Sc. Mathematics | Software Architect & Lead Developer**  
Based in **Querétaro, Mexico** | Building dependable systems for high-stakes software

### Professional Profile

I'm a software architect specializing in **modern C++, automotive systems, and quality-driven engineering**. With **10+ years** of experience, I design and deliver complex software solutions with emphasis on:

- **Architecture & Design** — Component boundaries, distributed systems, event-driven architecture, cross-platform decomposition
- **Quality as a System** — MISRA C/C++, static analysis, code review discipline, automated quality gates (60% review reduction)
- **Delivery Leadership** — Team scaling, repository governance, technical direction, mentoring

**Current Role:** Software Architect & Lead Developer, AUMOVIO/Continental (Radar Sensor Logic Model)  
**Key Achievement:** Led 14-person multidisciplinary team from quotation through production deployment to North American market; 58+ releases shipped, nominated for AUMOVIO Awards 2026

### Background
- **M.Sc. Mathematics** — Universidad Nacional Autónoma de México (UNAM)
- **B.Sc. Applied Mathematics** — Universidad Autónoma de Querétaro
- **Recent Certifications:** Google AI Essentials (2026), Secure Software Design Specialization (2025), Parallel & GPU Programming CUDA (2023), EF SET English C1 Advanced (2024)

### Technical Stack
`C++20/17` • `C` • `Python` • `CMake` • `GitHub Actions` • `Docker` • `Protobuf` • `Linux` • `Windows`

### Connect & Explore
- **Portfolio Website:** https://calileus.github.io 
- **LinkedIn:** [calileus](https://www.linkedin.com/in/calileus)
- **GitHub:** [@Calileus](https://github.com/Calileus)
- **HackerRank:** [Calileus](https://www.hackerrank.com/profile/calileus)
- **GitHub Organizations:**
  - [@ObsidianHonorCoders](https://github.com/ObsidianHonorCoders) — Engineering community for modern C++ and software quality
  - [@CalileusLab](https://github.com/CalileusLab) — Specialized engineering sandbox for high-performance systems
- **Academic:** [Mexican Logic Olympiad](https://olimpiada-logica.webnode.mx/) — Academic Manager & Facilitator

---

## Open-Source & Community Projects

### Obsidian Honor Coders (OHC)
<img width="204" height="204" alt="OHC-logo" src="https://github.com/user-attachments/assets/77a1c3c6-674d-49ce-bc4c-067affe9f69f" />

> **"Sharp Logic. High RPM. Unshakable Integrity."**

A software engineering organization focused on **modern C++ development**, **engineering standards**, and **collaborative development practices**.

**Key Projects:**
- **[ohc-template-repo](https://github.com/ObsidianHonorCoders/ohc-template-repo)** — Production-ready C++ template with Dev Containers, CMake, GoogleTest, GitHub Actions, and automated quality controls. Demonstrates repository governance standards applied to production systems.
- **[inheritance-chess](https://github.com/ObsidianHonorCoders/inheritance-chess)** — A modular C++20 chess engine exploring polymorphic design, component-based architecture, event-driven systems. Shows architectural tradeoffs between elegance and performance applied to complex systems.
- **[easy-examples](https://github.com/ObsidianHonorCoders/easy-examples)** — Learning and reference repository: Win32 programming, multithreading, smart pointers, STL best practices.

**OHC Principles:**
| Virtue | Technical Meaning | The OHC Action |
| :--- | :--- | :--- |
| **Integrity** | Pure Logic | We do not ship "hacks" that we aren't willing to fix later. |
| **Courage** | Refactoring | We are not afraid to delete bad code, even if we wrote it ourselves. |
| **Discipline** | Documentation | We document our systems so the next engineer can understand intent. |
| **Loyalty** | Peer Review | We protect the main branch like a fortress; no bug passes review. |

---

### CalileusLab
<img width="204" height="204" alt="calileuslab-org" src="https://github.com/user-attachments/assets/0abffeaf-5518-4599-8e3c-2534b1b3962e" />

> **"Sharp Logic. High Performance. Relentless Innovation."**

A specialized engineering sandbox where raw ideas transform into **high-performance software**. Experimental ground for:
- High-performance computing patterns
- Modern C++ techniques at scale
- Systems architecture research
- Production engineering practices

**Philosophy:** *"I don't just write code; I architect systems."*

---

## 📖 About This Repository

This repository contains the source code for my **professional portfolio website** built with modern web technologies.

### 🎨 Featured Portfolio Website

Visit **[calileus.github.io](https://calileus.github.io)** to see:
- ✨ Professional impact metrics and achievements
- 💡 Architecture philosophy and approach
- 📚 Continuous learning and certifications
- 🎯 Professional testimonials from team leaders
- 💻 Open-source projects and contributions
- 🔗 Links to GitHub, LinkedIn, and professional profiles

### 🚀 Website Tech Stack

- **Astro 5** — Modern static site builder for optimal performance
- **Tailwind CSS 3** — Utility-first styling with custom components
- **TypeScript** — Type-safe development
- **GitHub Pages** — Automatic deployment via GitHub Actions
- **Responsive Design** — Mobile-optimized interface

---

## 🔧 Development & Deployment

### Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build locally
npm run preview
```

### Project Structure

```
portfolio/
├── .github/workflows/deploy.yml  # GitHub Actions deployment
├── public/                       # Static assets
│   ├── profile.jpg               # Profile photo
│   ├── favicon.svg               # Site favicon
│   └── og-image.svg              # Social share image
├── src/
│   ├── layouts/Layout.astro      # Base HTML layout
│   ├── pages/index.astro         # Main portfolio page
│   └── styles/global.css         # Global styles & Tailwind components
├── astro.config.mjs              # Astro configuration
├── tailwind.config.mjs           # Tailwind CSS configuration
├── tsconfig.json                 # TypeScript configuration
├── eslint.config.mjs             # Linting configuration
└── package.json                  # Dependencies & scripts
```

### Customization

**Portfolio Content:**
Edit `src/pages/index.astro` to customize:
- Hero section (title, description, CTA buttons)
- Impact metrics and achievements
- Architecture philosophy
- Certifications and learning
- Experience timeline
- Testimonials
- Project showcase

**Styling:**
Modify `tailwind.config.mjs` to change colors, fonts, and spacing. Current theme uses:
- Colors: Emerald/Teal accent with neutral backgrounds
- Font: Space Grotesk (display) + JetBrains Mono (code)
- Architecture: Dark mode optimized for readability

**Images & Assets:**
- Replace `public/profile.jpg` with your professional photo (400×400px recommended)
- Update `public/og-image.svg` for social media sharing
- Ensure favicon matches your brand

### Deployment

**Automatic Deployment (GitHub Pages):**
1. Push to `main` branch
2. GitHub Actions workflow automatically builds and deploys
3. Site live at `https://calileus.github.io` (or your custom domain)

**Manual Deployment:**
```bash
npm run build
# Deploy the `dist/` folder to any static hosting provider
```

**Custom Domain:**
Add `CNAME` file to `/public/` with your domain, then update DNS settings.

---

## 📋 Scripts Available

```bash
npm run dev      # Start dev server at http://localhost:3000
npm run build    # Build for production
npm run preview  # Preview production build locally
npm run check    # Run type checking with Astro
npm run lint     # Run ESLint on src directory
```

---

## 🔐 Quality & Standards

- ✅ **Accessible** — WCAG 2.1 AA compliance, semantic HTML, ARIA labels
- ✅ **Performant** — Optimized images, minimal JavaScript, fast page loads
- ✅ **Responsive** — Mobile-first design, tested on all breakpoints
- ✅ **SEO-Ready** — Meta tags, Open Graph, structured data
- ✅ **Type-Safe** — TypeScript throughout codebase
- ✅ **Linted** — ESLint configuration for code consistency

---

## 📄 License

MIT License — Feel free to adapt this template for your own portfolio.
