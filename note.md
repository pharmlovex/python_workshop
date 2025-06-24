## Create Python Virtual environment
### Assumptions
You have installed python on your device
### Step 0
Create a folder for your your workspace

```
mkdir myworkspace
cd myworkspace
```
### Windows OS
### Step 1
On Windows, you can create a virtual environment by running the following command in the terminal

```
python -m venv analysis_env
```
This would a create a directory in your workspace folder called analysis_env

### Step 2
Activate the python virtual env 

```
analysis_env\Scripts\activate.bat
```
Now you should have `(analysis_env)` in your prompt

### Linux OS & Mac OS

### Step 1
you can create a virtual environment by running the following command in the terminal

```
python3 -m venv analysis_env
```
This would a create a directory in your workspace folder called analysis_env

### Step 2
Activate the python virtual env 

```
source analysis_env/bin/activate
```
Now you should have `(analysis_env)` in your prompt

## All devices