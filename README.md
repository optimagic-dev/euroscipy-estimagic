# Tutorial - EuroSciPy 2023

## Introduction to numerical optimization

> by Janos Gabler & Tim Mensinger

## Contents

- [Installation](#installation)
- [Slides](#slides)
- [Exercises](#exercises)
- [Troubleshooting](#troubleshooting)

> **Warning** Please pull the repo and update your conda environment before the tutorial
> to make sure that the most recent versions are installed.

## Installation

1. Install [miniconda](https://docs.conda.io/en/latest/miniconda.html)

1. Clone the repository

   ```console
   $ git clone https://github.com/OpenSourceEconomics/euroscipy-estimagic.git
   $ cd euroscipy-estimagic
   ```

1. Install and activate the environment

   ```console
   $ conda env create -f environment.yml
   $ conda activate euroscipy-estimagic
   ```

   > **Note** You have to repeat the activation step each time after closing your
   > terminal.

1. Update the environment

   > **Note** This step is only necessary if you have installed the environment a long
   > time ago and want to make sure that you're using the most recent versions.

   ```consolse
   $ cd euroscipy-estimagic
   $ conda activate euroscipy-estimagic
   $ conda env update -f environment.yml
   ```

   or use a completely fresh install:

   ```console
   $ cd euroscipy-estimagic
   $ conda deactivate euroscipy-estimagic
   $ conda env remove --name euroscipy-estimagic
   $ conda env create -f environment.yml
   ```

## Slides

You can download the slides by clicking
[here](https://github.com/OpenSourceEconomics/euroscipy-estimagic/raw/main/slides.pdf), or
you can view them directly on GitHub
[here](https://github.com/OpenSourceEconomics/euroscipy-estimagic/blob/main/slides.pdf).

## Exercises

You find the exercise notebooks in the folder
[exercises](https://github.com/OpenSourceEconomics/euroscipy-estimagic/tree/main/exercises),
and the corresponding solutions in the folder
[solutions](https://github.com/OpenSourceEconomics/euroscipy-estimagic/tree/main/solutions).

## Troubleshooting

If you have questions, problems with the installation or any other part of the
repository, please
[open an issue](https://github.com/OpenSourceEconomics/euroscipy-estimagic/issues).
