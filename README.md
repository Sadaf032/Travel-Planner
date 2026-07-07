# 🌍 AI-Powered Tour & Travel Web Application

## 📌 Project Overview

This project is a modern, responsive Tour & Travel web application built with **React.js** by following a structured AI-assisted development workflow.

The application helps users discover travel destinations, explore tour packages, view travel information, and plan their trips through an intuitive user interface.

---
# Prompt Used

```text
You are a senior full-stack developer experienced with React.js and modern web APIs. Build a responsive AI-powered travel planner web application for leisure travelers (solo, couples, families) that includes the following core features:

1. Itinerary Generation – users input destination, travel dates, and budget; the app returns a day-by-day itinerary with activities, suggested hotels, and estimated costs.
2. Destination Suggestions – based on user interests (culture, adventure, relaxation), the app proposes 3–5 destination options with brief descriptions and images.
3. Date & Budget Inputs – intuitive form components that validate dates, enforce a positive budget, and provide real-time feedback.
4. Interactive Map – integrate the Google Maps JavaScript API (or Leaflet) to display selected destinations and travel routes.
5. Responsive UI – use React.js, React Router, functional components, and Tailwind CSS (or plain CSS) to create a mobile-first design with a navigation bar, hero section, search form, results view, and a footer.
6. API Integration – fetch weather data (OpenWeatherMap) and country info (REST Countries) to enrich the itinerary.

Technical Constraints:
- Project scaffolded with Vite (or Create-React-App).
- Use ES6+, JSX, and modern React Hooks.
- All API keys must be stored in an .env file; do not hard-code them.
- Code must be linted with ESLint and formatted with Prettier.
- Provide unit tests for the itinerary generation logic using Jest.

Output Requirements:
- Return a zipped folder named `travel-planner-app` containing:
  - `src/` with all React components, hooks, and service files.
  - `public/` with index.html and assets.
  - `package.json` with all dependencies listed.
  - `.env.example` showing required environment variables.
  - `README.md` that explains how to set up, run, and test the app.
- Include a short summary (max 200 words) describing the architecture and any design decisions.

If any part of the specification is unclear, ask a clarifying question before generating code.
```
