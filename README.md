# Using Jupyter Notebook and Conda Environments for iPython Code Execution
All of the code repositories on this GitHub account contain interactive Python (iPython) files designed to be run within Jupyter Notebook.  For those who are unfamiliar with iPython/Jupyter Notebook, or who are unfamiliar with coding in general, have no fear!  All of the code was designed so that the user need not know anything about programming in order to run the code.  The most a user will need to do is provide the value of a variable (e.g. your expected cell diameter) or the name of a file.  Beyond this, you should be able to simply press play.

## Steps to get started
1. [Download and install Miniconda/Conda](https://conda.io/miniconda.html).
2. Create the necessary Conda environment.  Specific install instructions for creating the environment for a given repository are contained within each repository.  
3. Download all files in the specified repository onto your computer.
4. Activate the Conda environment from the command line terminal on your computer (command: `source activate EnvironmentName`).
5. Launch Jupyter Notebook from the command line terminal on your computer (command: `jupyter notebook`).  We have included jupyter notebook installation in the conda environment installation.
6. _From within Jupyter Notebook_, navigate to the iPython files and open them.  You can now run the code!  If you're new to Jupyter Notebook, you might check out some online tutorials.  There are tons.  [Here's one very simple one.](https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb)

### What is a Conda Environment?  
Conda is a package and environment manager that provides a convenient way to utilize different versions of Python and Python packages for different applications, solving compatibility issues.  Conda allows one to create different ‘environments’ on your computer, each with different versions of Python and any other packages, which you can then flexibly activate to use different applications.  

### Installing Conda and Creating a Conda Environment: 
Unless you have a reason for utilizing the full version of Anaconda, we recommend installing [Miniconda](https://conda.io/miniconda.html) which requires substantially less disk space.  Creating and activating a conda environment is easy to do using very few terminal commands.  See [here](https://conda.io/docs/user-guide/tasks/manage-environments.html) for details.  For each repository we have listed the terminal commands necessary to create the needed conda environment.

### What is Jupyter Notebook?  
Jupyter notbeook is an interactive development platform for programming.  It is in some ways similar to other text editors but has a much more logical flow (at least to us).  Code is organized into distinct ‘cells’ or chunks of code that can be independently run in the order of the user’s preference, and output is displayed just below each cell.  This allows the user to step through the code in a manner that is intuitive and view the results as they go along.  It also makes debugging during development easy. 
