# Michael High School & Marceline Junior College — Website Redesign

A free, modern redesign of the official website for **Michael High School & Marceline Junior College of Arts, Science & Commerce**, Kurla West, Mumbai. Managed by the Catholic Education Society (CES), established 1979.

Built with **Astro + Tailwind CSS** — outputs pure static HTML with no JavaScript runtime. Fast, accessible, and deployable anywhere.

---

## Pages

| Route | Page |
| :--- | :--- |
| `/` | Home |
| `/about` | About Us — Overview & Virtual Tour |
| `/about/mission-vision` | Mission & Vision |
| `/about/general-information` | General Information |
| `/about/anthem` | Anthem Song |
| `/about/staff` | Staff Directory |
| `/about/committees` | Committees |
| `/facilities` | Facilities |
| `/accreditation` | Accreditation |
| `/fee-structure` | Fee Structure |
| `/activities` | Activities Overview |
| `/activities/scholastic` | Scholastic Activities |
| `/activities/co-scholastic` | Co-Scholastic Activities |
| `/activities/departments-clubs` | Departments & Clubs |
| `/contact` | Contact Us |

---

## Tech Stack

- **[Astro](https://astro.build)** — static site generator, zero JS runtime
- **[Tailwind CSS v4](https://tailwindcss.com)** — utility-first styling
- **Google Fonts** — Playfair Display (headings) + Inter (body)

---

## Design

- Primary colour: `#1c5d38` (institutional green, matched to the school building)
- Accent: `#f5a623` (gold)
- Mobile-first responsive layout
- WCAG AA accessible — skip link, `aria-*` attributes, keyboard navigation, `focus-visible` rings
- School crest used as favicon (16px, 32px, 180px apple-touch-icon)

---

## Commands

| Command | Action |
| :--- | :--- |
| `npm install` | Install dependencies |
| `npm run dev` | Start dev server at `localhost:4321` |
| `npm run dev -- --port 3000` | Start on a custom port |
| `npm run build` | Build to `./dist/` |
| `npm run preview` | Preview production build locally |

---

## Deploy

The `./dist` folder after `npm run build` is a self-contained static site. Drop it on:

- **Netlify** — drag & drop the `dist` folder at netlify.com/drop
- **Vercel** — `vercel --prod` from the project root
- **cPanel / shared hosting** — upload contents of `dist` to `public_html`

---

## Credits

Designed and built by **Zaid** as a free community contribution to Michael High School, Kurla West, Mumbai.
