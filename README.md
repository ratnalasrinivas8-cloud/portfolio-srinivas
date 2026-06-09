# Cinematic Portfolio

A high-performance personal portfolio built with Next.js 16, GSAP, Three.js, and CSS Modules.

Live: Add your deployment URL after publishing.

## Stack

| Layer      | Technology                                      |
| ---------- | ----------------------------------------------- |
| Framework  | Next.js 16.2 (App Router, React Compiler)       |
| Animations | GSAP 3 + Three.js                               |
| Styling    | CSS Modules + Tailwind v4 (tokens only)         |
| Icons      | react-icons                                     |
| Fonts      | Geist, Baloo 2, Dancing Script (via next/font)  |

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

Build for production:

```bash
npm run build
npm start
```

## Profile Data

All personal information is managed in [data/profile.json](data/profile.json).

### Core fields used by UI sections

| Field         | What it controls |
| ------------- | ---------------- |
| name          | Full name shown across hero/footer sections |
| email         | Contact email used in CTA buttons |
| tagline       | Main one-line professional summary in hero |
| description   | Short profile description in footer and summary cards |
| roles         | Short and detailed role labels |
| location      | Based location and availability text |
| available     | Toggles availability card in hero |
| bio           | About section long-form bio |
| stats         | Experience/impact counters |
| skills        | About section skill marquee |
| experience    | Work experience timeline cards |
| projects      | Projects slider cards |
| publications  | Publications panel entries |
| socials       | Social links used in hero/footer |

### Extended resume fields added in this profile

| Field          | Purpose |
| -------------- | ------- |
| phone          | Contact number for resume reference |
| languages      | Spoken languages and proficiency |
| certifications | Professional certifications list |
| honors         | Awards and recognitions |
| education      | Education timeline details |

Non-personal website copy is in [data/content.json](data/content.json).

Design tokens are in [app/globals.css](app/globals.css).

Site URL config is in [lib/siteConfig.js](lib/siteConfig.js).

## Assets

Replace files in [public/assets](public/assets) with your own media:

| File                   | Used in                  | Description |
| ---------------------- | ------------------------ | ----------- |
| about-me.mp4           | Video Intro              | Full-screen intro video |
| hero.png               | Hero Section             | Profile image |
| about.webp             | About Section, OG Image  | About photo |
| work-experience.webp   | Work Experience          | Experience background |
| footer.png             | Footer Section           | Footer transition image |
| footer-mobile.webp     | Footer Section (mobile)  | Mobile footer background |
| footer-video.mp4       | Footer Section (desktop) | Footer loop video |
| project-*.png          | Projects Section         | Project slide images |

## Deployment

Deploy on [Vercel](https://vercel.com) with zero-config.

```bash
npm i -g vercel
vercel
```

## Author

Manikanta Kumar Redrouthu

- LinkedIn: [www.linkedin.com/in/manikanta-kumar-redrouthu-98b51b1a0](https://www.linkedin.com/in/manikanta-kumar-redrouthu-98b51b1a0)
- Email: manikanta.redrouthu47@gmail.com
- Location: Tenali, Andhra Pradesh, India
