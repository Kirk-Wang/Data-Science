# 也许……

## Anaconda
[https://www.anaconda.com/distribution/#download-section](https://www.anaconda.com/distribution/#download-section)

### Conda: Package and Environment Management
* Install Packages
* Update Packages
* Sandbox: Conda environment

### Conda: Environment Mgmt
* Create a new environment
  ```sh
  conda create --name python34 python=3.4
  ```
* Activate environment
  ```sh
  activate python34 # for Windows
  source activate python34 # for Linux & Mac
  ```
* Exit environment
  ```sh
  deactivate python34 # for Windows
  source deactivate python34 # for Linux & Mac
  ```
* Delete environment
  ```sh
  conda remove --name python34 --all
  ```

### Conda Package Mgmt
* Like Python pip
* Install Python package
  ```sh
  conda install numpy
  ```
* Check installed Python package
  ```sh
  conda list
  conda list -n python34 #check particular python env
  ```
* Delete Python package
  ```
  conda remove -n python34 numpy
  ```

### Data Science IDE vs Developer IDE
Data Science IDE | Developer IDE
-|-
Data-centric|Code-centric
Interactivity,visualizations,variable explorer|Classes,debugging,profiling
Less code complexity, scripts|More complex code,programs
Integration with data sources|Integration with git,build tools,compilers
Models and narratives storytelling|Tools and libraries functionality
RStudio,Spyder,Jupyter,JupyterLab|PyCharm,Visual Studio,Wing IDE,Sublime text
