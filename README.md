
Getting started

1. Install anaconda on your computer<br/>
   . please see https://www.anaconda.com/products/individual

2. Download the files from this github repository to your computer<br/>
   . either download all files in a single zip package or git clone the repo

3. Open an anaconda prompt on your computer and install the conda environment<br/>
   . 3.1. change into the directory where you downloaded (or git cloned) the files<br/>
   . 3.2. `conda env create -f fin_course_env.yml`
 
4. Activate the installed conda environment with<br/>
   . `conda activate fin_course_env`

5. At the anaconda prompt set up nbextensions with<br/>
   . `jupyter contrib nbextension install --user`

6. Start using the notebooks in your default browser:<br/>
   . type `jupyter notebook` at your anaconda prompt
