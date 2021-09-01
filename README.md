# paper-lunches
Notebooks and presentations related to papers discussed at our "paper lunch" events. The idea is to perform a thorough dissection and walkthrough of an external paper.

## Pre-requisites

[Poetry](https://python-poetry.org/) is needed to faithfully reproduce and run all notebooks.

## Usage

Assuming Poetry is installed, to run a notebook simply `cd` into the notebook directory, initialize the Poetry environment, and then run the notebook, e.g.

```
cd fb-randsent
poetry install
poetry shell
jupyter notebook
```

To then run the notebook in the presentation mode, simply run `run_presentation.sh` from within notebook directory.

## List of Papers

[No Training Required: Exploring Random Encoders for Sentence Classification, J. Wieting, D. Kiela](fb-randsent/randsent.ipynb)