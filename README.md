# ENVE4403 Fluid Transport, Mixing and Dispersion Introduction
Here we will run through some basics of Github, Python and their applications for environmental fluid mechanics. We will use [Jupyter Notebooks](https://jupyter.org/) to run Python code, and the [Github Codespaces](github.com/features/codespaces) platform to host our code and data. Otherwise, you can run the code on your own machine, but you will need to install the required packages and extensions. I can help if you have any issues.

## Git repositories and their function in project and code development
Github is a web-based platform for hosting, sharing and collaborating on software development projects. It provides support for version control, which allows developers to keep track of changes made to their code, and enables teams to work remotely and efficiently on projects together. Github also serves as an online repository to store your project history, giving you easy access to old versions or previous stages of development.

## Using Github Codespaces as a web-based python environment
Github recently released a browser-based virtual machine called "Codespaces" that can be used to initialise python environments from Github repositories that will automatically install the requisite packages and extensions to get up and running quickly. Effectively, it means that you will have a preconfigured python environment that you can access from any computer with a web browser, and you can use it to run your code and analyse your data. This is a great way to get started with python and Github, and it is free for public repositories.

### Steps
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository) this repository to your own account. Once in your own repository (i.e. your-user-name/repository-name), click "<> Code", then "Codespaces", then the three horizontal grey dots (hover will show "Codespace repository configuration"), and finally "+  New with options".

<img src="docs\Codespace 1.png">

Then check that the new Codespace will be on a machine with 2 cores, and click "Create Codespace"

<img src="docs/Codespace 2.png">

After this, your Codespace (which contains all of the data in the repository) will launch as a web implementation of Microsofts VS Code, which is a coding environment that has Python and required packages pre-installed along with the data you need. Each month you have access to 120 core-hours (so if you launch a 2-core machine, you really only get 60 hours), and 15 GB of storage. You will run out of core-hours if you leave your Codespace running for too long, so be sure to exit out of it when you are done. You can then access your Codespace at any time from [here](https://github.com/codespaces), and rename, shut down or delete Codespace environments. I suggest after you are finished with your analysis, download the repository onto your local machine and delete it from Codespaces so you don't run out of space.

## Jupyter Notebooks
Jupyter Notebooks are a web-based interactive computational environment that allows you to run Python code, and display the results of your code in a format that is easy to read and understand. Throughout the semester I will provide you with Jupyter Notebooks that contain the code and instructions for each practical. You can run the code in the notebook, and then edit the code to try different things and see how it affects the results. You can also add your own code to the notebook to extend the analysis, or to try something new. You can also add text to the notebook to explain what you are doing, and to document your analysis. These notebooks are not assessed.

To continue, launch a codespace, and navigate to "Tutorial1_CSVs_&_NCs" and open "Tutorial1_CSVs_&_NCs.ipynb" notebook.
