## You have to know this much about environments

From the directory where you find this file, you must **create** the **MPO624 environment** like this: 

`conda env create -f MPO624_conda_environment.yml`

And of course, to "activate" an environment before launching jupyter, 
source activate MPO624

If we need more packages, more lines can be added to that file (it is easy to read). To **update** your environment in a documented way, without reinstalling all its packages, step out of it first: 

`source deactivate`

Then, edit your .yml file as desired. Then, 

`conda env update -f MPO624_conda_environment.yml`

`source activate MPO624`


If you do all this a lot, conda can use a lot of disk space as it updates packages to the latest version, but leaves old versions lying around. You might like to use

`conda clean` 


The conda cheat sheet is worth the 1-page of paper to print it on, perhaps. 
