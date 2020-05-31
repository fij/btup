Installation

1. Install anaconda

2. Download (in zip format or git clone) the course files from github

3. Open an anaconda prompt and install the conda env with 
     conda env create -f env.yml -n fin_course_env
 
3. Activate the conda env with
     conda activate fin_course_env

4. At the anaconda prompt set up nbextensions (including toc) with 
     jupyter contrib nbextension install --user
   
5. Start notebooks:
     cd into the directory where you downloaded the course files
     type: jupyter notebook
