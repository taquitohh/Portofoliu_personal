# 🌐 Portofoliu Personal — Căldăraru Denisa Elena

<div align="center">

![Astro](https://img.shields.io/badge/Astro-4.16-purple?style=for-the-badge&logo=astro&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)

**Website portofoliu modern + CV profesional LaTeX**

[🔗 Live Demo](https://taquitohh.github.io/Portofoliu_personal) • [📄 CV PDF](#cv---versiuni)

</div>

---

## 📖 Descriere

Acest proiect conține portofoliul meu personal, dezvoltat ca website modern cu Astro și un CV profesional în format LaTeX. Website-ul prezintă experiența mea în dezvoltare web, robotică și design digital, cu suport pentru:

- 🌙 **Dark/Light Mode** — toggle pentru temă întunecată/deschisă
- 🌍 **Bilingv RO/EN** — conținut în română și engleză
- 📱 **Responsive Design** — optimizat pentru toate dispozitivele
- ⚡ **Animații fluide** — efecte moderne la scroll și hover
- 🎨 **Design modern** — gradient purple/cyan, carduri animate

## 📸 Screenshots

### Hero Section
![Hero Section](./screenshots/hero.png)

### Skills & Certificări
![Skills](./screenshots/skills.png)

### Dark Mode
![Dark Mode](./screenshots/dark-mode.png)

> ⚠️ **Notă:** Adaugă screenshots în folderul `/screenshots` după ce rulezi proiectul local.

---

## 📁 Structura Proiectului

```
Portofoliu_personal/
├── 📄 README.md              # Documentația proiectului
├── 📄 PLAN_CV.md             # Plan detaliat pentru CV
├── 📄 .gitignore             # Fișiere ignorate de Git
│
├── 📁 cv/                    # CV-uri LaTeX
│   ├── cv_original.tex       # CV complet (2+ pagini)
│   └── cv_simplified.tex     # CV simplificat (1 pagină) ✨
│
└── 📁 website/               # Website Astro
    ├── astro.config.mjs      # Configurare Astro
    ├── package.json          # Dependențe npm
    ├── tsconfig.json         # Configurare TypeScript
    │
    ├── 📁 public/
    │   ├── favicon.svg
    │   └── images/
    │       └── profile.jpg   # Poza de profil
    │
    └── 📁 src/
        ├── env.d.ts
        ├── 📁 components/
        │   ├── Navbar.astro      # Navigare + toggles
        │   ├── Hero.astro        # Secțiune principală
        │   ├── About.astro       # Despre mine
        │   ├── Skills.astro      # Skills + Certificări
        │   ├── Projects.astro    # Proiecte
        │   ├── Volunteering.astro # Voluntariat
        │   └── Contact.astro     # Contact + Footer
        │
        ├── 📁 layouts/
        │   └── Layout.astro      # Layout principal + CSS global
        │
        └── 📁 pages/
            └── index.astro       # Pagina principală
```

---

## 🛠️ Tehnologii & Dependențe

### Website

| Tehnologie | Versiune | Descriere |
|------------|----------|-----------|
| [Astro](https://astro.build) | 4.16.x | Framework static site generator |
| [TypeScript](https://www.typescriptlang.org) | 5.x | Tipare statice pentru JavaScript |
| CSS Custom Properties | - | Variabile CSS pentru teme |

### CV

| Tehnologie | Descriere |
|------------|-----------|
| LaTeX | Sistem de pregătire documente |
| [Overleaf](https://overleaf.com) | Editor online LaTeX |
| fontawesome5 | Icoane (GitHub, LinkedIn, etc.) |
| tcolorbox | Boxuri colorate |
| geometry | Margini custom |

---

## 🚀 Instalare & Rulare

### Cerințe
- [Node.js](https://nodejs.org) 18+ 
- npm sau yarn

### Pași

```bash
# 1. Clonează repository-ul
git clone https://github.com/taquitohh/Portofoliu_personal.git
cd Portofoliu_personal

# 2. Navighează în folderul website
cd website

# 3. Instalează dependențele
npm install

# 4. Rulează serverul de dezvoltare
npm run dev
```

Deschide [http://localhost:4321/Portofoliu_personal](http://localhost:4321/Portofoliu_personal) în browser.

### Build pentru producție

```bash
npm run build
npm run preview
```

---

## 📝 CV - Versiuni

### Original (`cv/cv_original.tex`)
- CV-ul complet cu toate proiectele și voluntariatele
- 2+ pagini
- Toate detaliile tehnice

### Simplificat (`cv/cv_simplified.tex`) ✨ RECOMANDAT
- Versiune curată, profesională
- ~1 pagină
- Top 4 proiecte cele mai relevante
- Voluntariate grupate
- Skills fără niveluri

### Compilare CV

#### Opțiunea 1: Overleaf (Recomandat)
1. Mergi la [overleaf.com](https://overleaf.com)
2. New Project → Upload Project
3. Încarcă fișierul `.tex` și `Poza.jpg`
4. Click **Compile**

#### Opțiunea 2: Local
```bash
# Windows - instalare MiKTeX
winget install MiKTeX.MiKTeX

# Compilare
cd cv
pdflatex cv_simplified.tex
```

---

## ✨ Funcționalități

### 🌙 Dark/Light Mode
- Salvat în `localStorage`
- Toggle în navbar
- Tranziție smoothă între teme

### 🌍 Limba RO/EN
- Conținut complet bilingv
- Salvat în `localStorage`
- Switch instant fără reload

### 🏆 Certificări Animate
- Carduri cu efect shine la hover
- Anul afișat prominent
- Sursa certificării vizibilă
- Animații staggered la scroll

### 📚 Skills cu Surse
- Fiecare categorie arată de unde ai învățat
- Niveluri afișate (Advanced, Intermediate, Beginner)
- Culori distincte per categorie

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

## 📜 Licență

Acest proiect este pentru uz personal. © 2025 Căldăraru Denisa Elena

---

<div align="center">

**Made with 💜 using Astro**

</div>