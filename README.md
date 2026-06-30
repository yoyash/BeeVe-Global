# BeeVe Global IoT Website

## Overview

**BeeVe Global IoT Website** is a premium, futuristic, responsive company website built for an IoT solutions business focused on GPS tracking, fleet management, connected devices, sensor monitoring, telematics, asset tracking, business automation, and real-time analytics.

<a href="https://beeve-global-3wzowb2os-yash7443p-1084s-projects.vercel.app/" style="display: block; text-align: center;"> Follow this link!!</a>

The website presents BeeVe Global as a modern IoT solutions company serving businesses that want to monitor, manage, secure, and optimize vehicles, devices, assets, infrastructure, and operations in real time. It includes pages and sections for IoT platform capabilities, fleet solutions, GPS tracking, AIS-140-ready tracking, cold chain monitoring, data center monitoring, HVAC monitoring, last-mile delivery, product/device enquiry, industries, insights, contact, request demo, and a mock client portal.

The design uses a dark premium interface with glassmorphism cards, animated sections, dashboard previews, mock fleet tracking, product comparison, validated forms, search overlay, newsletter signup, FAQ accordion, testimonial carousel, and conversion-focused calls to action.

---

## Technologies Used

This project is built using:

- **Node.js** — JavaScript runtime required to install packages and run the project locally.
- **Next.js** — React framework used for routing, pages, layouts, SEO metadata, and production build optimization.
- **TypeScript** — Adds type safety and improves code maintainability.
- **React** — UI library used for building reusable interactive components.
- **Tailwind CSS** — Utility-first CSS framework used for responsive styling and premium UI design.
- **Framer Motion** — Used for smooth animations, transitions, scroll reveals, hover effects, and modal animations.
- **Lucide React** — Icon library used across navigation, cards, features, products, and CTAs.
- **Recharts** — Used for dashboard-style charts and IoT data visualizations.
- **React Hook Form** — Used for fast, accessible form handling.
- **Zod** — Used for form validation schemas.
- **LocalStorage / Mock Backend** — Used to store contact forms, demo requests, product enquiries, quote requests, and newsletter submissions locally in the browser.

---

## Main Features

- Premium dark futuristic IoT company design
- Fully responsive layout for desktop, tablet, and mobile
- Sticky navigation with dropdown menus
- Mobile hamburger menu
- Search overlay
- Request demo modal
- Product enquiry modal
- Contact form with validation
- Newsletter signup
- Product listing with filters
- Product comparison table
- Interactive IoT dashboard preview
- Mock live fleet map with simulated alerts
- FAQ accordion
- Testimonial carousel
- Animated stats counters
- Scroll progress indicator
- Back-to-top button
- Floating Request Demo button
- Floating WhatsApp/contact placeholder
- SEO-friendly metadata
- Open Graph metadata
- JSON-LD schema placeholders
- Mock client portal login page
- Compliance-safe AIS-140 messaging without false certification claims

---

## Project Structure

```text
beeve-global-iot/
├── app/
│   ├── about/
│   ├── contact/
│   ├── industries/
│   ├── insights/
│   ├── platform/
│   ├── portal/
│   ├── products/
│   ├── request-demo/
│   ├── search/
│   ├── solutions/
│   ├── privacy-policy/
│   ├── terms-of-use/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── Header.tsx
│   ├── Footer.tsx
│   ├── Hero.tsx
│   ├── PlatformDashboard.tsx
│   ├── FleetMapDemo.tsx
│   ├── ProductCard.tsx
│   ├── ProductCompare.tsx
│   ├── DemoModal.tsx
│   ├── ContactForm.tsx
│   ├── FAQAccordion.tsx
│   ├── SearchOverlay.tsx
│   ├── Newsletter.tsx
│   └── many reusable UI components
├── data/
│   ├── blogs.ts
│   ├── faqs.ts
│   ├── industries.ts
│   ├── products.ts
│   ├── site.ts
│   └── solutions.ts
├── lib/
│   ├── schemas.ts
│   ├── seo.ts
│   └── utils.ts
├── public/              # Optional folder for future images, logo, icons, brochures
├── package.json
├── tailwind.config.ts
├── tsconfig.json
├── next.config.mjs
└── README.md
```

---

## Requirements

Before running the full Next.js website locally, install:

1. **Node.js LTS**
2. **npm** — normally installed automatically with Node.js
3. A code editor such as **Visual Studio Code**

