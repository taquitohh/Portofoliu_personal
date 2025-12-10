# 🌐 Personal Portfolio — Căldăraru Denisa Elena
*Portofoliu Personal — Căldăraru Denisa Elena*

<div align="center">

![Astro](https://img.shields.io/badge/Astro-4.16-purple?style=for-the-badge&logo=astro&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

**Modern portfolio website + Professional LaTeX CV**

*Website portofoliu modern + CV profesional LaTeX*

[🔗 Live Demo](https://taquitohh.github.io/Portofoliu_personal) • [📄 CV PDF](#cv---versions)

</div>

---

## 📖 Description
*Descriere*

This project contains my personal portfolio, developed as a modern website with Astro and a professional CV in LaTeX format. The website showcases my experience in web development, robotics, and digital design, featuring:

*Acest proiect conține portofoliul meu personal, dezvoltat ca website modern cu Astro și un CV profesional în format LaTeX. Website-ul prezintă experiența mea în dezvoltare web, robotică și design digital, cu suport pentru:*

- 🌙 **Dark/Light Mode** — theme toggle for dark/light appearance
  *— toggle pentru temă întunecată/deschisă*
- 🌍 **Bilingual RO/EN** — content in Romanian and English
  *— conținut în română și engleză*
- 📱 **Responsive Design** — optimized for all devices
  *— optimizat pentru toate dispozitivele*
- ⚡ **Smooth Animations** — modern scroll and hover effects
  *— efecte moderne la scroll și hover*
- 🎨 **Modern Design** — purple/cyan gradient, animated cards
  *— gradient purple/cyan, carduri animate*

## 📸 Screenshots

### Hero Section
*Secțiunea Hero*

![Hero Section](./screenshots/hero.png)

### Skills & Certifications
*Skills & Certificări*

![Skills](./screenshots/skills.png)

### Dark Mode
*Modul Întunecat*

![Dark Mode](./screenshots/dark-mode.png)

> ⚠️ **Note:** Add screenshots to the `/screenshots` folder after running the project locally.
> *Adaugă screenshots în folderul `/screenshots` după ce rulezi proiectul local.*

---

## 📁 Project Structure
*Structura Proiectului*

```
Portofoliu_personal/
├── 📄 README.md              # Project documentation / Documentația proiectului
├── 📄 PLAN_CV.md             # Detailed CV plan / Plan detaliat pentru CV
├── 📄 .gitignore             # Git ignored files / Fișiere ignorate de Git
│
├── 📁 cv/                    # LaTeX CVs / CV-uri LaTeX
│   ├── cv_original.tex       # Complete CV (2+ pages) / CV complet (2+ pagini)
│   └── cv_simplified.tex     # Simplified CV (1 page) ✨ / CV simplificat (1 pagină)
│
└── 📁 website/               # Astro Website
    ├── astro.config.mjs      # Astro configuration / Configurare Astro
    ├── package.json          # npm dependencies / Dependențe npm
    ├── tsconfig.json         # TypeScript config / Configurare TypeScript
    │
    ├── 📁 public/
    │   ├── favicon.svg
    │   └── images/
    │       └── profile.jpg   # Profile picture / Poza de profil
    │
    └── 📁 src/
        ├── env.d.ts
        ├── 📁 components/
        │   ├── Navbar.astro      # Navigation + toggles / Navigare + toggles
        │   ├── Hero.astro        # Main section / Secțiune principală
        │   ├── About.astro       # About me / Despre mine
        │   ├── Skills.astro      # Skills + Certifications / Skills + Certificări
        │   ├── Projects.astro    # Projects / Proiecte
        │   ├── Volunteering.astro # Volunteering / Voluntariat
        │   └── Contact.astro     # Contact + Footer
        │
        ├── 📁 layouts/
        │   └── Layout.astro      # Main layout + global CSS / Layout principal + CSS global
        │
        └── 📁 pages/
            └── index.astro       # Main page / Pagina principală
```

---

## 🛠️ Technologies & Dependencies
*Tehnologii & Dependențe*

### Website

| Technology | Version | Description |
|------------|---------|-------------|
| [Astro](https://astro.build) | 4.16.x | Static site generator framework |
| [TypeScript](https://www.typescriptlang.org) | 5.x | Static typing for JavaScript |
| CSS Custom Properties | - | CSS variables for theming |

*| Tehnologie | Versiune | Descriere |*
*| Astro | 4.16.x | Framework static site generator |*
*| TypeScript | 5.x | Tipare statice pentru JavaScript |*
*| CSS Custom Properties | - | Variabile CSS pentru teme |*

### CV

| Technology | Description |
|------------|-------------|
| LaTeX | Document preparation system |
| [Overleaf](https://overleaf.com) | Online LaTeX editor |
| fontawesome5 | Icons (GitHub, LinkedIn, etc.) |
| tcolorbox | Colored boxes |
| geometry | Custom margins |

*| Tehnologie | Descriere |*
*| LaTeX | Sistem de pregătire documente |*
*| Overleaf | Editor online LaTeX |*

---

## 🚀 Installation & Running
*Instalare & Rulare*

### Requirements
*Cerințe*

- [Node.js](https://nodejs.org) 18+ 
- npm or yarn / *npm sau yarn*

### Steps
*Pași*

```bash
# 1. Clone the repository / Clonează repository-ul
git clone https://github.com/taquitohh/Portofoliu_personal.git
cd Portofoliu_personal

# 2. Navigate to website folder / Navighează în folderul website
cd website

# 3. Install dependencies / Instalează dependențele
npm install

# 4. Run development server / Rulează serverul de dezvoltare
npm run dev
```

Open [http://localhost:4321/Portofoliu_personal](http://localhost:4321/Portofoliu_personal) in your browser.

*Deschide [http://localhost:4321/Portofoliu_personal](http://localhost:4321/Portofoliu_personal) în browser.*

### Build for Production
*Build pentru producție*

```bash
npm run build
npm run preview
```

---

## 📝 CV - Versions
*CV - Versiuni*

### Original (`cv/cv_original.tex`)
- Complete CV with all projects and volunteering / *CV-ul complet cu toate proiectele și voluntariatele*
- 2+ pages / *2+ pagini*
- All technical details / *Toate detaliile tehnice*

### Simplified (`cv/cv_simplified.tex`) ✨ RECOMMENDED
*Simplificat — RECOMANDAT*

- Clean, professional version / *Versiune curată, profesională*
- ~1 page / *~1 pagină*
- Top 4 most relevant projects / *Top 4 proiecte cele mai relevante*
- Grouped volunteering / *Voluntariate grupate*
- Skills without levels / *Skills fără niveluri*

### Compiling CV
*Compilare CV*

#### Option 1: Overleaf (Recommended)
*Opțiunea 1: Overleaf (Recomandat)*

1. Go to [overleaf.com](https://overleaf.com) / *Mergi la overleaf.com*
2. New Project → Upload Project
3. Upload `.tex` file and `Poza.jpg` / *Încarcă fișierul .tex și Poza.jpg*
4. Click **Compile**

#### Option 2: Local
*Opțiunea 2: Local*

```bash
# Windows - install MiKTeX / instalare MiKTeX
winget install MiKTeX.MiKTeX

# Compile / Compilare
cd cv
pdflatex cv_simplified.tex
```

---

## ✨ Features
*Funcționalități*

### 🌙 Dark/Light Mode
- Saved in `localStorage` / *Salvat în localStorage*
- Toggle in navbar / *Toggle în navbar*
- Smooth transition between themes / *Tranziție smoothă între teme*

### 🌍 Language RO/EN
*Limba RO/EN*

- Fully bilingual content / *Conținut complet bilingv*
- Saved in `localStorage` / *Salvat în localStorage*
- Instant switch without reload / *Switch instant fără reload*

### 🏆 Animated Certifications
*Certificări Animate*

- Cards with shine effect on hover / *Carduri cu efect shine la hover*
- Year prominently displayed / *Anul afișat prominent*
- Certification source visible / *Sursa certificării vizibilă*
- Staggered animations on scroll / *Animații staggered la scroll*

### 📚 Skills with Sources
*Skills cu Surse*

- Each category shows where you learned it / *Fiecare categorie arată de unde ai învățat*
- Levels displayed (Advanced, Intermediate, Beginner) / *Niveluri afișate*
- Distinct colors per category / *Culori distincte per categorie*

---

## 📧 Contact

<div align="center">

| | |
|---|---|
| 📧 Email | [caldararudenisa2@email.com](mailto:caldararudenisa2@email.com) |
| 💼 LinkedIn | [Denisa Căldăraru](https://www.linkedin.com/in/denisa-căldăraru-063ba5292) |
| 🐙 GitHub | [taquitohh](https://github.com/taquitohh) |

</div>

---

## 📜 License
*Licență*

This project is for personal use. © 2025 Căldăraru Denisa Elena

*Acest proiect este pentru uz personal. © 2025 Căldăraru Denisa Elena*

---

<div align="center">

**Made with 💜 using Astro**

</div>