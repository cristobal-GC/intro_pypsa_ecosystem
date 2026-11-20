# Introduction to the PyPSA ecosystem

Jupyter notebooks introducing the different elements of the [PyPSA](https://pypsa.org) ecosystem: `pypsa`, `atlite`, `linopy`, etc. Each element has its own folder.


## Visual Guide to Technology Representation in PyPSA-Eur

The folder [`visual_guide/`](visual_guide) contains the *Visual Guide to Technology Representation in PyPSA-Eur* ([PDF](visual_guide/PyPSA-Eur_Visual_Guide.pdf)), a slide deck that shows, one technology per slide, how PyPSA-Eur represents each technology with PyPSA components (buses, generators, links, stores, loads) and their efficiencies.

The guide is published on Zenodo: <https://zenodo.org/records/19437724> (CC BY 4.0).

Versions:

- **v0.0** (2026-04, 105 slides): published on [Zenodo](https://zenodo.org/records/19437724).
- **v0.1** (2026-11, 112 slides): work in progress, available in this GitHub repository ([PDF](visual_guide/PyPSA-Eur_Visual_Guide.pdf)).


## Environment

The environment is defined in [`pixi.toml`](pixi.toml) using [pixi](https://pixi.sh):

```bash
pixi install     # create the environment
pixi run lab     # launch JupyterLab
```

## References

- PyPSA user guide: <https://docs.pypsa.org/latest/user-guide/user-guide/>
