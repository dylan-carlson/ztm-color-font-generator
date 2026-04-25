# Random Aesthetic Generator

A minimalist, high-utility web tool designed to help designers and developers generate cohesive **color palettes** and **typography pairings** instantly.

---

## 🚀 Features

- **Cohesive Palettes**: Generates 5-color schemes using Analogous, Complementary, or Monochromatic logic derived from a single base color.
- **Typography Pairings**: Hand-picked pairings of high-quality Google Fonts for professional-grade heading and body text contrast.
- **Live Preview**: An interactive preview area to visualize how your aesthetic looks in a real UI context (buttons, headlines, and body text).
- **Accessibility First**: Built-in WCAG contrast ratio checking for every color against white and black backgrounds.
- **Persistent Favorites**: Save your favorite combinations to local storage to access them later.
- **Export Options**: One-click export to **CSS Variables** or **JSON** for easy integration into your development workflow.
- **Dark Mode**: A neutral UI design that supports both light and dark system preferences.

---

## ⌨️ Keyboard Shortcuts

Speed up your workflow with global hotkeys:

| Key     | Action                                        |
| :------ | :-------------------------------------------- |
| `Space` | Generate a completely new random aesthetic    |
| `S`     | Save the current aesthetic to your Favorites  |
| `C`     | Copy the generated CSS variables to clipboard |

---

## 🛠️ Technical Implementation

This project is a **Single Page Application (SPA)** built with a focus on performance and zero dependencies:

- **Vanilla JavaScript**: No frameworks or external libraries used for logic.
- **Dynamic Font Loading**: Uses the Google Fonts API to inject selected fonts into the document head on the fly.
- **Color Mathematics**: Custom functions for HEX/HSL conversion and relative luminance calculation to ensure design accuracy.
- **Modern CSS**: Utilizes CSS Grid, Flexbox, and Custom Properties (Variables) for a responsive and theme-aware interface.

---

## 🎨 How to Use

1.  **Shuffle**: Hit the **Shuffle** button or press `Space` to see random high-contrast pairings.
2.  **Tweak**: Use the **Base Color** picker to anchor the palette to a specific brand color while maintaining the generated font pairing.
3.  **Inspect**: Click any color swatch to instantly copy its HEX code.
4.  **Save**: Click **Save** to store the aesthetic in the right-hand sidebar.
5.  **Implement**: Use **Copy CSS** to grab the code and paste it directly into your project's stylesheet.

---

## 📝 License

This project is open-source and free to use for personal or commercial projects. No attribution required, but appreciated!
