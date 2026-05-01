# 🌿 Ritual — Habit Tracker

Minimalistický boho habit tracker jako Progressive Web App. Funguje offline, lze nainstalovat na Android i iOS přímo z prohlížeče.

## ✨ Funkce

- Týdenní mřížka s navigací mezi týdny
- Přidávání, editace a mazání návyků s emoji výběrem
- Zaškrtávání návyků pro každý den
- Denní progress kruh + týdenní statistiky a série
- Světlý / tmavý režim
- Ukládání do `localStorage` (data zůstávají v prohlížeči)
- **PWA** — funguje offline, lze nainstalovat na plochu

---

## 🚀 Nasazení na GitHub Pages

### 1. Vytvoř repository

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/TVOJE-JMENO/ritual-habits.git
git push -u origin main
```

### 2. Zapni GitHub Pages

- Jdi do **Settings → Pages**
- Source: `Deploy from a branch`
- Branch: `main`, složka: `/ (root)`
- Uložit

### 3. Hotovo!

Za ~1 minutu běží na:
```
https://TVOJE-JMENO.github.io/ritual-habits/
```

---

## 📱 Instalace na telefon

### Android (Chrome)
1. Otevři URL v Chrome
2. Zobrazí se banner „Nainstalovat Ritual" → klikni **Instalovat**
3. Nebo: tři tečky → **Přidat na plochu**

### iOS (Safari)
1. Otevři URL v Safari
2. Sdílení (čtverec se šipkou) → **Přidat na plochu**
3. Pojmenuj a potvrď

---

## 📁 Struktura projektu

```
ritual-habits/
├── index.html          # Celá aplikace (HTML + CSS + JS)
├── manifest.json       # PWA manifest
├── sw.js               # Service worker (offline podpora)
├── icons/              # Ikony pro různá zařízení
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   ├── icon-512x512.png
│   └── apple-touch-icon.png
└── README.md
```

---

## 🛠 Alternativní nasazení

### Netlify Drop (nejrychlejší)
1. Jdi na [netlify.com/drop](https://netlify.com/drop)
2. Přetáhni celou složku `ritual-habits/`
3. Hotovo — dostaneš URL okamžitě

### Vercel
```bash
npm i -g vercel
vercel
```

---

## 📝 Licence

MIT — používej jak chceš.
