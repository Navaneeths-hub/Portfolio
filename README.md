# Navaneeth Mohan — Product Designer Portfolio

A minimalist, high-craft product design portfolio built with **React 19**, **Vite 8**, and **Tailwind CSS v4**. Highlights in-depth product design case studies for physical kiosks, e-commerce try-on plugins, and spatial AI retail systems.

---

## 🚀 Quick Start (Local Development)

### 1. Install Dependencies
```bash
npm install
```

### 2. Start Dev Server
```bash
npm run dev
```
Open [http://localhost:5173](http://localhost:5173) in your browser.

### 3. Production Build
```bash
npm run build
npm run preview
```

---

## 📁 Repository Structure

```plaintext
final/
├── .github/workflows/deploy.yml # Automated GitHub Pages deployment
├── public/
│   ├── assets/                  # High-resolution project screen captures and renders
│   └── favicon.svg              # Portfolio monogram favicon
├── src/
│   ├── App.tsx                  # Main portfolio UI & case studies
│   ├── index.css                # Tailwind CSS v4 and typography
│   ├── main.tsx                 # React application entrypoint
│   └── vite-env.d.ts            # TypeScript Vite declarations
├── index.html                   # HTML shell with meta tags & SEO configuration
├── package.json                 # Project dependencies & scripts
├── tsconfig.json                # TypeScript configuration
├── vite.config.ts               # Vite build config with relative base path
└── .gitignore                   # Ignores node_modules, build dist, and cache
```

---

## 🌐 How to Upload to GitHub

### Option 1: Using Git Terminal (Recommended)

1. Open your terminal in this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio release"
   git branch -M main
   ```
2. Create a new empty repository on [GitHub](https://github.com/new) (e.g. `portfolio`).
3. Connect your local repository and push:
   ```bash
   git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
   git push -u origin main
   ```

### Option 2: Using GitHub Desktop
1. Open **GitHub Desktop**.
2. Go to **File** → **Add Local Repository...** and select this folder.
3. Click **Publish repository** to push it to your GitHub account.

---

## ⚡ How to Host It Online for Free

### 1. GitHub Pages (Zero Config)
This project includes an automated GitHub Actions deployment workflow:
1. Push your repository to GitHub (steps above).
2. On GitHub, navigate to your repo's **Settings** → **Pages**.
3. Under **Build and deployment** → **Source**, select **GitHub Actions**.
4. The site will automatically build and publish to `https://<YOUR-USERNAME>.github.io/<YOUR-REPO-NAME>/`.

### 2. Vercel (1-Click Deployment)
1. Go to [vercel.com](https://vercel.com) and log in with GitHub.
2. Click **Add New Project** → Import your portfolio repository.
3. Framework preset will automatically detect **Vite**.
4. Click **Deploy**. Your site will be live on a fast global CDN with a free `.vercel.app` domain.

### 3. Netlify
1. Go to [netlify.com](https://netlify.com) and log in.
2. Click **Add new site** → **Import an existing project** → connect GitHub.
3. Build command: `npm run build` | Publish directory: `dist`.
4. Click **Deploy**.

---

## ✏️ Customization Notes
- **Email Address**: Update the contact email in `src/App.tsx` (search for `mailto:`).
- **Social Links**: Replace the Twitter and Read.cv links in `src/App.tsx` (`SiteHeader` component) with your personal URLs.
- **Copyright Year**: Update the footer text at the bottom of `src/App.tsx`.
