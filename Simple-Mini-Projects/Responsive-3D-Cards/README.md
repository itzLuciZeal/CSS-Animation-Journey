# **Mini-Project 2**: Responsive 3D Cards

_This project is explores the use of **flex box** to organize the information into a **3D animated profile cards** that highlights the person's company name, logo, and the adaptive experience of each._

## 🔗 [**Live Demo**](https://itzlucizeal.github.io/CSS-Animation-Journey/Simple-Mini-Projects/Responsive-3D-Cards/)

## **Key Features**

* **Dynamic 3D Tilt Engine**: Profile cards utilize `perspective(100vh)` combined with `rotateX` and `rotateY` transforms to create a tactile, physical depth effect on hover.
* **Modern Glassmorphic UI**: High-fidelity *frozen* aesthetic achieved through `backdrop-filter: blur(1.2vh)` and alpha-channel linear gradients.
* **Advanced Parent-Child Logic**: Implements the `:has()` pseudo-class to dynamically increase background blur when specific cards or menu items are focused.
* **Atmospheric Layering**: A synchronized snow-effect overlay and `background-attachment: fixed` mountain backdrop create a deep, immersive user environment.

---

## **Technical Challenges & Solutions**

1. ### *Flickering `div` Button With Checkbox*
    **Challenge**: Decided to experiment with making a `div` button that has a `position: absolute` in that way it is on the top of the card and not ruining the structure. Consequently, added `checkbox` inside the `div` button to activate the **3D animated cards** to show the profile information.

    **Solution**: I proceed to just simply used pseudo-class named `:hover()` effect to immediately show the **3D animated cards** flawlessly.
   
---

## **Implementation Specs**

| Property | Use Case | Benefit |
| :--- | :--- | :--- |
| `perspective` | 3D Depth | Creates a realistic sense of distance and tilt for UI elements. |
| `:has()` | Contextual UI | Allows the container to react to the hover state of its children. |
| `:hover()` | Hover Effects | Enhances user interface with smooth hover animations. |
| `rotateX/Y` | Card Rotation | Provides the mechanical basis for the 3D flip animation. |

---

## ⚠️ **Project Disclaimer**

*The individuals, organizations, and narratives featured in **Responsive 3D Cards** (e.g., Marcus Thorne, Velostream Systems, and Yggdrasil Crystalline) are entirely fictional. All profile images and company logos are AI-generated samples. The description and job descriptions were crafted using AI to provide realistic context for the UI/UX design. This project is a demonstration of CSS architecture and 3D transform logic; it does not represent real-world entities.*