Recommended Node.js version:

```bash
node -v
```

Use Node.js version **18.17 or newer**. Node.js 20 LTS or newer is recommended for better compatibility.

Check npm:

```bash
npm -v
```

---

## Local Installation

### 1. Download and Extract the Project

Download the project ZIP file and extract it.

You should get a folder like:

```text
beeve-global-iot
```

### 2. Open the Project Folder

Open the folder in VS Code or any code editor.

### 3. Open Terminal

Inside the project folder, open a terminal.

In VS Code:

```text
Terminal → New Terminal
```

Or use the shortcut:

```text
Ctrl + `
```

### 4. Install Dependencies

Run:

```bash
npm install
```

This will install Next.js, React, Tailwind CSS, Framer Motion, Recharts, Zod, React Hook Form, Lucide React, and all other required packages.

### 5. Start Development Server

Run:

```bash
npm run dev
```

After the server starts, open this URL in your browser:

```text
http://localhost:3000
```

The BeeVe Global website should now be visible locally.

---

## Available Scripts

```bash
npm run dev
```

Starts the local development server.

```bash
npm run build
```

Creates an optimized production build.

```bash
npm start
```

Starts the production server after running `npm run build`.

```bash
npm run lint
```

Runs linting checks.

```bash
npm run typecheck
```

Runs TypeScript checks without building the project.

---

## Production Build

To test the website as a production build locally:

```bash
npm run build
npm start
```

Then open:

```text
http://localhost:3000
```

---

## Deployment Option 1: Deploy on Vercel

Vercel is the easiest deployment platform for Next.js projects.

### Steps

1. Create a GitHub account if you do not already have one.
2. Create a new GitHub repository.
3. Upload/push this project to the repository.
4. Go to Vercel.
5. Sign in with GitHub.
6. Click **Add New Project**.
7. Select the BeeVe Global repository.
8. Keep the default settings:
   - Framework Preset: **Next.js**
   - Build Command: `npm run build`
   - Install Command: `npm install`
   - Output Directory: leave default
9. Click **Deploy**.

After deployment, Vercel will give you a live website URL.

Example:

```text
https://beeve-global.vercel.app
```

---

## Deployment Option 2: Deploy on Netlify

Netlify also supports Next.js hosting.

### Steps

1. Push the project to GitHub.
2. Log in to Netlify.
3. Click **Add new site**.
4. Choose **Import an existing project**.
5. Connect the GitHub repository.
6. Use these build settings:

```text
Build command: npm run build
Publish directory: .next
```

7. Deploy the site.

Note: For advanced Next.js features, Netlify may install its Next.js adapter automatically.

---

## Deployment Option 3: Deploy on Your Own Server/VPS

Use this option only if you have a server with Node.js installed.

### Steps

Upload the project to your server, then run:

```bash
npm install
npm run build
npm start
```

By default, the app runs on port `3000`.

You can use a process manager like PM2:

```bash
npm install -g pm2
pm2 start npm --name beeve-global-iot -- start
pm2 save
```

Then configure Nginx or Apache as a reverse proxy to point your domain to the app.

---

## No-Installation Preview Option

If your laptop is slow or Node.js is not installed, use the static preview version instead.

The static preview is a lightweight `index.html` file that can open directly in a browser without installing anything.

Steps:

1. Download the static preview ZIP.
2. Extract it.
3. Open the folder.
4. Double-click `index.html`.
5. The preview opens directly in Chrome, Edge, or any modern browser.

Important: The static preview is for viewing the design quickly. The full production website is the Next.js project.

---

## Form Handling and Mock Backend

This project does not use a real backend database yet.

The following submissions are saved in browser LocalStorage:

- Contact form submissions
- Request demo submissions
- Product enquiry submissions
- Quote requests
- Newsletter signups

This is useful for prototype/demo purposes.

For a real launch, connect the forms to one of the following:

- A Node.js/Next.js API route
- Supabase
- Firebase
- MongoDB
- PostgreSQL
- Airtable
- Google Sheets API
- CRM tools such as HubSpot or Zoho
- Email service such as Resend, SendGrid, or SMTP

---

## Customization Guide

### Update Company Details

Edit:

```text
data/site.ts
```

You can update:

- Company name
- Tagline
- Email
- Phone
- Address
- Presence/market focus
- Social links
- CTA links

### Update Solutions

Edit:

```text
data/solutions.ts
```

You can add or modify:

- Connected Fleet
- GPS Vehicle Tracking
- AIS-140 Tracking
- Cold Chain Monitoring
- Data Center Monitoring
- HVAC Monitoring
- Last Mile Delivery
- Asset & Sensor Monitoring

### Update Products

Edit:

```text
data/products.ts
```

You can modify product names, features, categories, use cases, industries, and comparison fields.

### Update Industries

Edit:

```text
data/industries.ts
```

You can update industry cards, problems, IoT solutions, and measurable benefits.

### Update Blog / Knowledge Centre

Edit:

```text
data/blogs.ts
```

You can add new articles or change placeholder article content.

### Update FAQs

Edit:

```text
data/faqs.ts
```

---

## Branding Notes

Suggested brand direction used in this website:

- **Primary color:** Midnight Navy `#07111F`
- **Secondary color:** Deep Blue `#0B1E36`
- **Accent color:** Electric Cyan `#00D4FF`
- **Accent color:** Teal `#00FFC2`
- **Premium accent:** Gold `#F5B942`
- **Text color:** White and soft gray

