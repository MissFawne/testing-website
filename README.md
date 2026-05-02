# The Canopy — Homepage v2

A new house of botanicals · Grand Cayman

## Files

```
canopy-website/
├── index.html       # Homepage markup
├── styles.css       # All styles
├── clogo.png        # Custom C logo (transparent background)
└── README.md        # This file
```

## To preview locally

Open `index.html` in any browser. All four files must sit in the same folder.

## Brand system

### Palette
- **Cream** `#F8F4EA` — background
- **Olive Forest** `#3D4A33` — type, logo, primary color
- **Sage** `#8A9A7E` — supporting
- **Dusty Rose** `#C99488` — accent (place name, prices, N° markers)

### Typography
- **Display:** Playfair Display, italic
- **Body:** Inter
- **Accent:** JetBrains Mono

All free from Google Fonts.

### Logo
PNG with transparent background. Replaces the C in "The Canopy" wordmark, baseline-aligned with tight spacing.

**PNG limitations:** Won't scale infinitely like SVG, can't be recolored via CSS. For production at scale (signage, billboards, embroidery, large print), get this traced into a layered SVG by a designer.

## Replacing placeholders

### Hero video
```html
<div class="hero-video-wrap">
  <video autoplay muted loop playsinline poster="hero-poster.jpg">
    <source src="hero.mp4" type="video/mp4">
  </video>
</div>
```

### Product images
```html
<div class="product-image">
  <img src="plants/monstera.jpg" alt="Monstera Deliciosa">
</div>
```

Aspect ratio locked to 3:4 — shoot product photos in portrait.

## Next steps before launch

1. Hero video loop — 6–10 seconds, plant in Cayman natural light
2. Product photography — 8–12 shots, identical setup, cream backdrop
3. Real product copy — names, prices, descriptions, care details
4. Payment gateway — First Atlantic Commerce (FAC) for Cayman
5. Inner pages — product detail, shop, gift cards, corporate gifting form, care guide
6. SEO meta, Open Graph, sitemap
7. Privacy policy and terms
8. Get logo as a proper layered SVG for long-term scaling
