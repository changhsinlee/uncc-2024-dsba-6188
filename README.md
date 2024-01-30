## UNCC DSBA 6188 Notebooks

Lecture notes used by DSBA 6188 in Spring 2024

## Running the code

### Requirements

* Python version `>=3.9` is required.

### Create environment

After cloning the repository, create a virtual environment in the repository with

```sh
python3 -m venv .venv
```

### Activate virtual environemnt

After installation, activate the virtual environment and install the repository as a package

```sh
# For Macs or Linux
source .venv/bin/activate

# For Windows
.venv\Scripts\activate
```

and you should see your command line is prepended with `(.venv)`, indicating that now you are in the virtual environment.

To exit virtual environemnt, run

```sh
deactivate
```

### Install packages

After activating virtual environment, run this command to install packages used in this repository. You only need to do this once. Next time you activate virtual environment, the packages will remain.

```sh
pip install -r requirements.txt
```

### Launch Jupyter Lab

After activating virtual environment, run in the project folder (where `.ipynb`'s are)

```sh
jupyter lab
```