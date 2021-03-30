Introduction
============

AliGater is intended as a rapid application development environment for high-throughput gating using pattern recognition functions and libraries. It provides a framework with basic gating functionality and then lets you build your own mathematical and pattern recognition functions in your strategies.

Typically you can explore and gate your data in a notebook environment then run thousands of gates using the same strategy. See sample notebooks (to be made) for examples.

Jupyter templates for evaluating QC objects (downsampled image views) using PCs and UMAP clustering is also available.

**Features**

- Several pre-built functions to make gating easier, from simple thresholding and fixed quadgates to 1-2d mixed gaussian modelling, dijkstras shortest path implementations and principal components.
- Support for crunching through folder hierarchies with sample files and linking folder names to your experiment.
- Straight-forward requirements to build your own pattern-recognition methods into the workflow.
- Easily integrates with methods of libraries like scikit-learn & scipy.

**Installation**

Install AliGater by running below, which will also build the cython shared object from source:

``git clone https://github.com/LudvigEk/aligater``

``python3 setup.py build_ext --inplace``

``pip -e install .``

**Contribute**

- Issue Tracker: github.com/LudvigEk/Aligater/issues
- Source Code: github.com/LudvigEk/Aligater

**Support**

Main developer; ludvig.ekdahl@med.lu.se

**License**

MIT

**Citation**