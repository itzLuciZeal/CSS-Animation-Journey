# 🧊 Project 02: Responsive 3D Glassmorphism & Logic Cards

## 🚧 Status: Active Development (WIP)
**Current Phase**: Implementing the "Checkbox Hack" for state management and 3D card-flip mechanics.

## 🎯 The Vision
This project is a deep dive into **Adaptive Engineering**. I am building a dual-purpose UI that transitions between a "Team Directory" and an "Educational Flashcard" system—engineered entirely with HTML5 and CSS3. 

## 🛠️ Technical Highlights
* **3D Transform Engine**: Utilizing `perspective(350vh)` combined with `rotateX` and `rotateY` to create a tactile, physical depth effect on hover.
* **Modern Glassmorphism**: High-fidelity UI using `backdrop-filter: blur()` and layered linear gradients to create a "frozen" aesthetic.
* **Advanced Selectors**: Implementing the `:has()` pseudo-class to create environment-aware styling, such as increasing background blur when a card is active.
* **Flexbox Architecture**: A responsive layout designed to "adapt" rather than "break" across different screen dimensions.

## 🧪 Experimental Logic: The Checkbox Hack
Rather than relying on JavaScript for UI state changes, I am experimenting with **Boolean Logic** via hidden checkboxes to manage navigation and interactivity.
* **The Goal**: Use the `:checked` state to trigger a `scale()` and `opacity` transition between views.
* **The Transition**: Disposing of the 3 Team Profiles to make room for 5 interactive Math Problem cards.
* **The Interaction**: Applying `transform: rotateY(180deg)` to reveal card "answers" upon a user click.

## 📈 Roadmap
- [x] **Phase 1**: Environment setup and 3D hover states.
- [ ] **Phase 2**: Complete the 5 "Problem of the Day" cards with 3D flip logic.
- [ ] **Phase 3**: Refine the responsive "Dispose & Arrive" scale transitions.
- [ ] **Phase 4**: Final asset population (real hobbies, skills, and math problems).

---

> 💡 **Philosophy**: "Memorizing isn't necessary at all in programming; rather, it's about applying the knowledge you've learned to adapt."

---

### 🔗 Live Demo
[View the Ongoing Project Here](https://itzlucizeal.github.io/CSS-Animation-Journey/Simple-Mini-Projects/02-Responsive-3D-Cards/)
