# SICSS Aachen-Graz 2022 - Python Crash Course

Welcome to the Python crash course of the Summer Institute in Computational Social Science 2022!

In the first week (June 27 to July 1), you will learn the basics of programming in Python: data types, data structures, branching, loops, and functions. In [`./tutorials`](./tutorials/), you'll find interactive notebooks explaining these concepts (for each day there is one notebook). They include links to video tutorials for those of you who prefer spoken explanations over reading. To practice the newly learned skills, check out the examples in [`./exercises`](./exercises/)! (Again one notebook for each day).  
The table bellow gives you an overview of the weeks content and the links to the tutorials and exercises:

| Day | Tutorial | Exercise |
| ---      | ---      |  --- |
| 27.06    | [Print, Comments, Strings and Numbers](./tutorials/tut01_print_comments_strings_numbers.ipynb)   |  [Exercise 1](./exercises/ex01_print_comments_strings_numbers.ipynb) |     
| 28.06    | [Datastructures and Loops Part 1](./tutorials/tut02_datastructures_loops.ipynb)   |  [Exercise 2](./exercises/ex02_datastructures_loops.ipynb) |  
| 29.06    | [Booleans, Conditions and Loops Part 2](./tutorials/tut03_booleans_branching_loops.ipynb)   |  [Exercise 3](./exercises/ex03_booleans_branching_loops.ipynb) | 
| 30.06    | [Functions](./tutorials/tut04_functions.ipynb)   |  [Exercise 4](./exercises/ex04_functions.ipynb) | 
| 01.07    | [File I/O](./tutorials/tut05_file_IO.ipynb)   |  [Exercise 5_1](./exercises/ex05_file_IO.ipynb) and [Exercise 5_2](./exercises/ex05_reading_error_messages.ipynb) | 

The second week (July 04 to July 08) covers working with tabular data, plotting, basic statistics, and networks. For those topics, we'll skip the explanatory notebooks and go straight for practical tasks (again found in [`./exercises`](./exercises/)). But don't worry, the task descriptions contain links to helpful videos and documentation pages :)  
The table bellow gives you an overview of the weeks content and the links to the exercises:
| Day | Tutorial | Exercise |
| ---      | ---      |  --- |
| 04.07    | `pandas` Part 1   |  [Exercise 6](.exercises/ex06_pandas_a.ipynb) |     
| 05.07    | `pandas` Part 2   |  [Exercise 7](./exercises/ex07_pandas_b.ipynb) |  
| 06.07    | Plotting with `matplotlib`   |  [Exercise 8](./exercises/ex08_plotting.ipynb) | 
| 07.07    | Basic Statistics with `scipy` and `statsmodels`   |  [Exercise 9](./exercises/ex09_scipy_statsmodels.ipynb) | 
| 08.07    | Networks with `networkx`   |  [Exercise 10](./exercises/ex10_networkx.ipynb) | 


## Setup
There are many different environments in which you can work with Python. To simplify the setup, we encourage you to use Google Colab: https://colab.research.google.com/. It provides a notebook environment with all the required packages already installed. To get the content of this repository into Colab, download it (click the green "Code" button at the top right and select "Download ZIP"), extract the content, and upload it to your Google Drive. You should then be able to open the notebook files in Colab.

_**Alternatively**_, you can follow the steps to set up a local Python environment:

### Install Python locally

Do this only if you're not using Goole Colab!!

- Download the latest installer for your operating system here: https://www.python.org/downloads/  
    If you use Linux, execute the following commands instead (and skip the steps below)
    ```
    sudo apt-get update
    sudo apt-get install python3.10
    ```
    - Open the downloaded Python installer. **Make sure to check the "Add Python 3.10 to PATH" mark!**
    - Click "Install Now". This may take a while.
    - To finish the installation click "Close".
- To check if you successfully installed Python open up a terminal window:
    - Windows: press the Windows key <kbd>![](http://i.stack.imgur.com/B8Zit.png)</kbd>, enter `cmd`, and hit enter.
    - MacOSX: press <kbd>&#8984;</kbd> and enter `Terminal`
    - Linux: press the "Super key" and enter `Terminal`
- Type `python --version` and hit enter. You should see something like `Python 3.10.4`.

### Install a notebook environment
There are multiple notebook environments available. Below are two of the most commonly used:
#### VS Code
[Visual Studio Code](https://code.visualstudio.com/) is a general-purpose text editor. It [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) provides in-depth support for developing Python programs, including a notebook environment. For that to work, a _kernel_ is required. To install, open a terminal and execute

`python -m pip install ipykernel`

Click [here](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) for detailed instructions on working with notebooks in VS Code.

#### JupyterLab
[JupyterLab](https://jupyter.org/install) is an interactive notebook environment. You can open the `.ipynb` files provided for tutorials and exercises as well as other text-based files.
To install, enter 

`python -m pip install jupyterlab` 

in the terminal.
To run JupyterLab, execute 

`python -m jupyter lab`. 

A browser window should pop up with JupyterLab loading. Don't close your Command Prompt while working in jupyter lab. Click [here](https://jupyterlab.readthedocs.io/en/latest/user/interface.html) for a documentation of the JupyterLab Interface and how to use it

#### Which one should i choose?
JupyterLab is the more simple and lightweight option. VS Code provides much better autocompletion and helps finding mistakes early - it might feel overwhelming at first, but if you plan on programming more, it'll be worth your effort!
