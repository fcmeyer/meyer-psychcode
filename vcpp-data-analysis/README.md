## vCPP Data Extraction Tool

This Python script was designed for extracting data collected using the vCPP gmod task at the Childs and de Wit labs. The code is not too fancy, but it gets the job done.

In order to use this script, you will need to have a Python 2.7 distribution installed in your computer that includes all necessary components invoked. If you are not a coder or have never really dabbled in Python, a simple way to get this running is to install the free [Anaconda Scientific Python Distribution][1]. Please ensure you are downloading **Python 2.7** (it's the default).

Once you have installed Anaconda, you will need to [download the vcpp-data-full.py script file][2] (right-click "Save Target As...") to a location in your computer. I recommend making a folder with no spaces in its name.

### Usage

The script is invoked through a simple command line syntax, as follows:

`python vcpp-data-full.py <path_to_data_files>`

After being run, the script will generate the following output in the current directory:

`RWD_OUT.csv`

`BLN_OUT.csv`

`LOC_OUT.csv`

`graphs/<several png graphs of movement in a trial>`


[1]: https://store.continuum.io/cshop/anaconda/ 
[2]: https://raw.githubusercontent.com/fcmeyer/meyer-psychcode/master/vcpp-data-analysis/vcpp-full-data.py