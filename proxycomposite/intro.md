[![license](https://img.shields.io/github/license/khider/DISK-proxyComposite.svg)]()

# Proxy Composite using the CFR toolbox

This repository contains a notebook and associated instrumental data to create a proxy composite for the past 2,000 years using the [cfr](https://fzhu2e.github.io/cfr) Python Package. The proxy data comes from a [GraphDB](https://linkedearth.graphdb.mint.isi.edu) with the following query:
* Datasets from the [PAGES2k](https://lipdverse.org/project/pages2k/) and [iso2k](https://lipdverse.org/project/iso2k/) compilations.
* Variables that represent temperature.

The rest of the query allows to make the appropriate figures. 

## Motivation

Proxy records are important to assess the uniqueness of the current warming trend in its geological context. This notebooks allows updating the original "hockey stick" reconstruction with newly available datasets. 

## Authors

Deborah Khider

## Contributors

<a href="https://github.com/khider/DISK-proxyComposite/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=khider/DISK-proxyComposite" />
</a>

Made with [contrib.rocks](https://contrib.rocks).

## Structure

This repository contains one notebook (`HockeyStick.ipynb`) along with the calibration data and several `.csv` files that represent a thesaurus for the various archive and proxy observations. This is only necessary for the figures but may need to be updated as new datasets are added. 