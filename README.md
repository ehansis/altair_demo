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

* `quickstart_example.ipynb`: Example from the quickstart section of the Altair docs (to check installation worked)
* `display_examples.ipynb`: Different ways of showing or saving charts
* `interactive_examples.ipynb`: Some interactive examples copied from the Altair docs
* `talk_plots.ipynb`: Example plots used in talk slides

**Please note:** Interactive graphs work neither in the GitHub notebook preview nor in [nbviewer](https://nbviewer.jupyter.org/).
To play with the interactive graphs you'll have to clone the notebook and open it in your local JupyterLab environment.
For some graphs there's also a `html` version saved in the `output` folder.

(Or does anybody know how to view notebooks with interactive graphs in a zero-installation way like `nbviewer`? Let me know!)


## References

### Packages
* Altair docs: <https://altair-viz.github.io/index.html>
* Alteir example gallery - the best place to start! <https://altair-viz.github.io/gallery/index.html#>
* Vega-Lite docs: <https://vega.github.io/vega-lite/>
* Vega-Embed docs: <https://github.com/vega/vega-embed>

### Grammar-of-Graphics background
* Wickham paper, base for ggplot2: <http://vita.had.co.nz/papers/layered-grammar.pdf>
* Nice introductory slides to ggplot2: <https://pkg.garrickadenbuie.com/gentle-ggplot2/#1>

### Other interesting stuff
* A Dramatic Tour through Python’s Data Visualization Landscape (including ggplot and Altair): <https://dsaber.com/2017/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/>
* Jake VanderPlas - How to Think about Data Visualization - PyCon 2019: <https://www.youtube.com/watch?v=vTingdk_pVM>
