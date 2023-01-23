# Coding assignment of machinery analytics

This repo contains the following folders:

* main.py
* functions.py
* input folder
* output folder 
* requirements.txt


### main.py
This file includes the core part of the code and all the functions are called there to produce the final result. To get the desired JSON file, run main.py.


### functions.py
From getting the raw data to the desired JSON file, all is done by functions in functions.py. 

### requirement.txt
This file contains all the libraries used in the code. It will be used to create a virtual environment to run the code.

### input folder
The raw data is stored into the input folder.

### output folder
The requested JSON file is stored in this folder.

## Instruction to run the code

1- Open the termial and clone the repo to your terminal

```bash
git clone git@github.com:erfanbyt/machinery_analytics.git
```

2- change the directory to the project's folder


```bash
cd machinery_analytics
```

3- create a virtual environment (venv) in the directory


```bash
python3 -m venv venv
```

4- activate the virtual environment 

```bash
source venv/bin/activate
```

5- install the required libraries from requirements.txt

```bash
pip install -r requirements.txt
```

6-  run the python code

```bash
python main.py
```

After running the code successfully, "Code executed successfully!" will be displayed; a JSON file "results_Erfan" will be created.
























