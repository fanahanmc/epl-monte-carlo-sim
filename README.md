# ACM40960 Projects in Maths Modelling - UCD Summer Term 2021

# Monte Carlo Simulation of Fixtures and Betting Systems for the English Premier League
***Created by Fanahan McSweeney (Student Number: 20203868) ***

## Overview

The main aim of this project is to model the dynamics of the English Premier League and simulate multiple seasons of fixtures based on this model, as well as simulating and evaluating the profitability of different forms of betting systems that could be employed by bookmakers during the Premier League season.

<p align="center"><img width=50.0% src="https://github.com/ACM40960/project-fanahanmc/blob/main/Images/pointsprogression.gif"></p>

The project has been completed within a Jupyter Notebook using the Python programming language. These notebooks allow users to seamlessly blend multiple blocks of code and text within a single easy to navigate document. You can run these notebooks using an appropriate IDE/UI, such as *Jupyter Notebook* or (preferably) *JupyterLab*.

The main project notebook included in this repository (***ACM40960_Project_20203868.ipynb***) has already been executed in full, with all relevant plots, figures and results already visible. Therefore, the fully executed file can be viewed by clicking on the file name directly on GitHub. Alternatively, if you would like to access a copy of the notebook and execute it yourself, then proceed to the **Getting Started** section below.

## Getting Started

If you haven't used Jupyter Notebooks before, then first download and install *Anaconda*, the latest version of which [can be downloaded from here](https://www.anaconda.com/products/individual).

After completing the installation, open *Anaconda-Navigator* and select *Launch* on the *JupyterLab* pane (highligthed in the image below).

<p align="center"><img width=80.0% src="https://github.com/ACM40960/project-fanahanmc/blob/main/Images/AnacondaNavImg.png"></p>

Next, you can clone this GitHub repository onto your local machine. On GitHub, navigate to the repository (you should already be here if you're reading this README file...), select the green *Code* button, and then select the clipboard button beside the link to copy the repo link (highligthed in the image below).

<p align="center"><img width=80.0% src="https://github.com/ACM40960/project-fanahanmc/blob/main/Images/GithubRepo.png"></p>

Then open a terminal window on your local machine and navigate to the location where you want to save the repository. Then type *git clone* and paste the URL copied earlier, and enter the command.
```bash
git clone PASTE-REPOSITORY-URL-HERE
```
Finally, return to the *JupyterLab* window launched previously, click on the folder icon in the top left corner of the window, and navigate to the newly created project folder. Then double-click on the *ACM40960_Project_20203868.ipynb* file located in this folder to open the Jupyter Notebook (highlighted in the folder navigation pane in the image below).

<p align="center"><img width=40.0% src="https://github.com/ACM40960/project-fanahanmc/blob/main/Images/JupyterLabFolderTree.png"></p>

## Navigating the Jupyter Notebook

### Executing code cells

Now that you have opened the Jupyter Notebook for this project, you can proceed down through the notebook executing each code block sequentially. As some of the code blocks have a relatively long execution time, I recommend executing the blocks one-by-one, rather than immediately executing the entire notebook. 

***Note: Failure to execute the code blocks in chronological order may result in errors or incorrect results***. 

To execute a code block, ensure it is selected by clicking on the space on the left hand side of the block (A narrow blue bar will be displayed next to the block when it is selected) and press ```Shift + Return``` to execute. A useful reference detailing many of the most commonly used shorcuts for navigating Jupyter Notebooks can be found [here](https://towardsdatascience.com/jypyter-notebook-shortcuts-bf0101a98330)

### Installing external packages

The notebook also utilises a number of functions from one external package (***mord***) that needs to be installed before these functions can be used. You can install this package from a terminal window using the following command:
```bash
pip install mord
```
Alternatively, you can execute this command in a code block within the notebook itself (the command is currently included in the first code block of the notebook).

### Long-running code cells

Also note that some of the code cells in this notebook take a relatively long time to execute. In each case these cells will be preceded with a red warning message, similar to below.
```diff
-WARNING! Running the following cell may take a very long time (several hours)...
-Do not execute if you are not prepared to wait!!!
```
Only run these cells in their current configuration if you are prepared to wait the long execution time. If not, but you would still like to test the functionality of the code in the cell, then follow the guidance of the accompanying message written below the warning (also written in red text) which will suggest a modification that can be made to the cell to reduce execution time (e.g. run code for a reduced number of iterations).

### Collapsible headings (optional step)

As the Jupyter Notebook for this project is relatively long, I have divided it into several sections and sub-sections, each identified with an appropriate heading. A number of different packages are available that can be used to collapse each of these individual sections making the the notebook easier to read and to navigate. The *aquirdturtle_collapsible_headings* package can be installed to implement this functionality, allowing individual sections to be collapsed by clicking on their associated heading. If you would like to add this functionality to *JupyterLab*, run the following command from a terminal window. 

```bash
pip install aquirdturtle_collapsible_headings
```
