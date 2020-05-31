
Installation

1. Install anaconda
     please see https://www.anaconda.com/products/individual

2. Open an anaconda prompt and install the conda environment with
     conda env create -f fin_course_env.yml
 
3. Activate the conda environment with
     conda activate fin_course_env

4. At the anaconda prompt set up nbextensions (including toc) with 
     jupyter contrib nbextension install --user
   
5. Download the files of this directory from github
     download the directory as a single zip package or git clone the repo

6. Start notebooks:
     cd into the directory where you downloaded (or git cloned) the files
     type 'jupyter notebook' to start the notebooks in your default browser
