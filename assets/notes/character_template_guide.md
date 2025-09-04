
# Fantasy Character Template Guide

This document outlines the **best unique but simple character template** for your character portfolio.

---

##  index.html (Character Overview / Lore)
**Purpose:** Immersion, story hook, visual vibe.
Think of this page like a **character intro card**.

### Sections:
- **Header**
  - Character name, tagline, or quote.
- **Portrait / Symbol Slot**
  - Placeholder now, custom art later.
- **Lore Snippets**
  - *Known As*: names, titles, aliases.
  - *Born Of*: origin, homeland, bloodline.
  - *Bearer Of*: artifact, curse, weapon, mantle.
  - *Whispers About*: rumors, legends.
- **Backstory (short)**
  - 1–3 paragraphs max.
- **Reasons to Fear/Follow/Love**
  - Bullet list (quick and easy for readers).
- **Link to Rap Sheet**
  - Button or styled link.

 *This page is short, flavorful, and image-forward.*

---

##  rapsheet.html (Detailed Dossier)
**Purpose:** Crunchy info, stats, deeper worldbuilding.
Think of this page like an **RPG stat block + lore codex**.

### Sections:
- **Attributes / Stats**
  - Strength, Agility, Intellect, Willpower (expand later).
- **Feats & Abilities**
  - Unique powers, victories, signature skills.
- **Artifacts / Relics**
  - Cursed weapons, crowns, relics (list or image slot).
- **Allies & Foes**
  - World connections → good for faction pages later.
- **Visual Reference Gallery**
  - Portraits, sigils, maps (placeholder images now).
- **Navigation**
  - Back to `index.html` | Forward to next character.

 *This page is structured, data-rich, and expandable.*

---

##  Image Slots
Leave placeholders now, swap with real art later:

```html
<img src="images/placeholder.jpg" alt="Character Portrait">
```

Or with caption:

```html
<figure>
  <img src="images/placeholder-sigil.jpg" alt="Character Sigil">
  <figcaption>Sigil of the Thorned Crown</figcaption>
</figure>
```

---

##  Future Idea: Seller / SVG Stamp
Add a seal or badge to each site, e.g. a Figma SVG now, later your own world sigil:

```html
<footer>
  <p>© 2025 The Dark Codex</p>
  <img src="assets/figma.svg" alt="Designed in Figma" class="footer-badge">
</footer>
```

---

##  Summary
- **index.html** = immersive story intro
  *(name, tagline, origin, image slot, backstory, link to rap sheet)*
- **rapsheet.html** = crunchy dossier
  *(stats, feats, artifacts, allies/foes, gallery, navigation)*

