# Social Innovation Evaluation

An interactive bibliography explorer for researchers working with **creative evaluation** and **participatory evaluation**. Browse  case studies, explore evaluation stages, and discover connections through shared methods, design practices, and evidence.

This bibliography was developed primarily within PhD research examining the measurement and assessment of social innovation from a design perspective.

**Bibliography compiled by Beatriz Bonilla Berrocal.**

## Explore the collection

- **Connections:** explore a network of cases, filter the characteristics that connect them, and hover for descriptions and bibliographic sources.
- **Case studies:** browse the collection as searchable cards.
- **Case details:** read an overview, explore evaluation stages, see a consolidated tools list, compare related cases, and consult the original citations.

Search suggests matching case titles, methods and tools, and other characteristics as you type. Choose a suggestion with a click or the arrow keys and Enter. The selected case or value stays visible as a labeled filter until you clear it. **Explore values** lists every recorded value by dimension, including values found in only one case. These filters are independent of the dimensions selected under **Connect by**.

Select a node to bring its directly connected cases closer and move unrelated cases to the edge. Drag nodes to rearrange them, drag the background to pan, and use the zoom controls to explore. **Show all cases** restores your previous arrangement.

The interface adapts to desktop and mobile screens. Keyboard users can focus nodes, open them with Enter or Space, move them with arrow keys, and dismiss previews or details with Escape.

## Understanding connections

Connections reflect shared terms under the selected filters. Design practices, methods and tools, and collected evidence are the default starting points; additional characteristics can broaden the view.

Case descriptions and citations retain their original wording. A connection is an aid to exploration, not a quality rating. Map distance is not a similarity score, and different wording can leave otherwise related studies unconnected.


## Repository structure

```text
.
├── index.html       # Page structure
├── styles.css       # Visual design and responsive layouts
├── app.js           # Search, filters, graph, and case interactions
├── data.js          # Collection loaded by the browser
├── data/            # Downloadable JSON and CSV collection exports
├── .nojekyll        # Serve the static site directly on GitHub Pages
├── .gitignore
└── README.md
```

Built with HTML, CSS, JavaScript, and SVG. The collection is bundled with the site, which also works offline.
