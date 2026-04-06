# 🧊 Mini-Project 02: Responsive 3D Glassmorphism & Logic Cards

This project is a deep dive into **Adaptive Engineering**, focusing on building a dual-purpose UI that transitions between "Team Directory" profiles and a "Problem of the Day" section. Engineered entirely with HTML5 and CSS3, it explores 3D space and logic-driven state management.

## 🔗 [Live Demo](https://itzlucizeal.github.io/CSS-Animation-Journey/Simple-Mini-Projects/Responsive-3D-Cards/)

---

## ✨ Key Features (Current Build)

* **Dynamic 3D Tilt Engine**: Profile cards utilize `perspective(350vh)` combined with `rotateX` and `rotateY` transforms to create a tactile, physical depth effect on hover.
* **Modern Glassmorphic UI**: High-fidelity "frozen" aesthetic achieved through `backdrop-filter: blur(1.2vh)` and alpha-channel linear gradients.
* **Advanced Parent-Child Logic**: Implements the `:has()` pseudo-class to dynamically increase background blur when specific cards or menu items are focused.
* **Atmospheric Layering**: A synchronized snow-effect overlay and `background-attachment: fixed` mountain backdrop create a deep, immersive user environment.

---

## 🧪 Experimental Logic: The Checkbox Hack

Rather than relying on JavaScript for UI state changes, I am currently experimenting with **Boolean Logic** via hidden checkboxes to manage navigation and interactivity.

* **View Switching**: Using the `:checked` state of hidden `<input type="checkbox">` elements to toggle visibility between the Profile view and the Problem view.
* **Interaction Logic**: Applying `transform: rotateY(180deg)` to card containers when their internal checkboxes are toggled, allowing for a physical "flip" motion.

---

## 🛠️ Implementation Specs (Current State)

| Property | Use Case | Benefit |
| :--- | :--- | :--- |
| `perspective` | 3D Depth | Creates a realistic sense of distance and tilt for UI elements. |
| `:has()` | Contextual UI | Allows the container to react to the hover state of its children. |
| `backdrop-filter` | Glassmorphism | Enhances UI depth and readability against complex backgrounds. |
| `rotateY` | Card Rotation | Provides the mechanical basis for the 3D flip animation. |

---

## 📈 Future Improvements & Roadmap

- [ ] **Implementation of Content**: Populating the 3 profile cards with specific hobbies, technical skills, and assets.
- [ ] **Problem Set Logic**: Drafting and styling the 5 "Problem of the Day" cards.
- [ ] **Adaptive Stacking**: Finalizing media queries to ensure the Flexbox grid wraps perfectly for mobile devices.
- [ ] **Scale Transitions**: Engineering the "Dispose & Arrive" animations to smoothly swap view containers.
