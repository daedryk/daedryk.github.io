This is beyond your scope of imagination.

Legal notice:


# Custom Web Fonts Directory 🎨

This repository hosts custom OpenType fonts (`.otf`) utilized for the personal fan and historical project layout at **daedryk.github.io**. This document provides an overview of each font's origin, intended design language, license restrictions, and official legal disclaimers.

---

## 🌌 1. Triglavian Completed
* **File:** `triglavian-completed.otf`
* **Design Origin:** *EVE Online* (MMORPG) by **CCP Games**
* **Creator/Compiler:** Nicholas Antonucci (*Uriel Anteovnuecci* / *Nickosaurus*)
* **Description:** A clean, fully typed character set based on the alien typography of the Triglavian Collective. It includes parsed in-game symbols, community-decoded lore structures, and manually constructed symbols (punctuation and brackets).
* **License & Usage:** **Free for Personal/Fan Use Only.** 
  * This font is a derivative asset of CCP Games' Intellectual Property. 
  * It **cannot** be utilized in any commercial applications, behind paywalls, or for monetization.

---

## 😈 2. Daedra
* **File:** `Daedra.otf`
* **Design Origin:** *The Elder Scrolls* series (Daggerfall, Oblivion, Skyrim) by **Bethesda Softworks**
* **Creator/Compiler:** Neale Davidson (*Pixel Sagas*)
* **Description:** An occult, ceremonial script inspired by the demonic and daedric signage found within the Elder Scrolls universe. It contains a standard uppercase script mimicking the original games alongside custom "fandom-designed" numerals and weights.
* **License & Usage:** **Free for Personal Use.**
  * Distributed originally via Pixel Sagas as donationware/shareware for non-commercial layouts.
  * All underlying fictional language concepts belong to Bethesda Softworks.

---

## 📜 3. Vinodolski Zakon NH
* **File:** `Vinodolski_Zakon_NH.otf`
* **Design Origin:** Historical Croatian Glagolitic Script (16th-century copy of the 1288 Law Codex of Vinodol)
* **Creator/Compiler:** Nenad Hančić (*Glagoljica Fonts & Co.*)
* **Description:** A beautiful historical recreation font modeled after 16th-century Glagolitic chancery script. It features an extensive collection of automatic ligatures and contextual alternates to properly render authentic Glagolitic formatting. It includes a mapped Latin-to-Glagolitic system to translate direct text inputs instantly.
* **License & Usage:** **Free for Personal/Non-commercial Projects.**
  * Created and distributed freely by Nenad Hančić for the preservation and digital execution of traditional Glagolitic calligraphy.

---

## 🛠️ Web Implementation Example

To maintain lightweight network performance and avoid hotlinking, these fonts are hosted directly inside the repository. Convert them to modern `.woff2` packages and implement them via CSS using the syntax below:

```css
@font-face {
  font-family: 'Triglavian';
  src: url('fonts/triglavian-completed.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Daedra';
  src: url('fonts/Daedra.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'VinodolskiZakon';
  src: url('fonts/Vinodolski_Zakon_NH.woff2') format('woff2');
  font-weight: normal;
  font-style: normal;
}
```

---

## ⚖️ Legal Disclaimers & Fair Use Notice

This repository and its corresponding website (**daedryk.github.io**) are completely non-commercial, non-profit fan installations. 

* **EVE Online Assets:** *Triglavian Completed* relies on intellectual properties owned by **CCP Games**. No copyright infringement is intended. 
* **Elder Scrolls Assets:** *Daedra* relies on imagery and aesthetic signage owned by **Bethesda Softworks / ZeniMax Media**.
* All rights to characters, names, places, and visual designs remain with their respective legal owners. If you are a rights holder or asset creator and wish to have an asset adjusted or removed, please open an Issue.

