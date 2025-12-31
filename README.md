<div align="center">

# 🧮 Shopping Cost Calculator — Dynamic Pricing Engine

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5-7952B3?style=for-the-badge&logo=bootstrap)](https://getbootstrap.com/)
[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)

**An interactive product customization interface demonstrating real-time DOM manipulation and state-based price calculation.**

*Fast • Interactive • Vanilla JS*

[Report Bug](https://github.com/sajidmahamud835/shopping-cost-calculator-js/issues) · [Request Feature](https://github.com/sajidmahamud835/shopping-cost-calculator-js/issues)

</div>

---

## 🔬 About The Project

**Shopping Cost Calculator** is a foundational study in frontend state management without the overhead of modern reactive frameworks (like React or Vue). It simulates a "MacBook Pro" configurator where user choices immediately reflect in the pricing model.

The primary research goal here is to demonstrate **Direct DOM Manipulation** efficiency and the logic required to maintain pricing integrity (base price + modifiers - discounts) using pure JavaScript event listeners.

### 🎯 Key Implementations
1.  **Event-Driven Architecture**: Utilization of click listeners to trigger state updates for Memory, Storage, and Delivery options.
2.  **Defensive Programming**: Ensuring promo codes are validated rigidly (e.g., matching "stevekaku") to prevent client-side exploitation.
3.  **Semantic Layout**: Structuring the application with accessibility in mind using semantic HTML5 tags and Bootstrap classes.

---

## ⚙️ Technical Architecture

The application follows a simple **Model-View-Controller (MVC)** pattern implemented in a single file structure:

-   **Model**: The internal variables tracking `memoryCost`, `storageCost`, `deliveryCost`.
-   **View**: The HTML table updating dynamically via `innerText`.
-   **Controller**: The `main.js` script handling logic and bridging the Model and View.

---

## ✨ Features

### 🟢 Implemented Capabilities

| Component | Feature Description |
|-----------|---------------------|
| **Product Customizer** | Toggle between 8GB/16GB Ram, 256GB/512GB/1TB Storage |
| **Real-time Totals** | Immediate recalculation of the "Total Price" upon any selection |
| **Promo Code System** | Application of a 20% discount code with validation |
| **Delivery Options** | Tiered pricing for standard vs. prime delivery |

### 🗓️ Research & Development Plan (Todo)

- [ ] **State Persistence**: Implement `localStorage` to save user selections on page reload.
- [ ] **Componentization**: Refactor the vanilla JS into Web Components for reusability.
- [ ] **Server-Side Validation**: (Hypothetical) Move pricing logic to a Node.js backend to prevent client-side tampering.
- [ ] **Unit Testing**: Add Jest tests for the calculation logic functions.

---

## 🚀 Getting Started

### Prerequisites

-   A modern web browser (Chrome, Firefox, Edge).

### Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/sajidmahamud835/shopping-cost-calculator-js.git
    cd shopping-cost-calculator-js
    ```

2.  **Run Application**
    -   Simply open `index.html` in your browser.
    -   **OR** use a live server extension in VS Code.

---

## 🤝 Related Projects

Explore other components of the research portfolio:

1.  **[EasyCom](../easycom)** - The evolution of this concept into a full-scale E-commerce application.
2.  **[InspectHealth](../inspecthealth)** - Another example of frontend-focused development using libraries (React).
3.  **[BankSync](../banksync)** - Shows how financial calculations (like in this calculator) are handled securely in a real app.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">

**[Sajid Mahamud](https://github.com/sajidmahamud835)**

*JavaScript Developer • Frontend Enthusiast*

</div>
