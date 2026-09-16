# Kassia Naturals — Single-Origin Kerala Spices

A modern, high-performance web experience for **Kassia Naturals** (a brand of Rari & Co. Pvt Ltd), showcasing single-origin Kerala spices sourced directly from the Western Ghats and Idukki high ranges.

---

## 🌿 Highlights & Key Features

- **Hero Sequence Animation**: Smooth canvas-based frame animation synchronized with scroll via GSAP ScrollTrigger (supports both desktop and mobile frame sets).
- **Interactive Spices Showcase**: Bento-style interactive switchers and 3D depth-tilted cards for all five flagship spices.
- **Process & Traceability Walkthrough**: Interactive visual walkthrough illustrating the journey from cultivation in Kerala to lab certification and packing.
- **Responsive & Accessible**: Optimized for all viewports (mobile, tablet, desktop) with semantic HTML5 tags and high-contrast typography.
- **Lightweight & Fast**: Pure HTML5, Vanilla CSS, and modern JavaScript with no bloated runtime dependencies.

---

## 📁 Project Structure

```text
KASSIA/
├── assets/                  # Images, brand logos, videos, and product visuals
│   ├── cardamom_*.webp
│   ├── cinnamon_*.webp
│   ├── cloves_*.webp
│   ├── ginger_*.webp
│   ├── pepper_*.webp
│   ├── process_*.webp/.jpg
│   ├── spice_*.webp
│   ├── company.jpeg
│   ├── logo.webp
│   ├── our story.mp4
│   └── story_landscape.webp
├── css/
│   └── style.css            # Global stylesheet with design system and components
├── js/
│   ├── main.js              # GSAP animations, interactions, and carousel logic
│   └── particles-config.js  # Particles.js configuration
├── DESTOP/                  # Desktop hero sequence frames (1280x720 WebP)
├── MOB1/                    # Mobile hero sequence frames (720x1280 WebP)
├── index.html               # Main landing page
├── contact.html             # Trade desk & contact inquiry page
├── story.html               # Brand origin & narrative page
├── product-cardamom.html    # Green Cardamom product detail page
├── product-cinnamon.html    # Cassia Cinnamon product detail page
├── product-cloves.html      # Whole Cloves product detail page
├── product-ginger.html      # Dried Ginger product detail page
├── product-pepper.html      # Tellicherry Black Pepper product detail page
├── server.ps1               # Lightweight PowerShell HTTP server script
├── start-server.bat         # One-click launcher for Windows
└── README.md                # Project documentation
```

---

## 🚀 How to Run Locally

### Option 1: One-Click Launcher (Windows)
Double-click `start-server.bat` in the project root to start the local server and navigate to `http://localhost:8000`.

### Option 2: PowerShell
Open PowerShell in the project directory and run:
```powershell
powershell -ExecutionPolicy Bypass -File .\server.ps1 -Port 8000
```

### Option 3: Python Built-in Server
```bash
python -m http.server 8000
```

### Option 4: Node.js (npx)
```bash
npx serve .
```

---

## 📄 Pages

- `index.html`: Landing page featuring hero scroll sequence, featured spices, process cards, and company overview.
- `story.html`: The origin narrative, heritage, sourcing philosophy, and video showcase.
- `contact.html`: Inquiries form, corporate credentials, trade desk contact details, and location.
- `product-*.html`: Dedicated showcase pages for each spice grade, aroma notes, origin metrics, and grading specs.

---

## 📜 License & Copyright

&copy; 2026 Rari & Co. Private Limited. All rights reserved.
