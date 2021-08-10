# stockomen

```diff
- **This repository is currently under construction and is continuously filled with content.**
```

## Background

## Methodology

## Data

## Report

## Requirements

- numpy         1.15.0
- pandas        0.23.4
- matplotlib    2.2.2
- scikit-learn  0.19.1
- jupyter       1.0.0
- nb_conda      2.2.1
- seaborn       0.9.0
- missingno     0.4.1
- cython        0.28.5
- PyHamcrest    1.9.0
- plotly        3.1.0  

## Directory Structure
```
.
├── stockomen 	<- source files used in this project
│   ├── conf
│   ├── data
│   │   ├── ext
│   │   ├── int
│   │   └── raw
│   └── scripts		<- Scripts used in this project.
├── docs		<- Documents related to this project
├── images		<- Images for README.md files
├── notebooks           <- Ipython notebook files
└── reports		<- Generated analysis as HTML, PDF, Latex, etc
    ├── figures		<- Generated graphics and figures used in reporting
    └── logs		<- Generated log files
```
## Installation
Install python dependencies from  `requirements.txt` using conda.
```bash
conda install --yes --file conda-requirements.txt
```

Or create a new conda environment `<new-env-name>` by importing a copy of a working conda environment at the project root directory :`conda-stockomen.yml`.
```bash
conda env create --name <new-env-name> -f conda-stockomen.yml
```
## Usage

## References

## To Do
- [ ] TBA

## License
MIT License 
