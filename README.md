# Sarthak Nandre - Portfolio Website

A modern, responsive portfolio website for a Data Analytics & Business Intelligence professional built with Next.js, Tailwind CSS, and Framer Motion.

## Features

- **Fully Responsive Design** - Works seamlessly on all devices
- **Modern UI/UX** - Clean, minimal, and professional design
- **Smooth Animations** - Subtle scroll animations using Framer Motion
- **SEO Optimized** - Proper metadata and semantic HTML
- **Accessible** - WCAG compliant with proper ARIA labels
- **Performance Optimized** - Fast loading and efficient rendering

## Tech Stack

- **Framework**: Next.js 14 (App Router)
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **Language**: TypeScript

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm or yarn package manager

### Installation

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

```bash
npm run build
npm start
```

## Project Structure

```
portfolio/
├── app/
│   ├── layout.tsx       # Root layout with metadata
│   ├── page.tsx         # Main page
│   └── globals.css      # Global styles
├── components/
│   ├── Header.tsx       # Navigation header
│   ├── Footer.tsx       # Footer component
│   ├── Section.tsx      # Reusable section wrapper
│   ├── Hero.tsx         # Hero section
│   ├── About.tsx        # About section
│   ├── Skills.tsx       # Skills section
│   ├── Experience.tsx   # Experience timeline
│   ├── Projects.tsx     # Projects showcase
│   ├── Education.tsx    # Education section
│   └── Contact.tsx      # Contact form
└── public/              # Static assets
```

## Customization

### Update Personal Information

Edit the following files to update personal information:
- `components/Hero.tsx` - Name, headline, and intro
- `components/About.tsx` - Professional summary
- `components/Experience.tsx` - Work experience
- `components/Projects.tsx` - Project details
- `components/Education.tsx` - Education details
- `components/Contact.tsx` - Contact information
- `components/Footer.tsx` - Footer links

### Update Colors

Modify the color scheme in `tailwind.config.ts` under the `accent` color definition.

### Add Resume PDF

Place your resume PDF in the `public` folder and update the link in `components/Hero.tsx`.

## Deployment

This project is ready to deploy on:
- **Vercel** (recommended for Next.js)
- **Netlify**
- **AWS Amplify**
- Any platform supporting Next.js

## License

This project is private and proprietary.

