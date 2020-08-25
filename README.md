## ML tutorials - UniGe Cosmology Group

This repo contains tutorials for the ML meeting of the cosmology group at the University of Geneva. Please contact benjamin.bose@unige.ch for more information on how to join tutorial sessions or if you have general questions. 

## Key Contributors : 

Michele Mancarella, Joseph Kennedy, David Lous Daverio and Benjamin Bose. 

### Basic setup for Apple/Mac computer with conda

The requirements to run the jupyter notebooks are in the file requirements.txt. Have them installed ! 

If you aer new to python/jupyter, follow the following instructions:

* Install [miniconda](https://conda.io/en/latest/miniconda.html)
See the installation instructions [here](https://conda.io/projects/conda/en/latest/user-guide/install/).
You may need to restart your computer after installation.

* Download or clone the git repo: 
```
git clone https://github.com/nebblu/MLg.git
```

* Add the conda-forge channel 
```conda config --add channels conda-forge```

* Move into the directory with the git repo 
```cd <dir_name>```

* (Optional) Create an environment 
```conda create --name <name> ```

* Install the software 
 
```
conda install --name <name> --file requirements.txt 

conda install --name <name> -c conda-forge jupyter 
```
(If you did not created a dedicated environment, skip the --name option)

* (If you created a dedicated environment) Activate the environment 
```conda activate <name> ```

* Start the jupyter notebook server 
```jupyter notebook```
