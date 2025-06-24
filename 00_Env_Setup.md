# Python Environment Management


## Create Conda environment

### Assumption
You have installed anaconda on your device

### Step 1
Windows OS or Mac OS
1.	Open the Anaconda Prompt on your computer. <br>
NB: This can be found by searching for the application in the search bar located in the task bar (Windows OS) or command + space bar (Mac OS).

![anaconda_prompt](https://github.com/user-attachments/assets/ac9f9f6b-b21a-44a6-b9b3-8f3b608b4009)


### Step 2
Create your new python environment using the following command:
```bash
conda create -n analysis_env python
```
This will automatically build a conda virtual environment called “analysis_env” that will have python downloaded into it

### Step 3
After a moment, the creation of the virtual environment will begin, and you will be asked if you wish to proceed: Yes, is the answer, so type y and hit enter.  

![create_env](https://github.com/user-attachments/assets/c23b1477-e614-4c30-b1b1-3b2f5f095caa)

### Step 4

Voila! 
The virtual environment is now create and ready for you to use.

![env_created](https://github.com/user-attachments/assets/515a167f-2c4a-477d-9f31-f929a3a30da1)

### Step 5

Activate the virtual environment: 
```bash 
Conda activate analysis_env
```
Now you should have `(analysis_env)` in your prompt
### Step 6
Now we will install the packages that will be needed for this workshop, we will install the following packages using Pip. <br>
Pip is a package management software that is used for the installation and management of packages within python.

We will install the following packages: 

* jupyter – An interface for coding in python
* tifffile – A package for opening .tif files. 
* Scikit-image – A package designed for image analysis
* Pandas – A package to manage databases in python
* Matplotlib – A package for visualising graphs

The command to do this is:
```bash 
pip install jupyter tifffile scikit-image pandas matplotlib

```

Bravo!!! <br>
You are set for intresting image analaysis.
