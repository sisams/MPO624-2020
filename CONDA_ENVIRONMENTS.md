## You have to know this much about environments

#### 0. The first time, to **create** an environment: 
From the directory where you find this file, **create** the **MPO624 environment** by typing: 

`conda env create -f MPO624_conda_environment.yml`

#### 1. To "activate" an environment and launch jupyter in it, type the following: 

`source activate MPO624`
`jupyter notebook`

##### 2. To **update** your environment in a documented way, step out of it first: 

`source deactivate`

Then, edit your .yml file as desired, and use `update` instead of `create` like this: 

`conda env update -f MPO624_conda_environment.yml`


### 3. Cleanup: conda can use a lot of disk space as it updates packages to the latest version, but leaves the old versions lying around. You might like to use

`conda clean` 

The [conda cheat sheet](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf) has more. 
