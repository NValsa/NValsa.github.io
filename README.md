
# Hollywood Movies and Historical Events Analysis

This repository contains a **website analyzing Hollywood movies** and their connections with historical events. The website presents visualizations, plots, and insights about how films reflect or relate to social, economic, and political trends over time.

## Course Context

This project was developed for the EPFL course **CS-401 Applied Data Analysis**.  
Course page (if still hosted): https://epfl-ada.github.io/teaching/fall2024/cs401/

## Link

You can explore the website here:  
[https://nvalsa.github.io](https://nvalsa.github.io)

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

## Detailed Analysis

This repository focuses on the **website and its visualizations**. For an in-depth description of the **data processing, analysis methods, and research questions**, please see the main project README:  
[History in Hollywood – Full Analysis](https://github.com/epfl-ada/ada-2024-project-spaghettisolution))

## Installation / Local Development

To view the website locally, you need Ruby and Bundler installed. Then run:

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
````

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
