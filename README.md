# Using Jupyter Notebook and Conda Environments for iPython Code Execution
All of the code repositories on the Cai Lab GitHub account contain interactive Python (iPython) files designed to be run within Jupyter Notebook.  For those who are unfamiliar with iPython/Jupyter Notebook, or who are unfamiliar with coding in general, this code was designed with you in mind.  The goal is for the user to have to alter a minimal amount code in order for these scripts to work.  Ideally, the user should only have to alter the values of certain variables.  Where this is not possible, we try to direct the user towards resources that will enable them to hone their skills so that they can use the code.  At the same time, all code is accessible so that those with more coding experience can modify the code to suit their purposes.  Any and all feedback is appreciated!

## Steps to get started
1. [Download and install Miniconda/Conda](https://conda.io/miniconda.html).  Download version with Python 3.7.
2. Create the necessary Conda environment.  Because each repository has diffferent package dependencies, specific install instructions for creating the environment for a given repository are contained within each repository's README section.
3. From githug, download all files in the specified repository onto your computer.  On the main page of the repository, click the button to clone or download, and download the zip folder onto your harddrive (don't forget to unzip the folder).  Alternatively, use git commands if you are familiar with them.
4. Activate the Conda environment from the command line terminal on your computer.  On a mac, use your finder to open Terminal and enter the command: `source activate EnvironmentName`.  On a windows os, search for 'Anaconda Prompt'.  Once open, enter the command `conda activate EnvironmentName`.  
5. Launch Jupyter Notebook from the command line terminal on your computer (command: `jupyter notebook`).  We have included jupyter notebook installation in the conda environment installation.
6. **From within Jupyter Notebook**, navigate to the iPython files and open them.  You can now run the code!  If you're new to Jupyter Notebook, you might check out some online tutorials.  There are tons.  [Here's one very simple one.](https://nbviewer.jupyter.org/github/jupyter/notebook/blob/master/docs/source/examples/Notebook/Notebook%20Basics.ipynb)

### Do I need to install Python?  Do I need to install a text editor? Do I need to download and install Jupyter Notebook.
No.  The correct version of Python, as well as jupyter notebook, are included in the conda environment installation.  Additionally, all code is run within Jupyter Notebook and a separate text editor is not needed.

### What is a Conda Environment?  
Conda is a package and environment manager that provides a convenient way to utilize different versions of Python and Python packages for different applications, solving compatibility issues.  Conda allows one to create different ‘environments’ on your computer, each with different versions of Python and any other packages, which you can then flexibly activate to use different applications.  

### Installing Conda and Creating a Conda Environment: 
Unless you have a reason for utilizing the full version of Anaconda, we recommend installing [Miniconda](https://conda.io/miniconda.html) which requires substantially less disk space.  Creating and activating a conda environment is easy to do using very few terminal commands.  See [here](https://conda.io/docs/user-guide/tasks/manage-environments.html) for details.  For each repository we have listed the terminal commands necessary to create and activate the needed conda environment.

### What is Jupyter Notebook?  
Jupyter notbeook is an interactive development platform for programming.  It is in some ways similar to other text editors for coding but has a much more logical flow (at least to us).  Code is organized into distinct ‘cells’ or chunks of code that can be independently run in the order of the user’s preference, and output is displayed just below each cell.  Moreover, each cell of code can be placed in between instructions.  This allows the user to step through the code in a manner that is intuitive and view the results as they go along.  It also makes debugging during development easy.

