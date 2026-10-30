<div align="center">

# STYLE

**Effortless style. Everyday.**

A clean, editorial fashion landing page, crafted with care for detail and a refined, minimal look.

[**View Live Demo**](https://sara-nejat.github.io/style/) · [**Repository**](https://github.com/sara-nejat/style)

<br>

<img src="style/assets
/img/Screenshot (63).png" alt="Style website, hero section preview" width="100%">

</div>

<br>

## About

**Style** is a responsive fashion website built around a quiet, luxurious aesthetic: warm neutral tones, generous whitespace, bold editorial typography and large, confident imagery.

The goal of this project was to translate a premium fashion-brand feel into a fast, lightweight front end, with no heavy frameworks, just thoughtful HTML and utility-first CSS.

## Highlights

- **Editorial hero section** with oversized typography layered behind the model, for a magazine-style first impression
- **Fully responsive**, with separate, optimized hero images for mobile and desktop
- **Refined navigation** with a clean header, minimal icons (search, account, cart) and a clear call to action
- **Warm, cohesive palette** of cream, beige and black that keeps the whole page elegant
- **Semantic HTML** (`header`, `nav`, `main`, `section`, `article`) for clarity and accessibility
- **Smooth hover states** and subtle transitions on interactive elements
- **Multilingual-ready typography**, with Latin and Persian fonts bundled locally

## Built With

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure |
| **Tailwind CSS** | Utility-first styling and responsive design |
| **Node.js / npm** | Tailwind build tooling |
| **GitHub Pages** | Hosting |

**Typography:** Jost · Vazirmatn · Shabnam

## Project Structure

```
style/
├── assets/
│   ├── css/
│   │   ├── input.css      # Tailwind source
│   │   └── output.css     # Compiled stylesheet
│   ├── font/              # Locally hosted fonts
│   └── img/               # Hero and collection imagery
├── index.html
├── package.json
└── README.md
```

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/sara-nejat/style.git
cd style
```

**2. Install dependencies**

```bash
npm install
```

**3. Build the CSS**

```bash
npx @tailwindcss/cli -i ./assets/css/input.css -o ./assets/css/output.css --watch
```

**4. Open the site**

Open `index.html` in your browser, or use a local server such as the VS Code *Live Server* extension.

## Design Notes

- **Mobile first:** layouts are designed for small screens and scale up through Tailwind's `md` and `lg` breakpoints.
- **Art direction:** the hero uses different images per device, so the composition stays strong at every size.
- **Restraint:** a limited palette and a small set of type styles keep the interface calm and premium.

## Roadmap

- [ ] Collections grid (Men, Women, Accessories)
- [ ] Product cards with hover effects
- [ ] Newsletter sign-up
- [ ] Footer with social links
- [ ] Dark mode

## Author

**Sara Nejat**
GitHub: [@sara-nejat](https://github.com/sara-nejat)

---

<div align="center">

Made with care · Style, everyday.

</div>
