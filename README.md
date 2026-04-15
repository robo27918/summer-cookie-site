# Cookie World

Cookie World is a single-page static website built with plain HTML, CSS, and a small amount of JavaScript. It presents a cozy baking-themed layout with cookie highlights, low-carb cookie recipes, regular and low-carb bread recipes, and a decorative visitor message board.

## Preview

The page includes:

- A hero section introducing the site
- A cookie showcase with popular cookie types
- A low-carb cookie recipe section
- A bread recipe section with tab switching between regular and low-carb options
- A styled message board with pinned-note cards

## Built With

- HTML5
- CSS3
- Vanilla JavaScript

## Project Structure

```text
cookies/
|-- index.html
`-- README.md
```

## How To Run

This project does not require a build step or dependencies.

1. Open `index.html` directly in a web browser, or
2. Serve the folder with any simple local server

Example with Python:

```bash
python -m http.server
```

Then open `http://localhost:8000`.

## Notes

- Everything is contained in a single `index.html` file.
- Styles are written inline inside the page.
- The bread recipe tabs are powered by a small JavaScript function at the bottom of the file.

## Future Improvements

- Split HTML, CSS, and JavaScript into separate files
- Add real images or illustrations for recipes
- Improve accessibility and keyboard interaction
- Fix character encoding issues so emojis and symbols render correctly everywhere

## License

No license file is currently included in this project.
