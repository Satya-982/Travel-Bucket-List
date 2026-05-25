# 🕉️ Sacred Trails & World Wonders

> **A Pilgrim's Journal & Explorer's Diary** — A beautifully designed Travel Bucket List app with a dedicated Devotional section for Hindu sacred sites and a Travel section for world destinations.

---

## 📸 Preview

| Devotional — Jyotirlingas | Devotional — Pancharamas | Travel Destinations |
|:---:|:---:|:---:|
| 12 sacred Shiva temples | 5 Andhra Pradesh shrines | India & International cards |

---

## ✨ Features

### 🛕 Devotional Section
- **Jyotirlingas** — All 12 sacred Jyotirlingas displayed as individual cards with images, location, significance, mantra, best time to visit, and travel directions
- **Pancharamas** — All 5 Pancharama Shiva temples of Andhra Pradesh with detailed descriptions and travel info
- **Visited / Not Visited Toggle** — Mark each temple as visited directly from the detail modal; status persists via `localStorage`
- **Pilgrimage Progress Bar** — Live progress tracker showing how many temples you've visited out of 12 (Jyotirlingas) and 5 (Pancharamas)
- **Completion Celebration** — Special message when you complete all temples in a category

### ✈️ Travel Section
- **12 Destinations** — Curated cards for Indian and International destinations
- **Region Filter** — Filter by All / India / International
- **Per-card Detail Modal** — Each destination opens with a full image, famous foods list, and must-visit places
- **Responsive card grid** — Works on all screen sizes

### 🎨 UI/UX
- Dark theme with dual color identity — **Saffron/Gold** for Devotional, **Teal/Ocean** for Travel
- Cinzel + EB Garamond + Inter font pairing for a sacred-editorial aesthetic
- Smooth hover animations, modal transitions, and entrance effects
- Fully responsive — mobile, tablet, and desktop
- Custom scrollbar and atmospheric gradient backgrounds

---

## 🗂️ Project Structure

```
sacred-trails-world-wonders/
│
├── index.html          # Complete single-file application
└── README.md           # This file
```

> The entire app lives in a single `index.html` — no build tools, no dependencies, no backend required.

---

## 🚀 Getting Started

### Option 1 — Open directly
Just download `index.html` and open it in any modern browser. No server needed.

### Option 2 — Clone & run
```bash
git clone https://github.com/YOUR_USERNAME/sacred-trails-world-wonders.git
cd sacred-trails-world-wonders
# Open index.html in your browser
```

### Option 3 — Live Server (VS Code)
```bash
# Install Live Server extension in VS Code
# Right-click index.html → "Open with Live Server"
```

---

## 🛕 Devotional Data Covered

### Jyotirlingas (12)
| # | Name | Location |
|---|------|----------|
| 1 | Somnath | Prabhas Patan, Gujarat |
| 2 | Mallikarjuna | Srisailam, Andhra Pradesh |
| 3 | Mahakaleshwar | Ujjain, Madhya Pradesh |
| 4 | Omkareshwar | Khandwa, Madhya Pradesh |
| 5 | Kedarnath | Rudraprayag, Uttarakhand |
| 6 | Bhimashankar | Pune, Maharashtra |
| 7 | Kashi Vishwanath | Varanasi, Uttar Pradesh |
| 8 | Trimbakeshwar | Nashik, Maharashtra |
| 9 | Vaidyanath | Deoghar, Jharkhand |
| 10 | Nageshwar | Near Dwarka, Gujarat |
| 11 | Rameshwaram | Pamban Island, Tamil Nadu |
| 12 | Grishneshwar | Ellora, Maharashtra |

### Pancharamas (5)
| # | Name | Location |
|---|------|----------|
| 1 | Amararama | Amaravati, Guntur District, AP |
| 2 | Somasrama | Bhimavaram, West Godavari, AP |
| 3 | Kumararama | Samalkot, East Godavari, AP |
| 4 | Ksheerarama | Palakollu, West Godavari, AP |
| 5 | Draksharama | Draksharamam, East Godavari, AP |

---

## 🌍 Travel Destinations Covered

### 🇮🇳 India
- Goa, Rajasthan, Kerala, Himachal Pradesh, Andaman Islands, Varanasi

### 🌐 International
- Paris (France), Bali (Indonesia), Dubai (UAE), Maldives, Japan, Switzerland, Singapore

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| HTML5 | Structure and semantic markup |
| CSS3 | Animations, grid layout, custom properties, backdrop-filter |
| Vanilla JavaScript | Tab switching, modal system, visited state, localStorage |
| Google Fonts | Cinzel · EB Garamond · Inter |
| Unsplash / Wikipedia | Travel and temple images (CDN-loaded) |

**Zero dependencies. Zero frameworks. Zero build step.**

---

## 💾 Data Persistence

Visited status for all temples is saved in the browser's `localStorage` under the key `visitedPlaces`. This means:
- Your progress is remembered across browser sessions
- Data is stored locally on your device — no server, no account needed
- Clearing browser data will reset your progress

---

## 📱 Responsive Breakpoints

| Screen | Layout |
|--------|--------|
| Desktop (>1024px) | 3–4 column card grid |
| Tablet (640–1024px) | 2 column card grid |
| Mobile (<640px) | Single column, stacked layout |

---

## 🙏 Acknowledgements

- Temple data sourced from historical and religious references
- Travel information compiled from cultural and tourism sources
- Images via Unsplash (travel) and Wikimedia Commons (temples)
- Inspired by the rich Hindu pilgrimage tradition of South and Central India

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

Feel free to fork, customize, and add your own bucket list destinations!

---

## 🤝 Contributing

Pull requests are welcome! Some ideas for contribution:
- Add more travel destinations
- Add more devotional categories (Char Dham, Shakti Peethas, Divya Desams)
- Add a notes/journal feature per destination
- Add visited date tracking
- Add map integration

---

<div align="center">
  <b>Made with 🕉️ and ✈️ — for every soul that seeks both the sacred and the spectacular</b>
</div>
