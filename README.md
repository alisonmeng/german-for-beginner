---

# German For Beginner
German For Beginner is a site for sharing basic German language learning materials.
It's a static site made with HTML5 and CSS3.
---

## Page Overview

| Page | Purpose / Content |
|------|--------------------|
| **index.html** | Homepage introducing the site and navigation links |
| **grammar.html** | Grammar explanations with formatted tables and anchor navigation |
| **vocabulary.html** | Themed vocabulary lists (weather, greetings, etc.) |
| **gallery.html** | Image slideshow showing humorous German learning memes |
| **resources.html** | Embedded YouTube video, recommended shows, and external learning resources |

---

## Requirement Mapping

| Requirement | Implementation |
|--------------|----------------|
| 5 pages incl. homepage, gallery, and 3 others | All 5 listed above |
| Navigation bar on every page | `<nav><ul id="navbar">…</ul></nav>` |
| Internal and external links | Internal: navbar links; External: YouTube, LinkedIn |
| At least one table | Grammar page |
| At least one list | Vocabulary and Resources pages |
| Embedded or local video | YouTube iframe on Resources page |
| CSS positioning | `position: sticky` (navbar), `fixed` (back-to-top) |
| Both inline & block elements | Inline: `<a>`, `<i>`   Block: `<div>`, `<ul>`, `<table>` |
| Separate HTML & CSS files | `styles.css` handles all presentation |
| HTML5 semantic tags | `<header>`, `<nav>`, `<main>`, `<footer>` used throughout |
| 5+ CSS3 features | `flexbox`, `clamp()`, `scroll-behavior`, `object-fit`, `box-shadow`, `transform`, `border-radius`, etc. |
| Responsive design | `clamp()` fonts, `%` and `vh` units, responsive iframe container |

---

## 🖌️ Design Notes
- **Color scheme:** adapted from [Visme color palettes](https://visme.co/blog/website-color-schemes/).  
- **Typography:** monospace for a casual learning tone; font size uses `clamp()` for responsiveness.  
- **Accessibility:** `scroll-margin-top` prevents navbar overlap on anchor jumps.  
- **Floating back-to-top:** pure CSS anchor (`href="#top"`) with smooth scroll.  

---

## 🔗 Code Reference
- Slideshow logic adapted from:  
  [W3Schools – How To Create a Slideshow](https://www.w3schools.com/howto/howto_js_slideshow.asp)  
  (structure reused, styles and sizing customised)


---