# altair_demo
This is a collection of demo notebooks for plotting in Python with Altair/Vega-Lite.

## Installation

To get started with Altair, follow the [instructions in the Altair documentation](https://altair-viz.github.io/getting_started/installation.html).

If you are using [Conda](https://conda.io/en/latest/) for managing your Python packages and environments, the following one-liner will set up a new environment `altair` for you and install the required packages:
```bash
conda create -n altair -c conda-forge python=3.7 altair vega_datasets jupyterlab
```
This uses JupyterLab. After installation you can launch a new session with
```bash
jupyter lab
```

If you want to programatically save `svg` or `png` versions of your graphs, you'll need to also install
the `selenium` Python package and the `chromedriver` executable - see [the Altair docs](https://altair-viz.github.io/user_guide/saving_charts.html) or ask [your favourite search engine](https://duckduckgo.com/?q=install+chromedriver) for help.


## Notebooks

* `quickstart_example.ipynb`: Example from the quickstart section of the Altair docs
* `display_examples.ipynb`: Different ways of showing or saving charts
* `talk_plost.ipynb`: Example plots used in talk slides


## References

### Packages
* Altair docs: https://altair-viz.github.io/index.html
* Vega-Lite docs: https://vega.github.io/vega-lite/
* Vega-Embed docs: https://github.com/vega/vega-embed

### Grammar-of-Graphics background
* Original Wickham paper: http://vita.had.co.nz/papers/layered-grammar.pdf
* Nice introductory slides to ggplot2: https://pkg.garrickadenbuie.com/gentle-ggplot2/#1

### Other interesting stuff
* A Dramatic Tour through Python’s Data Visualization Landscape (including ggplot and Altair): https://dsaber.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/