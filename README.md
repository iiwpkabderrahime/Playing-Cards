# Uno Cards CSS Illustration

A sleek, interactive web component that recreates **Uno Playing Cards** using pure HTML and CSS. This project focuses on utilizing CSS Flexbox for layout and advanced CSS transforms for the signature "tilted" card design.

## 🚀 Live Interaction
The cards feature a **3D-style hover effect**:
* **Front Side:** Displays the card number (1, 2, 3, or 9) in its respective color (Green, Red, Blue, Yellow).
* **Hover State:** The card flips/rotates, the background turns black, and the center design changes to display the "UNO" logo.

## ✨ Key Features
* **Pure CSS Shapes:** No images used. The card's internal oval and styling are handled via `border-radius` and `transform`.
* **Flexbox Layout:** The `main` container uses `flex-wrap: wrap` and `justify-content: center` to ensure the cards are responsive and center-aligned on all screen sizes.
* **Dynamic Hover Effects:** * `rotateY(180deg)` for a flip animation.
    * Pseudo-elements (`::after`) used to swap text from numbers to "UNO" dynamically.
* **Typography:** Uses the "Inter" font family for a clean, modern look.

## 🛠️ Built With
* **HTML5:** For the structural layout.
* **CSS3:** Featuring:
    * Flexbox
    * CSS Transitions & Transforms
    * Pseudo-classes (`:hover`) and Pseudo-elements (`::after`)
    * Variable-like class mapping (`.card1`, `.card2`, etc.)

## 📂 Project Structure
```text
├── index.html   # The structural layout of the cards
└── styles.css   # The styling, animations, and color logic
```
<img width="567" height="899" alt="{2114E074-359E-41A9-85E4-B8F19D97852A}" src="https://github.com/user-attachments/assets/a4d11eab-8e74-4da6-9d58-8dfdfcd2f07a" />

