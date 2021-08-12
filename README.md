# Easy PDA (Patron Driven Aquisition) for the [Max-Planck-Institute for the Study of Societies](http://www.mpifg.de)

- autor: [Cora Molloy](mailto:cm@mpifg.de)
- coded 2021 as final project in the certification course "Data Librarian" at the ZBIW, advised by [Konrad U. Foerstner](https://github.com/konrad)
- This code is free for usage in others projects. Please note, that the URL for data download is limited to usage of the Max-Planck-Institute for the Study of Societies

## About

This code was created for a project at the Max-Planck-Institute for the Study of Societies in developing a workflow to fetch, check and prepare bookstore data to be imported into Aleph Software (and from there into the vufind discovery).

The import into Aleph allows us to check and work with the data before they are exported into vufind. The existing export routines from the title and holdings data of the Institute could easily be re-used and the whole idea was, to create a workflow, that is a simple as possible.

## Documentation

- Documentation is included as comments in the Jupyter Notebook itself, see [PDA_MPIfG.ipynb](PDA_MPIfG.ipynb).
- As there is a second step necessary to enrich the data with a working permanent Mailto-Link, a second Jupyter Notebook titled [mailto_link_skript](mailto_link_skript.ipynb) is also included in this repo.
- an executable version of this notebook has been made accessible via [mybinder.org](https://mybinder.org/v2/gh/cogemol/PDA_am_MPIfG/HEAD)

## Requirements

The notebook was created with Visual Studio Code 1.58.2  
It was written in python 3.8.10 / 64-bit  
For more information on dependencies see: [requirements.txt](requirements.txt)  
