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

### From Ipython to Jupyter

### What is Ipython?
* A powerful interactive shell
* Is the kernel of Jupyter
* Support for interactive data visualization and use of GUI

### Ipython kernel
* Save and run user code
* Interact with Ipython shell through sdin/stdout
* Communicate with notebook through ZeroMQ using json format message

### What is Jupyter Notebook?
* Come from IPython notebook
* A open source Web application
* Create and share code with community
* Use for data science

### Interaction with Notebook and kernel
* Notebook server is the core
* Notebook server load and save notebook

### Notebook file format(.ipynb)
* Defined by IPython Notebook(json)
* Can read online data or CSV/XLS file
* Can convert to other format(py,html,pdf,md, etc.)

### NBViewer
* One online viewer for notebook with ipynb format
* Share with URL
* Github intergreted NBViewer
* Convert to Blogs Emails, Wikis, Books easily