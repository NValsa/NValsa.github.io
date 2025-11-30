---

# Hollywood Movies and Historical Events Analysis

This repository contains a **website analyzing Hollywood movies** and their connections with historical events. The website presents visualizations, plots, and insights about how films reflect or relate to social, economic, and political trends over time.

## Link

You can explore the website here:
[https://nvalse.github.io](https://nvalse.github.io)

## Data Source

The movie dataset used for the analysis comes from Carnegie Mellon University:
[https://www.cs.cmu.edu/~ark/personas/](https://www.cs.cmu.edu/~ark/personas/)

## Features

* Interactive plots showing trends in Hollywood films over time.
* Analysis of specific historical themes and events (e.g., wars, social movements, economic events).
* Tag and search functionality to explore movies by theme or year.

## Technology

* Built using **Jekyll**, a static site generator.
* Uses HTML, CSS, and JavaScript for front-end visualizations.
* Plot data is precomputed and included as HTML/JSON files.

## Installation / Local Development

To view the website locally, you need Ruby and Bundler installed. Then, run:

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Repository Structure (Simplified)

```
assets/      # CSS, JS, images, and plot files
_includes/   # Jekyll templates and reusable HTML snippets
_layouts/    # Jekyll page layouts
_config.yml  # Jekyll configuration
index.html   # Homepage
```

Optional files like `_data` and staticman configurations can be removed if comments or search are not needed.

## License

This repository uses the [MIT License](LICENSE).

---
