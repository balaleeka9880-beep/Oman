# Oman
# Shopify AI Agent — Landing Page Design Prompt

---

## 🎯 Task

Design a **full Shopify landing page** that exactly follows the wireframe layout below, using the provided brand color palette. The page should feel **premium, earthy, and organic** — think artisanal goods, farm-to-table, or natural lifestyle products.

---

## 🗂️ Page Structure (follow this exact order top → bottom)

### 1. NAVIGATION BAR
- Logo on the left
- Navigation links in the center (Home, Collections, About, Contact)
- Cart icon + CTA button ("Shop Now") on the right
- Background: `--color-primary` (#3D5A27)
- Text & links: `--color-white`
- CTA button: `--color-secondary` (#C95C2E) with white text

---

### 2. HERO BANNER
- Full-width section with a **large background image** (nature/landscape/product lifestyle shot)
- Overlay with a dark gradient using `--color-primary-dark` at 60% opacity
- Centered headline (large, bold, serif font)
- Sub-headline below it
- One primary CTA button: `--color-accent` (#E8A820) background, dark text
- One secondary ghost/outline button in white

---

### 3. COLLECTION LIST SLIDER
- Horizontal scrollable slider with **left/right arrow controls**
- Each card shows:
  - Collection image (square or 4:3 ratio)
  - Collection name (bold)
  - Arrow link ("Explore →")
- Pagination dots below
- Card background: `--color-white`
- Card border: 2px solid `--color-primary-light`
- Active dot: `--color-secondary`
- Section background: light warm off-white or `#F5F0E8`

---

### 4. FEATURED COLLECTION — BESTSELLER
- Section title: **"Featured Collection"** (centered, serif)
- Sub-title: **"Bestseller Collection"** (smaller, muted)
- **2×2 product grid** (4 products):
  - Each product: image placeholder + product name + price ($100)
- "ADD TO CART" button centered below the grid
- Product card hover: subtle lift shadow + `--color-accent` border
- Button: `--color-primary` background, white text
- Section background: `--color-white`

---

### 5. NEWSLETTER SIGNUP
- Centered section with heading: **"Stay in the Loop"**
- Short description line
- Inline form: **Email input** + **"Subscribe" button**
- Input border: `--color-primary`
- Button: `--color-secondary` (#C95C2E), white text
- Section background: `--color-primary-light` or a warm texture overlay

---

### 6. FOOTER
- Dark background: `--color-primary-dark` (#2E4420)
- Text: `--color-white`
- Three columns:
  - **Contact** — address, phone, email
  - **About Us** — short links list
  - **Social Media** — icons (Facebook, Twitter, Pinterest, Instagram)
- Bottom bar: copyright line, centered

---

## 🎨 Color Palette

```css
:root {
  --color-primary:        #3D5A27;
  --color-primary-light:  #4A6B2F;
  --color-primary-dark:   #2E4420;

  --color-secondary:      #C95C2E;
  --color-secondary-light:#D97043;
  --color-secondary-dark: #A84824;

  --color-accent:         #E8A820;
  --color-accent-light:   #F0BC45;
  --color-accent-dark:    #C8901A;

  --color-white:          #FFFFFF;
}
```

---

## ✍️ Typography

- **Headings**: Serif font (e.g., Playfair Display, Lora, or similar) — warm, editorial feel
- **Body / UI text**: Clean humanist sans-serif (e.g., DM Sans, Nunito, or similar)
- Headline size: 48–64px on desktop
- Body size: 16–18px

---

## 💫 Animations & Interactions

- Hero: fade-in + subtle upward slide on load
- Collection cards: horizontal scroll with smooth easing
- Product cards: lift on hover (translateY -4px + box-shadow)
- CTA buttons: background color transition on hover (0.3s ease)
- Newsletter button: scale pulse on hover

---

## 📱 Responsive Behavior

- Mobile: stack all sections vertically
- Collection slider: swipeable on touch
- Product grid: 2 columns on tablet, 1 column on mobile
- Navigation: collapses to hamburger menu on mobile

---

## 🧩 Design Personality

**Earthy · Artisanal · Trustworthy · Warm**

This is NOT a cold tech brand. Every element should feel handcrafted and intentional:
- Slightly rounded corners (8–12px) on cards and buttons
- Generous padding and whitespace
- Warm shadows (use `rgba(61, 90, 39, 0.15)` for green-tinted shadows)
- Decorative dividers (thin `--color-accent` lines between sections)