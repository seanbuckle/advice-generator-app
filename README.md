# Advice Generator | Type-Safe API Interface 🎲
A high-performance web application that interfaces with the Advice Slip JSON API. This project demonstrates an advanced handle on Asynchronous TypeScript, data-driven UI updates, and a responsive design system managed through Modular SCSS.

## 📸 Preview

![Professional UI of the Advice Generator app featuring a dark-themed card with neon green accents and a central quote.](./images/screenshot.png)

## 🚀 Technical Highlights

- **Type-Safe API Integration:** Leverages TypeScript Interfaces to strictly define the API response structure, preventing runtime errors during data fetching.
- **Asynchronous Orchestration:** Implemented a robust Fetch API handler using `async/await` to manage real-time data retrieval.
- **Dynamic DOM Management:** TypeScript ensures that DOM element selection and manipulation are handled with strict null-checking and type-casting.
- **Styling Architecture:** Modular SCSS following the BEM (Block Element Modifier) methodology for encapsulated, maintainable styles.
- **Modern CSS:** Utilises CSS Custom Properties for theme tokens and high-contrast interactive states.

## 🏗️ Architectural Overview

### 1. TypeScript & Asynchronous Logic

The application logic is built for stability and predictability:
- **Interface Definition:** Defined a clear `AdviceResponse` interface to map the incoming JSON data (ID and Advice string) to the UI.
- **Error Handling:** Implemented `try/catch` blocks within asynchronous functions to gracefully handle network failures or API downtime.
- **Event Handling:** TypeScript manages the dice button interaction, ensuring the generator is throttled appropriately to align with API rate limits.

### 2. Design System (SCSS + BEM)

The visual layer is engineered for high-end aesthetic fidelity:
- **Neon Aesthetic:** Custom-engineered box-shadows and transitions for the dice trigger, utilising the high-contrast "Neon Green" palette.
- **Asset Art Direction:** Uses dynamic asset swapping for the "pattern divider" to ensure the visual rhythm remains consistent across mobile and desktop breakpoints.
- **Typography:** Precise implementation of the 'Manrope' typeface (Weights 800) for maximum legibility in a quote-centric layout.

### 3. Accessibility & UX

- **Focus & Hover States:** Interactive elements are optimised with clear visual cues for keyboard and touch users.
- **Semantic Markup:** Uses the `<q>` tag for the advice text and `<main>` for the card container to provide the best possible experience for assistive technologies.
- **Performance:** Optimised for a near-instant Largest Contentful Paint (LCP) through lightweight assets and minimal execution overhead.

## 🛠️ Built With

## 🔗 Live Implementation

- **Live Site:** https://advice-generator-app.seanbuckle.com

- **Source Code:** https://github.com/seanbuckle/advice-generator-app

## 👨‍💻 Author

**Sean Buckle**

[Frontend Mentor Profile](https://www.frontendmentor.io/profile/seanbuckle)

[LinkedIn](https://www.linkedin.com/in/seanbuckle)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/seanbuckle/advice-generator-app/blob/main/LICENSE) file for details.

---

***Note: This project was built as a solution to a Frontend Mentor challenge.***
