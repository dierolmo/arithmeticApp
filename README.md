# arithmeticApp

hi, this is just a clean, custom web calculator built my own way to explore vanilla javascript logic and minimal styling with tailwind CSS. 

the project features a monolithic dark glassmorphic layout with responsive feedback, keyboard mapping, and a technical architecture tailored for a structured development portfolio.

## tech stack
- html5 (clean semantic structure)
- tailwind css (custom background gradients & utility classes)
- vanilla javascript (modular camelCase architecture)
- fonts: jetbrains mono via google fonts

## architecture & features
- **state engine**: manages precise tracking of operands (`currentOperand`, `leftOperand`), pending operators, and state transitions during multi-step evaluations.
- **precision arithmetic motor**: handles basic operations, float evaluation, chaining commands without explicit breaks (e.g., `3 + 5 × 2`), percentage parsing relative to preceding variables, and division-by-zero blocks.
- **interactive ui/ux**:
  - continuous font-scaling script to adjust display layout based on string length to prevent layout breaks.
  - fluid button interactions via micro-animations (`transition-all duration-180`) and organic scaling tactile responses (`active:scale-94`).
  - integrated visual error handling with native css `@keyframes` animation resets to trigger layout shakes on input errors.
- **developer console interface**: custom background styled using multiple overlayed radial-gradients, frosted glass blur elements, and an active blinking text cursor tracking current input logs.
- **native keyboard listener**: full keyboard mapping bindings (`0-9`, `.`, `+`, `-`, `*`, `/`, `%`, `Enter`, `Backspace`, `Escape`) to allow quick navigation directly from the typing deck.

## project structure
 arithmeticApp
 ├── index.html      # combined semantic layout, inline glassmorphism css, and js engine
 └──README.md       # project log & structural overview

---
devLog // dieromlo