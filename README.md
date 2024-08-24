# My Obsidian Jekyll

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Table of Contents
- [Obsidian Jekyll](#obsidian-jekyll)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Github Pages](#github-pages)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## About the Project

Obsidian Jekyll is a static site generator based on Jekyll that supports Roam-style note linking and features a graph visualization of your notes and their connections. It is designed to provide a simple, responsive, and interactive experience for managing and visualizing your notes.

### Built With

- [Jekyll](https://jekyllrb.com/) - Static Site Generator
- [Markdown](https://daringfireball.net/projects/markdown/) - Lightweight Markup Language

## Features

- **Roam-style Linking**: Supports double bracket link syntax to other notes.
- **Automatic Backlinks**: Automatically generates backlinks to other notes.
- **Link Previews**: Displays link previews on hover.
- **Graph Visualization**: Visualizes notes and their connections in a graph.
- **Responsive Design**: Simple and responsive design suitable for various devices.
- **Markdown/HTML Support**: Write notes in Markdown or HTML.

## Getting Started

Follow these instructions to set up the Obsidian Jekyll project on your local machine.

### Prerequisites

Before installing the project, ensure you have the following installed:

- **Ruby and Jekyll**: Install Ruby and Jekyll on your system. Instructions are available on [Jekyll's official site](https://jekyllrb.com/docs/installation/).

### Installation

1. Clone the repo
2. Install the dependencies
3. Serve the site locally

## Usage

Once set up, you can start adding your notes in the `_notes` directory. Use double brackets `[[note-title]]` to create links between your notes. The graph visualization and other features will automatically be generated when you build the site.

## Github Pages

> **Update (January 2023):** It seems that GitHub Pages supports custom plugins now, thanks to GitHub Actions ([view relevant discussion](https://github.com/maximevaillancourt/digital-garden-jekyll-template/discussions/144)).

GitHub Pages only partially supports this template. To power the interactive notes graph, this template uses a custom Jekyll plugin to generate the graph data in `notes_graph.json`, and GitHub Pages doesn’t support custom Jekyll plugins.

If you want to use the graph with GitHub Pages, you can build your garden locally using Jekyll and then push the result to GitHub Pages.

Alternatively, you can deploy your garden to Netlify, and it’ll work out of the box. [Here’s a guide on how to set this up](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).

If you don’t need the graph, you can remove it from the layout [as explained here](https://github.com/maximevaillancourt/digital-garden-jekyll-template/discussions/132#discussioncomment-3625772).

## Roadmap

- Add SEO plugins
- Add collections
- Add search bar
- Change theme

See the [open issues](https://github.com/yourusername/obsidian-jekyll/issues) for a full list of proposed features (and known issues).

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License

Distributed under the MIT License. See `LICENSE.md` for more information.
