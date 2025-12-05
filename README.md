# Formulaire de la Gloire — Ultimate Contact Form

![Formulaire de la Gloire](screenshot.png)  

A retro, interactive, Undertale-inspired contact form packed with fun easter eggs, pixel-style visuals, and a Matrix-like interactive background. Designed for both fun and functionality, it demonstrates advanced frontend techniques, including keyboard navigation, audio feedback, visual effects, and client-side form validation.

---

## Table of Contents
1. [Tech Stack](#tech-stack)  
2. [Project Overview](#project-overview)  
3. [Features & Functionalities](#features--functionalities)  
4. [How to Use the Form](#how-to-use-the-form)  
5. [Keyboard Navigation](#keyboard-navigation)  
6. [Easter Eggs](#easter-eggs)  
7. [Setup & Running](#setup--running)  
8. [Contributing](#contributing)  
9. [Author](#author)  

---

## Tech Stack

- **HTML5** — semantic structure for the form and dialogs  
- **CSS3 / Custom Variables** — retro pixel UI, Matrix-style interactive background, animations, confetti  
- **JavaScript (ES6)** — form validation, easter eggs, typing animation, audio feedback, DOM manipulation  
- **Web Audio API** — sound effects (beeps, musical notes)  
- **Canvas API** — interactive pixel/matrix background and confetti effects  
- **Optional backend** — simulated form submission with downloadable JSON fallback  

---

## Project Overview

This project is a contact form with a **retro gaming vibe** inspired by Undertale. It has been enhanced with:  

- Audio feedback when typing or interacting with the UI  
- Visual feedback using confetti, golden alerts, and an interactive matrix background  
- Multiple hidden easter eggs activated by typing keywords, Konami code, or interacting with specific elements  
- Keyboard-friendly navigation for accessibility and retro feel  

The project can be run **fully client-side**, with a fallback JSON download if no backend exists.  

---

## Features & Functionalities

### Form Features
- Required fields: `Nom`, `Email`, `Sujet`, `Message`  
- Real-time client-side validation  
- Visual feedback for invalid fields (red outline)  
- Submit button triggers typing animation, sound effects, and confetti on success  
- Demo fill button for instant testing  

### Dialog / Alert Features
- Pop-up dialogs with typewriter animation  
- Golden glory mode for special messages  
- Alerts with moving “OK” button for interactive fun  
- ESC key closes alerts  

### Audio Feedback
- Beeps on typing or new lines  
- Short musical note sequences on form submission and easter eggs  

### Matrix-Style Background
- Interactive pixel/matrix rain effect on canvas  
- Background reacts to easter eggs or special triggers  

---

## How to Use the Form

1. Fill in the required fields: `Nom`, `Email`, `Sujet`, `Message`  
2. Use **keyboard arrows** to navigate fields (Up/Down or Tab)  
3. Press **Enter** on the submit button to send the form  
4. On submit:  
   - Form is validated  
   - Typing animation displays confirmation  
   - Musical notes play  
   - Confetti bursts if special keywords are detected  

---

## Keyboard Navigation

- **ArrowDown / Tab** → move to the next field  
- **ArrowUp** → move to the previous field  
- **Enter** → activates the focused button (submit, demo, or reset)  

This mimics the **Undertale-style retro interface**.  

---

## Easter Eggs

Multiple hidden interactions enhance the retro experience:

### Text-based Easter Eggs
- Typing **INFO**, **NUIT**, or **GLORY** triggers special effects:  
  - Pop-up golden alert (`GLORY`)  
  - Matrix / confetti effects (`INFO` / `NUIT`)  
- Keywords in `Sujet` or `Message` like `gagner` can trigger “You won” messages  

### Konami Code
- `↑ ↑ ↓ ↓ ← → ← → B A` triggers a hidden dialog with confetti and sound  

### Field Interactions
- Focusing / hovering repeatedly over inputs can trigger random effects:  
  - Field wiggle  
  - Beeps or musical notes  
  - Visual pixel sparkle effects  

### Draggable Logo Easter Egg
- Dragging the logo reveals a hidden message  
- Logo reacts to movement, giving visual feedback  

### Matrix Background Easter Eggs
- Clicking or moving the mouse over the background can trigger:  
  - Pixel explosions  
  - Color glitches  
  - Interactive sound feedback  

---

## Setup & Running

1. Clone the repository:  
```bash
git clone https://github.com/MohamedAmineZalila/Formulaire-de-la-Gloire.git
cd Formulaire-de-la-Gloire
