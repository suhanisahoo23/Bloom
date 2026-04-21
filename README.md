# 🌸 Bloom — PCOS Tracker

> A beautiful, privacy-first PCOS cycle & symptom tracker. Built as a single-file HTML app — zero dependencies, zero backend, zero data leaving your device.

![Bloom PCOS Tracker](https://img.shields.io/badge/version-1.0.0-pink) ![License](https://img.shields.io/badge/license-MIT-purple) ![HTML](https://img.shields.io/badge/HTML-only-rose)

---

## ✨ Features

| Feature | Details |
|---|---|
| 📅 **Cycle Calendar** | Visual period, fertile window, and ovulation tracking with predicted days |
| 🌸 **Daily Logging** | Flow, symptoms (12+), mood, energy, stress, anxiety, focus sliders |
| 💊 **Medication Tracking** | Metformin, Inositol, supplements with checkboxes |
| 🥗 **Lifestyle Logging** | Sleep, water, exercise type & duration |
| 🌡️ **Vitals** | BBT, weight, cervical mucus, LH test results |
| 📊 **Analytics** | Cycle length history, symptom frequency, mood trends, hormone bar chart, BBT graph |
| 💧 **Hydration Tracker** | Interactive 8-glass water tracker |
| ⏰ **Reminders** | Daily medication & logging reminders with check-off |
| 🤖 **AI Insights** | PCOS-specific daily insights based on cycle phase |
| 📋 **History View** | Full table of logged entries with symptom tags |

---

## 🚀 Getting Started

### Option 1: Direct Use (Recommended)
```bash
# Clone the repo
git clone https://github.com/yourusername/bloom-pcos-tracker.git

# Open in browser — no server needed!
open index.html
```

### Option 2: GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your tracker is live at `https://yourusername.github.io/bloom-pcos-tracker`

### Option 3: Local Server
```bash
# Python
python -m http.server 3000

# Node
npx serve .
```

---

## 📁 Project Structure

```
bloom-pcos-tracker/
├── index.html          # Complete app (HTML + CSS + JS in one file)
├── README.md           # This file
└── LICENSE             # MIT
```

---

## 🗂 Pages

### Dashboard
- Morning greeting with current cycle day and phase
- 4 stat cards: Cycle Day, Next Period, Fertility Status, Meds Today
- Interactive cycle calendar with color-coded days
- Cycle phase ring visualization
- Quick symptom logger
- Mood + energy/stress sliders
- AI-powered daily insights
- Water tracker
- Today's medication reminders

### Log Today
- Date navigation (previous/next day)
- Period flow selector (None → Spotting → Light → Medium → Heavy)
- 12-symptom physical symptom grid
- Mood selector + anxiety/focus sliders
- Medication checklist
- Nutrition & lifestyle inputs (sleep, water, exercise)
- Vitals section (BBT, weight, cervical mucus, LH test)
- Free-text notes area

### Analytics
- Summary stats (avg cycle, period length, logging rate, symptom score)
- Cycle length history bar chart (6 months)
- Top symptoms frequency bars
- Mood trend chart
- Hormone levels visualization (LH, FSH, E2, Progesterone, Testosterone, Insulin, AMH)
- BBT correlation chart (32-day pattern)

### History
- Full table: date, cycle day, flow, mood emoji, symptom tags, sleep, weight

---

## 🎨 Design System

```css
--rose:   #E8687A  /* Primary — period, period-related */
--mauve:  #9B7FA6  /* Secondary — mood, hormones */
--sage:   #7AAB8A  /* Tertiary — fertility, positive */
--cream:  #FDF8F4  /* Background */
--ink:    #2A1F2D  /* Text */
```

Fonts: **Playfair Display** (headings) + **DM Sans** (body)

---

## 🔒 Privacy

**100% local.** All data exists only in your browser session. Nothing is sent to any server. No accounts, no login, no analytics, no tracking.

> To persist data across sessions, the app can be extended with `localStorage` — see the [Contributing](#contributing) section.

---

## 🌿 PCOS-Specific Features

This tracker is built specifically for people with PCOS:

- **Irregular cycle support** — handles cycles from 21–90 days
- **Androgen symptoms** — acne, hair concerns, hirsutism tracking
- **Insulin resistance indicators** — blood sugar, cravings, energy dips
- **Relevant hormones** — AMH, LH/FSH ratio, testosterone, insulin
- **PCOS medications** — Metformin, Inositol, Spironolactone presets
- **Supplement tracking** — D3, Omega-3, Zinc, Magnesium support
- **Phase-specific AI tips** — different guidance for each cycle phase

---

## 🤝 Contributing

```bash
git fork https://github.com/yourusername/bloom-pcos-tracker
git checkout -b feature/localStorage-persistence
# Make your changes
git commit -m "feat: add localStorage data persistence"
git push origin feature/localStorage-persistence
# Open a Pull Request
```

### Roadmap
- [ ] localStorage data persistence
- [ ] Export to CSV / JSON
- [ ] Custom medication presets
- [ ] Dark mode toggle
- [ ] PWA support (offline, home screen install)
- [ ] Chart.js integration for richer graphs
- [ ] Doctor appointment notes section
- [ ] Blood test result logging
- [ ] Partner / support person view

---

## 📄 License

MIT — free to use, modify, and distribute.

---

<p align="center">Made with 💜 for the PCOS community</p>
