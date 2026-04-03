# Mini Project 01: Simplistic CSS Loaders

This project focuses on creating simple loading animations using only CSS, avoiding the need for heavy GIFs or JavaScript.

## ✨ Key Features
- **Gradient Spinner**: Uses `-webkit-mask-composite` to create a smooth, hollow ring with a linear gradient.
- **Dotted Ring**: A complex loader generated from a single `div` using multiple layered `box-shadow` coordinates.
- **Glassmorphism**: A background header using `backdrop-filter: blur(10px)` for a modern frosted-glass effect.

## 🧪 Technical Challenges Solved
- **Masking**: Figured out how to use `destination-out` masking to "hollow out" a border-box.
- **Layering**: Used `grid-template-areas: "stack"` to perfectly align multiple animation elements on top of each other.

## 📸 What I learned
- **Glassmorphism**: Learned how to use `backdrop-filter` to blur in the background images for styling.
- **Box Shadows**: Realize how useful `box-shadow` is to create cool loading effects; currently looking forward to improve it.
- **Experimenting Web-Kit**: Curiosity hits me when I found out that I can use `-webkit-background-clip` to clip the text and make the color just like in the background.
- **Pseudo-Class & Keyframes**: Experimented on how I can manage to use animations to create beautiful effect; practicing also the use of pseudo-class to use in future projects.
