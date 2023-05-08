# Tomogram downloader

A collection of examples for downloading tomograms from the Caltech Tomogram
Archive in CaltechDATA.

[![License](https://img.shields.io/badge/License-BSD--like-lightgrey)](https://choosealicense.com/licenses/bsd-3-clause)
[![Latest release](https://img.shields.io/github/v/release/caltechlibrary/template.svg?color=b44e88)](https://github.com/caltechlibrary/template/releases)
[![DOI](https://data.caltech.edu/badge/201106666.svg)](https://data.caltech.edu/badge/latestdoi/201106666)


## Table of contents

* [Introduction](#introduction)
* [Installation](#installation)
* [Getting help](#getting-help)
* [Contributing](#contributing)
* [License](#license)
* [Authors and history](#authors-and-history)
* [Acknowledgments](#authors-and-acknowledgments)


## Introduction

The `download-tomograms.ipynb` contains an example of downloading tomograms via
the Open Storage Network S3 interface. First a search query is run in
CaltechDATA based on a subject keyword (species in the example). You can also
search based on any of the other metadata in CaltechDATA by just modifying the
API call.The notebook then processes the response to extract the tilt series ID
and DOI of each hit.

You need the tile series ID to retrieve data from the Open Storage network. The
example in the notebook uses s3fs, but you can use any S3-enabled tool to
download the data.

## Installation

This notebook assumes you have a python installation with jupyter and python
dependencies `requests` and `s3fs` installed.

## Getting help

Make an issue in the issue tracker

## Contributing

Pull requests are very welcome

## License

Software produced by the Caltech Library is Copyright © 2022 California Institute of Technology.  This software is freely distributed under a BSD-style license.  Please see the [LICENSE](LICENSE) file for more information.


## Authors and history

Tom Morrell

## Acknowledgments

This work was funded by the Jensen Lab and the California Institute of Technology Library.


<div align="center">
  <br>
  <a href="https://www.caltech.edu">
    <img width="100" height="100" src="https://raw.githubusercontent.com/caltechlibrary/template/main/.graphics/caltech-round.png">
  </a>
</div>
