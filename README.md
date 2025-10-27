# Virtual Herbal Garden — Frontend (Minimal Scaffold)

This repository contains a minimal Next.js frontend scaffold for the Virtual Herbal Garden project. It includes a plant catalog, plant detail pages with Sketchfab embed placeholders, and basic layout components.

What is included
- Next.js app (pages: /, /plants, /plants/[id])
- Components: Header, Footer, PlantCard, SketchfabEmbed (with DOMPurify)
- Sample data: `src/data/plants.js` (3 example plants)
- Basic global styles and a README

Run locally
1. Install dependencies

```powershell
npm install
```

2. Run dev server

```powershell
npm run dev
```

Open http://localhost:3000 in your browser.

How to add your Sketchfab embed
- Edit `src/data/plants.js` and replace the `sketchfabEmbed` placeholder comment with the full iframe/embed HTML from Sketchfab for that plant.
- The `SketchfabEmbed` component sanitizes the HTML using DOMPurify before rendering.

Next steps (I can do for you)
- Implement authentication, favorites, and API integration (Node.js + MongoDB)
- Add Recommendation Wizard and chatbot UI
- Improve SEO (Next.js server-side rendering) and accessibility
