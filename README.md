# Tackling and Analyzing COVID-19 with Data Science

<h2> <u> About </u> </h2>
This repo consists of all the  codebase, work, and references, for the Independent Study and Research for Data Science (DSC-199) course from UCSD during Summer 2020 under Ilya Zaslavsky, Director of Spatial Information Systems Laboratory and Peter Rose, Director of Structural Bioinformatics Laboratory at the San Diego Supercomputer Center. 
  
The project attempts to explore metadata representation in Knowlege Graphs and attempts to build automated systems for optimal querying across multiple knowledge graphs to drive data-driven science. As a simple use case, the project attempts to use such systems to link knowledge graphs containing protein-protein interactions and protein-drug interactions to showcase viable drugs for repurposing needs. 

<hr>

<h2> <u> Contents </u> </h2>










* [Notebooks](https://github.com/Krganapa/dsc199/tree/master/notebooks)


* [References](https://github.com/Krganapa/dsc199/blob/master/references/master_list.txt)


<h2> <u> Installation </u> </h2>

Below are instructions to setup this project on your local machine using a Anaconda or miniconda environment. Please ensure that you have installed `git` on your machine beforehand. Further instructions can be found [here](https://git-scm.com/).

**Note: These instructions assume that the directory (`dsc199`) containing all the files will be located in the path `C:\Users\<username>`. Feel free to change where you store your files, but ensure that you are in the same directory for every step.**

**1. Clone this project to your local machine.**

Fork the repository into your own GitHub account (a ```fork``` is a copy of the repository), and run the following on the Anaconda/miniconda prompt:

```
git clone https://github.com/<your-user-name>/dsc199.git
```

You may be asked to enter your GitHub credentials.

**2. Create a conda environment.**

Using a [conda](https://docs.conda.io/en/latest/) environment will help manage modules/dependencies and isolate working environments. The file ```requirements.txt``` specifies the Python version and required libraries.

```
cd dsc199
conda create --name dsc199 python=3.7
```

Once the environment is created, activate it in the Anaconda/miniconda console.

```
conda activate dsc199
```

**3. Install modules.**

Using the `requirements.txt` file located in the `dsc199` directory, install **Jupyter Notebook** and the required libraries using `pip` or `conda`.

```
pip install -U jupyter
pip install -r requirements.txt
```

**4. Launch the Jupyter Notebook.**

Once the environment is fully set-up, launch **Jupyter Notebook** in the console.

```
jupyter notebook
```

This will open up a web-browser where you will access all of the files associated with `dsc199`.

**For Windows users:**
Alternatively, you can write a batch script to start-up the notebook instantly.

On `Notepad`, write the following script:

```
echo off

CALL C:\Users\<username>\miniconda3\Scripts\activate.bat C:\Users\<username>\miniconda3\envs\dsc199
CD /D C:\Users\<username>\dsc199
jupyter notebook

echo on
```
Save the file as `dsc199.bat`. This script will automatically open a browser with **Jupyter Notebook** access.

<hr>
Content will be updated as weeks roll by!

