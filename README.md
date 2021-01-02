
(A) Introduction

1. Quantitative Finance / Financial Engineering is usually considered to be a composition of three main areas:
   - Financial markets and products.
   - Quantitative modeling.
   - Data processing and analysis.

2. Goals are complex. Business needs speed, product flexibility, high stability, low costs and high returns at the same time.

3. Note that finance, similary to other fields, has many of its own technical terms.


(B) Recommended learning:

1. Video courses:<br/>
   1.1 Arzu Ozoguz: Global Financial Markets and Instruments<br/>
       https://www.coursera.org/learn/global-financial-markets-instruments<br/>
   1.2 Damir Filipovic: Interest Rate Models<br/>
       https://www.coursera.org/learn/interest-rate-models<br/>
   1.3 Martin Haugh and Garud Iyengar: Financial Engineering and Risk Management Part I, also Part II<br/>
       https://www.coursera.org/learn/financial-engineering-1

2. A detailed syllabus with book titles. Google finds the majority of the PDFs of the listed books.<br/>
   Global Association of Risk Professionals (GARP): Financial Risk Manager (FRM) 2020 Learning Objectives<br/>
   https://www.garp.org/#!/landing/2020-frm-learning-objectives

3. Investopedia - Descriptions / Summaries / Short videos<br/>
   Example: https://www.investopedia.com/terms/f/fixedincome.asp , see also menu on the left<br/>
   Warning: _avoid_ the ads


(C) How to use these jupyter notebooks on your computer:

1. Install anaconda on your computer<br/>
   . please see https://www.anaconda.com/products/individual

2. Download the files from this github repository to your computer<br/>
   . either download all files in a single zip package or git clone the repo

3. Open an anaconda prompt on your computer and install the conda environment<br/>
   . 3.1 change into the directory where you downloaded (or git cloned) the files<br/>
   . 3.2 `conda env create -f fin_course_env.yml`
 
4. Activate the installed conda environment with<br/>
   . `conda activate fin_course_env`

5. At the anaconda prompt set up nbextensions with<br/>
   . `jupyter contrib nbextension install --user`

6. Start using the notebooks in your default browser:<br/>
   . type `jupyter notebook` at your anaconda prompt

7. On the main page of jupyter notebook open the Nbextensions panel<br/>
   . 7.1 enable configurations: uncheck the "disable" box, if it is checked<br/>
   . 7.2 turn on the nbextension "Table of Contents"

8. Several notebooks will ask you to download free data that they process.


(D) Planned items:

1. Black-Derman-Toy model with calibration

2. Yield curve calculation from LIBORs (RFRs?) + Swaps + Bonds (?)
