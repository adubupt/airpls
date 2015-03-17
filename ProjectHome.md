beauty and art of penalty.


<h3>1. Intorduction</h3>
> adaptive iteratively reweighted Penalized Least Squares (airPLS) algorithm doesn’t require any user intervention and prior information, such as detected peaks. It iteratively changes weights of sum squares errors (SSE) between the fitted baseline and original signals, and the weights of SSE are obtained adaptively using between previously fitted baseline and original signals. This baseline estimator is fast and flexible in fitting baseline.


<h3>2. Installation</h3>

<h4>2.1 C++ version</h4>

We have already noticed the parameter optimizing problem in R and Matlab version of airPLS. So we have rewritten this airPLS algorithm in C++ and MFC (Visual Studio 2010) to provide a better user interface for baseline-correction. One can tune the lambda parameter by dragging the slider easily.

1. airPLS version 2 can be downloaded from http://airpls.googlecode.com/files/airPLS2.0.exe

<font color='#0000ff'>

What's new in C++ version 2:<br>
<br>
(1). The development environment is upgraded to visual c++ 2010, So there are no need to install the runtime of C++ anymore. Just copy the dll files to the airPLS.exe directory is OK.<br>
<br>
(2). The MALDI-TOF data is removed from the setup file to reduce the size of setup file.<br>
<br>
</font>


2. airPLS version 1 can be downloaded from http://airpls.googlecode.com/files/airPLS.exe

![http://airpls.googlecode.com/files/cplusplusversion.jpg](http://airpls.googlecode.com/files/cplusplusversion.jpg)

<h4>2.2 MATLAB version</h4>

1. Install MATLAB 6.5 or higher in you computer

2. download, unzip and enjoy it http://airpls.googlecode.com/files/airPLS%202.0%20matlab.rar

<h4>2.3 R version</h4>

<h5>2.3.1 airPLS 2.0</h5>

<font color='#0000ff'>
What New of airPLS in R version 2.0.0:<br>
<br>
By taking the advantage of sparse matrix in R package "Matrix", we implemented the sparse version of whittaker smoother and airPLS alogrithm. Now the speed of airPLS 2.0 is faster than airPLS 1.0 by 100 times or more.<br>
</font>


Firstly, you must download and install R 2.12.2 from the urls as follows:

> for linux: http://cran.r-project.org/src/base/R-2/R-2.12.2.tar.gz

> for windows: http://cran.r-project.org/bin/windows/base/old/2.12.2/R-2.12.2-win.exe

Then, download the airPLS package from this project download pages.


> for linux: http://airpls.googlecode.com/files/airPLS_2.0.0.tar.gz

> for windows: http://airpls.googlecode.com/files/airPLS_2.0.0.zip

<h5>2.3.2 airPLS 1.0</h5>

Firstly, you must download and install R 2.8.1 from the urls as follows:

> for linux: http://cran.r-project.org/src/base/R-2/R-2.8.1.tar.gz

> for windows: http://cran.r-project.org/bin/windows/base/old/2.8.1/R-2.8.1-win32.exe

Then, download the airPLS package from this project download pages.


> for linux: http://airpls.googlecode.com/files/airPLS_1.0.0.tar.gz

> for windows: http://airpls.googlecode.com/files/airPLS_1.0.0.zip


Finally,install the downloaded packages from local zip or tar.gz file.

To start running this algorithm, load the airPLS package through "library(airPLS)" in the R commandline windows, try "?airPLS" in the R commandline windows to open the documents.


<h4>2.4 Python version</h4>

<h5>2.4.1 Python version of airPLS 2.0</h5>

<font color='#0000ff'>

Python version of airPLS using the scipy framework by Renato<br>
Lombardo of University of Palermo.<br>
<br>
</font>


<h5>2.4.2 Usage of the Python version</h5>

1. Download and install the TortoiseSVN
2. Clone a copy of Python verison of airPLS using following command:
> svn checkout https://airpls.googlecode.com/svn/trunk/

> or just download copy of airPLS from this URL:
> > https://airpls.googlecode.com/svn/trunk/airPLS.py

3. Download and Install Python 2.7, NumPy, SciPy and Matplotlib.

> The Spyder IDE is cool for editing and debugging Python Code.
> It can be downloaded from https://bitbucket.org/spyder-ide/spyderlib/downloads.

4. Some simulated datasets will be generated in the unit test of this file.
> You can try the Python version of airPLS by just running this py file with python interpreter.
> If you want to try it with your dataset, please use scipy.io.loadmat or scipy.io.netcdf to import your datasets for baseline correction.




<h3>3. Contact</h3>

For any questions, please contact:

Yi-Zeng Liang: yizeng\_liang@263.net

or:

Zhi-Min Zhang: zhangzhimin.csu@gmail.com


<h3>4. <font color='#cc0000'>How to cite:</font></h3>


Z.-M. Zhang, S. Chen, and Y.-Z. Liang, Baseline correction using adaptive iteratively reweighted penalized least squares. Analyst 135 (5), 1138-1146 (2010).

<a href='http://www.rsc.org/ej/AN/2010/b922045c.pdf'><font color='#0000ff'>Download pdf and endnote citation here</font></a>
