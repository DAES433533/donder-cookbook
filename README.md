<img src="thumbnail.png" alt="thumbnail" width="300"/>

# Visualizing Data with EPA's Air Quality System (AQS) API

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

This Project Pythia Cookbook covers ways to utilize the [US EPA's AQS](https://www.epa.gov/aqs) as a repository for air pollution data. Notebooks will go over topics related to accessing the data, plotting a time-series, making the time series interactive, plotting the data over a map, and making an interactive time-series map.

You will need an active email address for an API key to use this Cookbook.

## Motivation

At the end of this Cookbook, you should have the skills to:
- access the AQS using the EPA's "pyaqsapi" package
- manipulate AQS data
- plot AQS data from a spatiotemporal perspective
- generate interactive air pollution figures

## Authors

[Adam Deitsch](https://github.com/AMDeitsch), [Sam DeSousa](https://github.com/wxsamdes), [Kayla Lewis](https://github.com/KaylaLewis23), [Anadhi Sharma](https://github.com/zee290)


### Contributors

<a href="https://github.com/ProjectPythia/cookbook-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/cookbook-template" />
</a>

## Structure

This Cookbook will be broken into four sections.

### Section 1 ("AQS Data Foundations")

1. Accessing data from the AQS
2. Exploring the format of the data
3. Preparing the data for visualization
4. Generating a time-series plot

### Section 2 ( Interactive Time Series Title )

1. 
1. 
1. 
1. 


### Section 3 ( Map Plot? )

1. 
1. 
1. 
1. 

### Section 4 ( Interactive/Met Map Plot? )

1. 
1. 
1. 
1. 

## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

(Replace "cookbook-example" with the title of your cookbooks)

1. Clone the `https://github.com/ProjectPythia/cookbook-example` repository:

   ```bash
    git clone https://github.com/ProjectPythia/cookbook-example.git
   ```

1. Move into the `cookbook-example` directory
   ```bash
   cd cookbook-example
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate cookbook-example
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
