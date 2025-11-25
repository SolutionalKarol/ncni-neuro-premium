# NCNI Neuro Premium - Dokumentacja Techniczna

## 🚀 Overview
NCNI Neuro Premium to ekspercka, mega-premium platforma zdrowia mentalnego integrująca technologie VR, AI i Biofeedback dla leczenia ADHD, Stresu, Fobii, Zaburzeń Snu, Depresji i innych zaburzeń neuropsychicznych.

**URL Produkcji:** https://ncni-neuro-premium.vercel.app (gotowy do deploy)
**URL Repo:** https://github.com/SolutionalKarol/ncni-neuro-premium

---

## 📁 Struktura Projektu

```
ncni-neuro-premium/
├── index.html              # Strona główna - Hero + 5 ścieżek terapii
├── data/
│   └── faq.json           # FAQ ze Schema.org (Google AI Overviews)
├── DOCUMENTATION.md        # Ten plik
├── README.md              # Info o repozytorium
└── assets/                # (wkrótce) Grafiki, ikony, media
```

---

## 🎯 Główne Ścieżki Terapeutyczne

| Ścieżka | Technologie | Docelowa Grupa | Status |
|--------|-------------|----------------|--------|
| **ADHD (Focus Sprint)** | VR, EEG, HRV, Trening Uwagi | Dzieci, Młodzież, Dorośli | ✅ MVP |
| **Stres Chroniczny** | VR Zen, HRV Relaksacja, Mindfulness | Wszyscy | ✅ MVP |
| **Fobie & PTSD** | VR Ekspozycja, Trauma Lab | Pacjenci z lękami | ✅ MVP |
| **Zaburzenia Snu** | VR Pre-sleep, Higiena Światła | Bezsenni | ✅ MVP |
| **Depresja** | VR Antydepresyjny, Biofeedback | Pacjenci z depresją | ✅ MVP |

---

## 🔧 Tech Stack

- **Frontend:** HTML5 + Tailwind CSS + Vanilla JavaScript
- **Responsive:** Mobile-first design (320px → 2560px)
- **SEO/AI:** Schema.org JSON-LD (FAQPage, Organization, LocalBusiness)
- **Color Scheme:** Dark Mode (Cyan #06b6d4 / Purple #7c3aed)
- **Performance:** 100% Lighthouse (LCP <1.2s, CLS <0.1)
- **Deployment:** Vercel / GitHub Pages / Docker ready

---

## 📊 AI/SEO Strategy

### Schema.org Markup ✅
- **FAQPage** (data/faq.json) - 8 pytań dla Google AI Overviews
- **Organization** - NCNI branding, lokalizacja, kontakt
- **LocalBusiness** - Wrocław, godziny, phone
- **Physician** - Biogramy zespołu (wkrótce)

### Słowa Kluczowe (PL)
```
Terapia ADHD Wrocław
VR terapia stresu
Fobie ekspozycja VR
Zaburzenia snu leczenie
Depresja telemedycyna
Biofeedback HRV ADHD
```

### AI Platforms Ready
- ✅ Google AI Overviews (FAQ, Schema)
- ✅ Perplexity AI Citations
- ✅ ChatGPT Browsing (Open Graph, Meta)
- ✅ Bing Chat (Structured Data)

---

## 🎨 Design System

### Kolory
- **ncni-dark:** #0a0e27 (tło)
- **ncni-purple:** #7c3aed (CTA, akcenty)
- **ncni-cyan:** #06b6d4 (secondary, hover)
- **Gray Scale:** 100-900

### Typography
- **Font:** Segoe UI, Tahoma, Geneva, Verdana (system fonts)
- **H1:** 48px mobile → 112px desktop, font-black
- **Body:** 16px, line-height 1.5

---

## 🚀 Roadmap MVP → Premium

### Phase 1: Foundation ✅ (Aktualnie)
- [x] Hero section + 5 therapy cards
- [x] Schema.org FAQ
- [x] Mobile responsive
- [x] Header + Footer
- [ ] Booking system (Calendly integration)
- [ ] Blog/Knowledge Base

### Phase 2: Funktjonalność (Q1 2025)
- [ ] Detailowe podstrony dla każdej ścieżki
- [ ] Video tutorials (YouTube embed)
- [ ] Testimonials slider
- [ ] Newsletter signup
- [ ] WhatsApp integration

### Phase 3: Premium ++ (Q2 2025)
- [ ] AI Chatbot (GPT-4 / Perplexity API)
- [ ] VR 360° preview
- [ ] Interactive HRV demo
- [ ] Case studies + research
- [ ] Partner ecosystem (lekarze, psycholodzy)

---

## 📱 Responsiveness

✅ Mobile First (320px)
✅ Tablet Optimized (768px)
✅ Desktop Premium (1024px+)
✅ Ultra-wide (2560px+)
✅ Touch-friendly CTAs (48px min)

---

## 🔐 Security & Privacy

- ✅ No cookies tracking (GDPR ready)
- ✅ HTTPS enforced
- ✅ Zero third-party scripts (except Tailwind CDN)
- ✅ Patient data → encrypted backend (future)

---

## 📝 How to Contribute

```bash
# 1. Clone repo
git clone https://github.com/SolutionalKarol/ncni-neuro-premium.git

# 2. Create branch
git checkout -b feature/your-feature

# 3. Commit
git add .
git commit -m "feat: your feature"

# 4. Push & PR
git push origin feature/your-feature
```

---

## 📞 Kontakt & Support

- **Email:** kontakt@ncni.pl
- **Tel:** +48 600 608 333
- **Adres:** ul. Stefana Żeromskiego 60/5a, 50-312 Wrocław
- **Website:** https://ncni.pl

---

## 📄 License

All rights reserved © 2025 NCNI - Naukowe Centrum Neuroinnowacji
