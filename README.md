CCIDataPreparation
------------------

## About

This repository contains the documentation on how to prepare observational data from the ESA-CCI ECV teams to become an ops4MIPs dataset.

## Development

Create and activate the conda environment `cci` with the following command:

```
conda env create -f environment.yml
conda activate cci
```

Build/rebuild the html pages with 

```
make html
```

and run a development server from the `build/html` directory, e.g.:

```
cd build/html
python -m http.server 8000
```

Point your browser to `localhost:8000` and start developing.

## Acknowledgments

This work is part of the ESA CCI+ CMUG project. 