Suggested tagline used:

```text
Smart IoT. Smarter Business.
```

You can replace the placeholder logo text with a real BeeVe Global logo later.

---

## AIS-140 Compliance Note

The AIS-140 page uses safe wording such as:

```text
AIS-140-ready tracking solutions
AIS-140 compatible solutions
```

It does **not** falsely claim that BeeVe Global is certified.

Certification details and compliance documents should be added only after official proof is available.

---

## SEO Notes

The website includes SEO-friendly structure such as:

- Page-level metadata
- SEO titles and descriptions
- Proper heading hierarchy
- Open Graph metadata
- JSON-LD structured data placeholders
- Natural keywords for IoT, GPS tracking, fleet management, sensor monitoring, and business automation

Suggested important keywords:

- IoT solutions company
- GPS tracking solution
- Fleet management system
- Connected fleet
- AIS-140 GPS tracking
- Cold chain monitoring
- Data center monitoring
- HVAC monitoring
- Last mile delivery software
- Asset tracking
- Sensor monitoring
- Real-time alerts
- IoT platform India

---

## Accessibility Notes

The project includes:

- Semantic HTML sections
- Proper form labels
- Keyboard accessible buttons and links
- Modal ARIA labels
- Focus states
- Responsive mobile navigation
- Good color contrast for dark UI
- Reduced-motion handling where possible

Before final launch, test with:

- Keyboard navigation
- Screen reader tools
- Lighthouse accessibility report
- Mobile browser testing

---

## Performance Notes

The website is designed to stay fast by using:

- Component-based architecture
- Reusable data files
- Optimized Next.js routing
- Lightweight mock data
- Tailwind CSS utility classes
- No paid map API dependency
- No unnecessary backend dependency

Before launch, you can further improve performance by:

- Adding optimized images in the `public/` folder
- Using `next/image` for real images
- Compressing logo and hero graphics
- Running Lighthouse performance checks
- Removing unused placeholder sections if not required

---

## Troubleshooting

### `node` is not recognized

Node.js is not installed properly or PATH is not set.

Fix:

1. Install Node.js LTS.
2. Restart the laptop.
3. Open Command Prompt.
4. Run:

```bash
node -v
npm -v
```

### `npm` is not recognized

Reinstall Node.js LTS and make sure npm is selected during installation.

### PowerShell script error for npm

If you see an error like scripts are disabled, use Command Prompt instead of PowerShell.

Open Command Prompt and run:

```bash
npm install
npm run dev
```

### Port 3000 already in use

Run:

```bash
npm run dev -- -p 3001
```

Then open:

```text
http://localhost:3001
```

### Website is slow locally

Close other apps and browser tabs, or use the static preview file for a quick view.

---

## Recommended Next Steps Before Real Launch

Before using this as a live company website, update:

- Real BeeVe Global logo
- Real phone number
- Real email address
- Real office address
- Real product images
- Real product specifications
- Real certification/compliance documents
- Privacy Policy and Terms of Use
- Domain name
- Form backend or CRM integration
- Google Analytics / privacy-friendly analytics
- Sitemap and robots.txt
- Real client testimonials only after approval
- Real case studies only after data is available

---

## License / Usage

This project is created for BeeVe Global website development and business presentation use.

Replace placeholder content, images, contact details, and legal pages before final public launch.
