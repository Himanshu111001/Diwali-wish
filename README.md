# 🪔 Diwali Wish — Interactive Festive Web App

A radiant, mobile-first Diwali greeting web app featuring traditional glowing terracotta diyas, GPU-accelerated canvas fireworks, ambient audio, synthesized sound effects, and personalized WhatsApp sharing.

![Diwali Greeting Preview](https://images.unsplash.com/photo-1605647540924-852290f6b0d5?auto=format&fit=crop&w=1200&q=80)

---

## ✨ Features

- **🪔 Handcrafted SVG Terracotta Diyas:** Three animated clay lamps with layered radial gradients, dynamic flame flicker, halo glow, and breathing animations.
- **🎆 60–120 FPS Canvas Fireworks:** High-performance particle physics engine using additive color blending (`globalCompositeOperation = 'lighter'`) for lag-free glowing fireworks on mobile and desktop.
- **🎵 Dual Audio Experience:**
  - Ambient background festival audio loop.
  - Zero-latency Web Audio API synthesized chimes and crackles upon tapping or clicking.
  - Clear `🔊` / `🔇` sound status indicator with automatic mobile audio unlocking.
- **📱 Mobile-First Responsive Design:** Modern glassmorphic aesthetic built with CSS clamp fluid typography, dynamic viewport height (`100dvh`), and safe area insets for iOS/Android notches.
- **✍️ Personalized Wishes & Sharing:**
  - Dynamic URL parameters: `?from=YourName` and `?to=RecipientName`.
  - Built-in "Personalize Your Wish" modal to instantly change sender name and copy the unique link.
  - One-tap WhatsApp sharing that includes the live website URL and personalized name.
- **⚡ Ultra Lightweight:** Decoupled external audio asset, reducing the initial HTML page payload from 6.4 MB down to ~22 KB for instant page loads.
- **♿ Accessible & SEO Ready:** Semantic HTML, Open Graph tags for WhatsApp link previews, inline SVG Diya favicon, and polite ARIA announcements.

---

## 🚀 Getting Started

Clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/Himanshu111001/Diwali-wish.git
cd Diwali-wish
```

Simply serve the directory with any static server or open `index.html` directly:

```bash
# Using Python
python -m http.server 3000

# Using Node.js
npx serve .
```

---

## 🌐 Deploy on Vercel

Deploy instantly with Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FHimanshu111001%2FDiwali-wish)

Or via Vercel CLI:
```bash
npx vercel
```

---

## 🎨 Personalization URL Examples

- `https://your-domain.vercel.app/?from=Himanshu`
- `https://your-domain.vercel.app/?to=Priya&from=Himanshu`

---

## 📜 License

MIT License — Feel free to customize and share warmth and happiness this Diwali season! 🪔✨
