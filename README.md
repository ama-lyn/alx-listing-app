# ALX Listing App

## Project Overview

The **ALX Listing App** is a simplified property listing platform inspired by Airbnb. It showcases properties available for rent, allowing users to view key details, interact with call-to-action buttons, and explore listings in a visually appealing way. This project focuses on reusability, TypeScript best practices, and a component-driven approach using Next.js and TailwindCSS.

---

## Project Structure

Here's a breakdown of the core directories and their purposes:

### `/components`
Reusable components that are used throughout the application.

- `common/Card.tsx`: A card component for displaying individual property listings.
- `common/Button.tsx`: A customizable button component for user actions like “Book Now” or “View Details.”

### `/interfaces`
Houses all TypeScript interfaces used in the project.

- `index.ts`: Contains interfaces like `CardProps` and `ButtonProps` to ensure type safety across components.

### `/constants`
Central location for configuration data and static values.

- `index.ts`: Stores reusable constants such as API URLs, UI text, and configuration values.

### `/public/assets`
Contains all static media assets used in the app.

- Includes images, icons, and SVGs used across the UI.
- Organized for clarity and ease of reference.

---

## Tech Stack

- **Next.js** (v13+)
- **TypeScript**
- **TailwindCSS**
- **ESLint** (for linting)
- **Responsive Design** principles

---

## Project Goals

- Build a visually clean and responsive property listing interface.
- Practice component reusability using TypeScript interfaces.
- Maintain a clean and scalable folder structure for real-world projects.
- Explore TailwindCSS utility-first styling in a production-style setup.

---

## Getting Started

After cloning the repository and installing dependencies:

```bash
npm install
npm run dev

