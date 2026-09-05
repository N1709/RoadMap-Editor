# RoadMap Editor

A lightweight, offline-first visual roadmap builder that runs entirely in a single HTML file — no build step, no backend, no external dependencies. Drag nodes onto a canvas, connect them, style them by type, and export or save your roadmap whenever you like.

## Features

- Drag-and-drop canvas — place and reposition nodes freely on a large scrollable board
- Multiple node types — Title, Info Panel, Topic, Checkpoint, and Note, each with distinct styling
- Node connections — link nodes together with directional arrows to show flow/progression
- Inline editing — click a node to select it, then edit its text and type from the side panel
- Save / Load — export your roadmap as JSON and load it back later to keep editing
- Export to SVG — generate a shareable, scalable image of your roadmap
- Dark mode — toggle between light and dark themes
- Bilingual UI — switch instantly between Bahasa Indonesia and English
- Zero dependencies — pure HTML, CSS, and JavaScript in a single file; works fully offline

## Getting Started

No installation required.

1. Download `index.html` from this repository
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari)
3. Start building your roadmap

## How to Use

| Action | How |
|---|---|
| Add a node | Click **+ Topic**, **+ Checkpoint**, **+ Note**, or use a quick template in the sidebar |
| Select a node | Click on it |
| Move a node | Drag it around the canvas |
| Edit text/type | Select a node, then use the panel on the left |
| Connect nodes | Click **Connect**, then click a source node followed by a target node |
| Delete a node | Select it and click the delete icon, or use **Delete Node** in the panel |
| Save your work | Click **Save** to download a `.json` file |
| Resume later | Click **Load** and choose a previously saved `.json` file |
| Export image | Click **Export SVG** |
| Switch theme | Click **Dark Mode** / **Light Mode** |
| Switch language | Use the language dropdown in the top bar |

## Node Types

| Type | Purpose |
|---|---|
| Topic | Main subject or learning material |
| Checkpoint | Milestone or completion marker |
| Note | Supplementary information |
| Title | Main heading card |
| Info Panel | Roadmap description/overview |

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks, no libraries)
- SVG (for connections and export)

## License

This project currently has no license specified. Feel free to add one (e.g. MIT) if you plan to share or accept contributions.

## Contributing

Issues and pull requests are welcome. Since this is a single-file project, most changes will be made directly to `index.html`.
