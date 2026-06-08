# GEII Upcycling, E-Waste to Object

A small gallery of BUT2 GEII (IUT de Lille) student projects: working objects built from electronic waste. One page, no build step, no dependencies.

## How it works

- `index.html` is the whole gallery. Open it by double-clicking, or serve it with GitHub Pages.
- Hero photos live in `images/`.
- The project list lives inside `index.html`, in the `PROJECTS` array near the bottom.

## Add a project

1. Drop a hero photo of the object into `images/` (a photo of the object, not the makers).
2. Add an entry to `PROJECTS` in `index.html`:

   ```js
   {
     title: "The Project Name",
     credit: "Firstname & Firstname · BUT2 GEII A2I",
     image: "images/yourphoto.jpg",
     idea: "One or two sentences on the idea.",
     parts: ["Recovered PCB", "LEDs", "Wire"],
     visibility: "public"
   }
   ```

## The visibility switch

Every submission can live in the list. You choose what appears:

- `"public"` — shown in the gallery.
- `"unlisted"` — kept in the file but not shown (reserved for a future direct link).
- `"private"` — kept in the file but not shown.

Nothing is ever deleted to hide it. You only change the switch. This is how every submission can be received fairly while you still decide what is displayed.

## Privacy

- Credit by **first names or class only**. No surnames.
- Photographs show the **objects**, not the makers.
- Shown with the students' permission.

## Publishing

To put it online: push this repo to GitHub, then Settings → Pages → Deploy from branch → `main` / root. The link can then sit in the GEII site's ACTUALITÉS section.

---
*Built with Sarah. Seeded with three A2I projects: The Upcycled Carousel, The Pianist, The Stargazer.*
