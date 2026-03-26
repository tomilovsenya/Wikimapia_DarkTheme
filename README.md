# Wikimapia Dark Theme

A clean, modern **CSS-only** dark mode override for Wikimapia. This theme replaces the dated aesthetic with a deep, high-contrast interface designed for better readability during night use and reduced eye strain.

---

### 🎨 Features

* **Custom Color Palette:** Uses a centralized CSS variable system (`--surface-1`, `--surface-2`, `--text-muted`, etc.) for consistent colors across the UI.
* **Modern Typography:** Removes outdated text shadows and cleans up link styling.
* **Enhanced UI Components:** Refreshed accordions, menus, and the "Place Info" panel.
* **Material Design Integration:** Swaps default browser icons for modern Material Symbols.
* **Custom Image Viewer:** A fully restyled lightbox/swipebox for a seamless viewing experience.

---

### 🛠 Installation

#### Option 1: Stylebot (Recommended)
1.  Install the [Stylebot extension](https://stylebot.dev/) for Chrome, Firefox, or Edge.
2.  Navigate to [Wikimapia.org](https://wikimapia.org).
3.  Open Stylebot and click **Edit CSS**.
4.  Paste the contents of `theme.css` into the editor.

#### Option 2: Stylus
1.  Install the [Stylus extension](https://add0n.com/stylus.html).
2.  Create a new style for the domain `wikimapia.org`.
3.  Paste the CSS and save.

---

### 📂 Project Structure

* **Core UI:** Global overrides for the map interface and panels.
* **Place Info:** Styles for location trees, categories, and descriptions.
* **Image Viewer:** Custom styling for the `#swipebox-overlay`.
* **Icons:** Integration of custom font-family glyphs for navigation.

---

### 🔧 Customization

You can easily change the look by modifying the root variables at the top of the file:

```css
:root {
  --surface-2: #1e1e1e; /* Secondary backgrounds */
  --surface-3: #2d2d2d; /* Hover states */
  --text-muted: #aaaaaa; /* Less important text */
  --link: #3498db;      /* Primary link color */
}
