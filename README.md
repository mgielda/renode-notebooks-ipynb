# Renode Jupyter/Colab notebooks in ipynb

This repo contains Renode interactive Jupyter notebooks that can be run in the cloud e.g. using Google's Colab.
This will let you try out some of Renode's features without having to install anything (but as you will see in the notebooks themselves, installing Renode is actually very easy).

> Files in this repository are auto-generated from source .py files. Do not edit the repo manually other than the README.

## Running on Colab in the cloud

* [HiFive Unleashed execution metrics demo](https://colab.research.google.com/github/mgielda/renode-notebooks-ipynb/blob/master/unleashed-metrics.ipynb)

## Connect to a local runtime in Colab (optional)

* pyrenode (super simple script a variant of renode-pytest)
* Jupyter notebook installed and running locally:

```
python3 -m jupyter notebook \
  --NotebookApp.allow_origin='https://colab.research.google.com' \
  --port=8888 \
  --NotebookApp.port_retries=0
```

* following this guide: https://research.google.com/colaboratory/local-runtimes.html

## Running entirely locally

Close this repo, then use Jupyter notebook as normal.

## TODO

* [ ] Automatically generate the demo list, also include it in the notebooks.
