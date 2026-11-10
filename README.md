# Life Chapters

Een complete, responsive, Nederlandstalige one-page website voor Life Chapters. De site gebruikt geen afbeeldingen: alle visuele elementen zijn opgebouwd met HTML, CSS-gradients, vormen, borders, shadows en animaties.

## Bestanden

- `index.html` — homepage met Home, Services, About, Contact en het volledige artikel.
- `style.css` — responsive design system, CSS-vormen, animaties en states.
- `script.js` — mobiele navigatie, smooth scrolling, actieve sectie en demo-contactformulier.
- `server.js` + `package.json` — optionele zero-dependency server voor lokaal gebruik en Preview.
- `manus-routes.json` — route-manifest voor de websiteomgeving.

## Lokaal starten

Met Node.js:

```bash
npm start
```

Open daarna `http://localhost:3000`.

Zonder Node.js kan de map ook rechtstreeks worden geopend via `index.html`, of worden geserveerd met:

```bash
python3 -m http.server 3000
```

## Zippen

Zip de volledige map `lifechapters`. Er zijn geen externe afbeeldingen, frameworks of installatie-stappen nodig.
