## Financial Engineering, BMETE15MF78


### (A) Grading:

Please see https://physics.bme.hu/BMETE15MF78_kov?language=en


### (B) Topic Description:

1. Business goals usually combine many factors: responsible behavior, application of best industry practices in the interest of the client, product flexibility and stability, continuity of business, risk management, continuous development, speed, profit, and many others.

2. Accordingly, Financial Engineering is a mix of several different approaches :
   - **Finance:** Markets, Products
   - **Math:** Modeling, Data analysis
   - **Coding:** Software implementation and testing

3. Similarly to other fields, finance also has its own extensive **technical language**. Examples: spread, fixing, leg.


### (C) Purpose of the course:

Show by examples how Finance, Math and Coding are connected.

**Note** that code in these notebooks is for **illustration only**.


### (D) Structure of each lesson:

1. New material is presented. You must guide the lecturer with your questions.

2. Problems are solved together.


### (E) How to use the jupyter notebooks on your computer:

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

6. Set your jupyter notebook password with `jupyter notebook password`.

7. Start using the notebooks in your default browser:
   * type `jupyter notebook` at your anaconda prompt

8. On the main page of jupyter notebook open the Nbextensions panel
   * 8.1. enable configurations by unchecking the `disable` box, if it is checked
   * 8.2. turn on the nbextension `Table of Contents`

9. Several notebooks will ask you to download free data that they process.
   * 9.1. Please create your local subfolder called `data` within the folder that contains this README file.
   * 9.2. Download the requested files to this local subfolder.


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

3. Emanuel Derman and Paul Wilmott: The Financial Modelers' Manifesto

4. Alex Kuznetsov: The Complete Guide to Capital Markets for Quantitative Professionals

5. John Hull: Options, Futures, and Other Derivatives



### (G) Acknowledgements

I thank all those who found the time to teach me.
