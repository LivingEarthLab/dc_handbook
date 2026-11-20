# UNIGE & UNEP/GRID-Geneva Data Cubes Capacity Building

[![Open Data Cube](img/logo_OpenDataCube.png)](https://yg1975.github.io/Nostradamus_CB/)

This repository contains the source of the **Data Cubes Capacity Building** handbook, a resource on Data Cubes and Earth Observation developed by the University of Geneva ([Living Earth Lab](https://www.unige.ch/envirospace/livingearth)) and [UNEP/GRID-Geneva](https://unepgrid.ch). It is part of the [Living Earth](https://livingearthhub.org) ecosystem.

📖 **Read the handbook online: [yg1975.github.io/Nostradamus_CB](https://yg1975.github.io/Nostradamus_CB/)**
⬇️ [Download the full site (PDF)](https://yg1975.github.io/Nostradamus_CB/full_site.pdf)

## About

The handbook introduces the core concepts behind Data Cubes: which problems they help to solve, how they organise satellite and geospatial data, and the main steps involved in setting them up. It also walks through concrete, hands-on implementations.

At its core is the **Nostradamus datacube**, a modified [Open Data Cube](https://www.opendatacube.org/) deployment with a multi-user JupyterHub, an integrated STAC datastore, and ready-to-use notebooks. The handbook documents how to install and use it, complemented by step-by-step tutorials, recorded workshops, and a parallel section on vector datacubes for non-raster geospatial data.

## Contents

| Section | Description |
|---------|-------------|
| **Introduction to datacubes** | What is a Data Cube, the Open Data Cube (overview and installation), and other datacube platforms |
| **Nostradamus datacube** | Overview, datacube use, and data sources used (CLMS CLC+ Backbone, AlphaEarth Foundations) |
| **LandShift** | Overview of the LandShift datacube |
| **Nemesis** | Overview of the Nemesis datacube |
| **Tutorials** | How to install an Open Data Cube, use it, index new data, and retrieve data with the Python API |
| **Workshops** | Workshop material, including Nostradamus T6.3 |
| **Vector datacubes** | Overview and installation |
| **Data sources** | Landsat, Sentinel, Planetary Computer, NASADEM, Copernicus DEM, ESA WorldCover, Impact Observatory Land Cover, Copernicus Land Monitoring Service, CLMS CLC+ Backbone, AlphaEarth Foundations |
| **Tools** | Jupyter, LivingEarth, Cube in a box |
| **Other pages** | Publications, Acknowledgments, Glossary, FAQ, Contact |

## Building the handbook locally

The site is built with [Quarto](https://quarto.org/). You need Quarto installed ([installation guide](https://quarto.org/docs/get-started/)).

```bash
git clone https://github.com/yg1975/Nostradamus_CB.git
cd Nostradamus_CB

# Live preview in your browser
quarto preview

# Or render the full site
quarto render
```

> 🔧 *If the project needs extra dependencies to execute code (Python environment, etc.), document them here.*

## Contributor guidelines

Contributions are welcome and greatly appreciated! To contribute, please follow these guidelines:

**Reporting issues**
* Check that the issue has not already been reported on the [issue tracker](https://github.com/yg1975/Nostradamus_CB/issues).
* Submit a new issue on the [issue tracker](https://github.com/yg1975/Nostradamus_CB/issues).

**Development process**
* Fork the repository, make changes in your fork, and submit a pull request.
* Follow the existing writing style and structure.
* Make sure the site renders without errors (`quarto render`) before submitting.
* Describe your changes in the pull request.

**Where to get help**
* See the [FAQ](https://yg1975.github.io/Nostradamus_CB/faq.html) and the [Contact](https://yg1975.github.io/Nostradamus_CB/contact.html) page.
* Maintainer: [Gregory Giuliani](https://www.unige.ch/envirospace/people/giuliani)

## Citation

If you use this resource in your work, please cite it:

```bibtex
@book{datacubes_capacity_building,
  author    = {{UNIGE and UNEP/GRID-Geneva}},
  title     = {Data Cubes Capacity Building},
  year      = {2026},
  publisher = {University of Geneva and UNEP/GRID-Geneva},
  url       = {https://yg1975.github.io/Nostradamus_CB/}
}
```

> 🔧 *Replace with the authors and DOI (e.g. Zenodo) you want people to use.*

## License

> 🔧 *State the license(s): one for the text/content (e.g. CC BY-NC-SA 4.0, as for the Living Earth Handbook) and one for the code (e.g. EUPL-1.2), and add a `LICENSE` file.*

## Acknowledgements

See the [acknowledgments](https://yg1975.github.io/Nostradamus_CB/acknowledgments.html) page of the handbook.

> 🔧 *Add the Horizon Europe funding statement and grant number for Nostradamus here.*
