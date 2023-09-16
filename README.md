## Financial Engineering, BMETE15MF78

### (A) Grading:

Please see https://physics.bme.hu/BMETE15MF78_kov?language=en


### (B) Topic Description:

1. The goals of business usually combine many factors: responsible behavior, application of best practices in the interest of the client, product flexibility and stability, speed, profit, liquidity, and many others.

2. Accordingly, Financial Engineering is a composition of several areas:
   - Finance: Markets, Products
   - Math: Modeling, Data analysis
   - Coding: Software implementation and testing

3. Similarly to other fields, finance also has many of its own technical terms.


### (C) Purpose of the course:

Show through examples how Products, Math, Coding are connected.


### (D) Structure of each lesson:

1. New material is presented. You must guide the lecturer with your questions.
2. Problems are solved together.


### (E) How to use these jupyter notebooks on your computer:

1. Download the files from this github repository to your computer
   * either download all files in a single zip package or git clone the repo

2. Install anaconda on your computer
   * please see https://www.anaconda.com/products/individual

3. Open an anaconda prompt on your computer and install the conda environment
   * 3.1 change into the directory where you downloaded (or git cloned) the files of this repo
   * 3.2 execute this command: `conda env create -f fin_course_env.yml`
 
4. Activate the installed conda environment with
   * `conda activate fin_course_env`

5. At the anaconda prompt set up extensions:
   * set up nbextensions: `jupyter contrib nbextension install --user`
   * set up the rise extension:
     * install with `jupyter-nbextension install rise --py --sys-prefix`
     * initialize with `jupyter nbextension enable rise --py --sys-prefix`

6. Start using the notebooks in your default browser:
   * type `jupyter notebook` at your anaconda prompt

7. On the main page of jupyter notebook open the Nbextensions panel
   * 7.1. enable configurations by unchecking the `disable` box, if it is checked
   * 7.2. turn on the nbextension `Table of Contents`

8. Several notebooks will ask you to download free data that they process.
   * 8.1. First, please create your local subfolder called `data` in the folder that contains this README file.
   * 8.2. Second, download the requested files to this local `data` folder.


### (F) Recommended Further Learning:

1. Courses:
   * 1.1 Arzu Ozoguz: Global Financial Markets and Instruments<br/>
       https://www.coursera.org/learn/global-financial-markets-instruments
   * 1.2 Damir Filipovic: Interest Rate Models<br/>
       https://www.coursera.org/learn/interest-rate-models
   * 1.3 Martin Haugh and Garud Iyengar: Financial Engineering and Risk Management Part I, also Part II<br/>
       https://www.coursera.org/learn/financial-engineering-1

2. Investopedia - Descriptions / Summaries / Short videos<br/>
   Example: https://www.investopedia.com/terms/f/fixedincome.asp , see also menu on the left<br/>
   Warning: _avoid all ads_

3. The Financial Modelers' Manifesto, by Emanuel Derman and Paul Wilmott (pdf, 2 pages)


### (G) Acknowledgements

I would like to thank all those who found the time to teach me.

