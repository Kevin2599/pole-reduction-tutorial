# Reducing magnetic data to the pole and why you probably shouldn't do it

by
[Leonardo Uieda](http://www.leouieda.com)

This paper has been submitted for publication in *The Leading Edge*.


## Abstract

Paste here the abstract.


## Reproducing the results

You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:

    git clone https://github.com/pinga-lab/PAPER-REPO.git

or [click here to download a zip archive](https://github.com/pinga-lab/PAPER-REPO/archive/master.zip).



### Setting up your environment

You'll need a working Python **2.7** environment with all the standard
scientific packages installed (numpy, scipy, matplotlib, etc).  The easiest
(and recommended) way to get this is to download and install the
[Anaconda Python distribution](http://continuum.io/downloads#all).
Make sure you get the **Python 2.7** version.

You can use `conda` package manager (included in Anaconda) to create a
virtual environment with all the required packages installed.
Run the following command in the repository folder (where `environment.yml`
is located):

    conda env create

To activate the conda environment, run

  source activate rtp-tutorial

or, if you're on Windows,

  activate rtp-tutorial

This will enable the environment for your current terminal session.

**Windows users:** It is highly recommended that you install the bash shell
to run code and produce the results here.
You can download bash for Windows at http://git-for-windows.github.io/.
Install the "Git for Windows SDK" that will come with bash and `make` as
well.


### Running the code

To execute the code in the Jupyter notebooks, you must first start the
notebook server by going into the repository folder and running:

  jupyter notebook

Make sure you have the `conda` environment enabled first.

This will start the server and open your default web browser to the Jupyter
interface. In the page, go into the `code` folder and select the
notebook that you wish to view/run.

The notebook is divided cells (some have text while other have code).
Each cell can be executed using `Shift + Enter`.
Executing text cells does nothing and executing code cells runs the code
and produces it's output.
To execute the whole notebook, run all cells in order.


## License

All source code is made available under a BSD 3-clause license.  You can freely
use and modify the code, without warranty, so long as you provide attribution
to the authors.  See `LICENSE.md` for the full license text.

The manuscript text is licensed under a Creative Commons Attribution license.
