# 📝 Plan de Îmbunătățire CV - Căldăraru Denisa Elena

## 🎯 Obiectiv
Transformarea CV-ului actual într-o versiune **curată, concisă și profesională** de **maxim 1 pagină** (sau 2 pagini dacă e absolut necesar).

---

## 📊 Analiza CV-ului Actual

### ❌ Probleme Identificate

| Secțiune | Problema | Impact |
|----------|----------|--------|
| **Summary** | Paragraf prea lung (~100 cuvinte) | Recrutorii nu citesc blocuri mari de text |
| **Proiecte (8)** | Prea multe proiecte, prea detaliate | CV depășește 2 pagini |
| **Voluntariate (7)** | Fiecare cu 2 bullet points | Repetitiv, ocupă spațiu |
| **Skills** | Format tabel bun, dar "levels" sunt subiective | Poate fi simplificat |

### ✅ Puncte Forte
- Experiență tehnică diversificată (CAD, Web, Robotics)
- Proiecte reale cu link-uri GitHub
- Certificări relevante (CCNA, ECDL, Adobe Workshop)
- Voluntariat consistent în domeniu

---

## 🔧 Plan de Acțiune

### Pasul 1: Summary → 2-3 rânduri MAX
**Înainte:** Paragraf lung cu multe adjective
**După:** "Industrial Engineering student at UPB with hands-on experience in web development (React, Astro), CAD software, and robotics. Active FTC volunteer and tech community contributor."

### Pasul 2: Proiecte → Top 3-4 cele mai relevante
**Păstrează:**
1. ✅ Neural Network Blender Script Generator (cel mai recent, AI/ML)
2. ✅ Eneba Website Clone (React + TypeScript)
3. ✅ SongApp - Fourier Transform (Python, team project)
4. ✅ Educational Website - Vectors (arată inițiativă)

**Elimină sau combină:**
- ❌ Rainbow Six Siege (similar cu alte proiecte web)
- ❌ Butcher Website (poate fi menționat în skills)
- ❌ Dimension Calculator (mai puțin relevant pentru web/software)
- ❌ Lockdown Protocol (similar cu alte proiecte Astro)

### Pasul 3: Voluntariate → Grupează și condensează
**Înainte:** 7 intrări separate cu descrieri
**După:** 
```
Volunteer Experience (2023-2025)
- FTC Romania: Alumni Referee & Robot Inspector (5 regional/national events)
- ASPOLI Events: RiseUp, StartUp, Robo-Fest, POLIJobs, EFest (coordination, graphic design, event organization)
```

### Pasul 4: Skills → Elimină "levels", grupează mai bine
**Înainte:** Tabel cu (Beginner/Intermediate/Advanced)
**După:** Grupuri simple:
- **Web:** React, TypeScript, Astro, Svelte, HTML/CSS, JavaScript
- **CAD/3D:** AutoCAD, CATIA, SolidWorks, Fusion 360, Blender
- **Programming:** Python, C/C++, Java
- **Tools:** Arduino, LabVIEW, Git, Vivado

### Pasul 5: Certificări → Păstrează dar condensează
- Combină într-o singură linie unde e posibil

---

## 📐 Structura Nouă Propusă (1 pagină)

```
┌─────────────────────────────────────────────┐
│  HEADER (Nume, Contact, GitHub, LinkedIn)   │ ~10%
├─────────────────────────────────────────────┤
│  SUMMARY (2-3 rânduri)                      │ ~5%
├─────────────────────────────────────────────┤
│  EDUCATION (2 intrări)                      │ ~10%
├─────────────────────────────────────────────┤
│  TECHNICAL SKILLS (grupate pe categorii)    │ ~15%
├─────────────────────────────────────────────┤
│  PROJECTS (3-4 cu 1-2 bullet points)        │ ~35%
├─────────────────────────────────────────────┤
│  CERTIFICATIONS (lista scurtă)              │ ~10%
├─────────────────────────────────────────────┤
│  VOLUNTEERING (grupat)                      │ ~15%
└─────────────────────────────────────────────┘
```

---

## 📁 Fișiere de Creat

1. `cv/cv_original.tex` - CV-ul original (backup)
2. `cv/cv_simplified.tex` - Versiunea nouă, curată
3. `cv/Poza.jpg` - Poza de profil (trebuie adăugată manual)

---

## 🛠️ Dependențe Necesare

### Opțiunea A: Overleaf (Recomandat)
- Nu necesită instalare locală
- Upload fișierul `.tex` pe [overleaf.com](https://overleaf.com)

### Opțiunea B: Instalare Locală (Windows)
```powershell
# Instalare MiKTeX (distribuție LaTeX pentru Windows)
winget install MiKTeX.MiKTeX

# SAU descarcă manual de la: https://miktex.org/download
```

### Pachete LaTeX necesare (se instalează automat în MiKTeX):
- fontawesome5
- tcolorbox
- geometry
- hyperref
- graphicx

---

## ✅ Checklist Final

- [ ] Summary redus la 2-3 rânduri
- [ ] Proiecte reduse la 3-4 (cele mai impactante)
- [ ] Fiecare proiect are maxim 2 bullet points
- [ ] Voluntariate grupate într-o singură secțiune compactă
- [ ] Skills fără niveluri (Beginner/Advanced)
- [ ] CV încape pe 1 pagină (maxim 2)
- [ ] Testat compilarea în Overleaf
- [ ] Link-uri GitHub funcționale
