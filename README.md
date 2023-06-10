## Open Data on GitHub Dataset

This repo contains the dataset files for the Open Data on GitHub paper.

## Background

GitHub is the world’s largest platform for collaborative software development, with over 100 million users. GitHub is also used extensively for open data collaboration, hosting more than 800 million open data files, totaling 142 terabytes of data. This study highlights the potential of open data on GitHub and demonstrates how it can accelerate AI research. We analyze the existing landscape of open data on GitHub and the patterns of how users share datasets. Our findings show that GitHub is one of the largest hosts of open data in the world and has experienced an accelerated growth of open data assets over the past four years. By examining the open data landscape on GitHub, we aim to empower users and organizations to leverage existing open datasets and improve their discoverability – ultimately contributing to the ongoing AI revolution to help address complex societal issues. We release the three datasets that we have collected to support this analysis as open datasets in this repository.

## Requirements

### Steps for generating the `datapackage.json` file

1. Run `pipenv install` to install the dependencies. If you don't have pipenv installed, follow the instructions on https://pipenv.pypa.io/en/latest/.
2. Run `pipenv shell` to activate the virtual environment.
3. Run `python3 generate_datapackage.py` to generate the `datapackage.json` file.

## License 

The data associated with this project is licensed under the terms of the Community Data License Agreement - Permissive - Version 2.0 license. Please refer to [CDLA-Permissive-2.0](./LICENSE.md) for the full terms.

The (minimal) [code](./generateDatapackage.py) in this project is licensed under the terms of the MIT open source license.
