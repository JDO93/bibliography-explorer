# Project Beta

An interactive bibliography explorer for researchers working with **creative evaluation** and **participatory evaluation**. Browse 32 case studies, explore 124 evaluation stages, and discover connections through shared methods, design practices, and evidence.

## Explore the collection

- **Connections:** explore a network of cases, filter the characteristics that connect them, and hover for descriptions and bibliographic sources.
- **Case studies:** browse the collection as searchable cards.
- **Case details:** read an overview, explore evaluation stages, see a consolidated tools list, compare related cases, and consult the original citations.

Select a node to bring its directly connected cases closer and move unrelated cases to the edge. Drag nodes to rearrange them, drag the background to pan, and use the zoom controls to explore. **Show all cases** restores your previous arrangement.

The interface adapts to desktop and mobile screens. Keyboard users can focus nodes, open them with Enter or Space, move them with arrow keys, and dismiss previews or details with Escape.

## Understanding connections

Connections reflect shared terms under the selected filters. Design practices, methods and tools, and collected evidence are the default starting points; additional characteristics can broaden the view.

Case descriptions and citations retain their original wording. A connection is an aid to exploration, not a quality rating. Map distance is not a similarity score, and different wording can leave otherwise related studies unconnected.

## Run locally

Open `index.html` in a browser. No installation, account, build step, or backend is required.

Alternatively, with Python installed, run this command from the repository folder and open <http://localhost:8000>:

```sh
python -m http.server 8000
```

Node arrangements are temporary and remain in the current page session. Refreshing the page resets them.

## Publish with GitHub Pages

1. Commit and push the repository to GitHub.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select **main** and **/ (root)**, then save.

Once the deployment finishes, the site will be available at:

**https://jdo93.github.io/bibliography-explorer/**

Subsequent pushes to `main` update the published site. See the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) for setup details.

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

Built with HTML, CSS, JavaScript, and SVG. The collection is bundled with the site, which also works offline. **Export collection** downloads the structured bibliography as JSON.
