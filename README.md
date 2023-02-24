# ENVE4403 Introduction
Here we will run through some basics of Github, python and their applications for environmental fluid mechanics

## Git repositories and their function in project and code development


## Using Github Codespaces as a web-based python environment
Github recently released a browser-based virtual machine that can be used to initialise python environments from Github repositories that will automatically install the requisite packages and extensions to get up and running quickly. We will use it in this class to 

### Steps
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository) this repository to your own account. Once in your own repository (i.e. your-user-name/repository-name), click "<> Code", then "Codespaces", then the three horizontal grey dots (hover will show "Codespace repository configuration"), and finally "+  New with options".

<img src="/docs/Codespace 1.png">

Then check that the new Codespace will be on a machine with 2 cores, and click "Create Codespace"

<img src="/docs/Codespace 2.png">

After this, your Codespace (which contains all of the data in the repository) will launch as a web implementation of Microsofts VS Code, which is a coding environment that has Python and required packages pre-installed along with the data you need. Each month you have access to 150 core-hours (so if you launch a 2-core machine, you really only get 75 hours), and 15 GB of storage. I suggest after you are finished with your analysis, download the repository onto your local machine and delete it from Codespaces so you don't run out of space.

You can then access your Codespace at any time from [here](https://github.com/codespaces), and rename, shut down or delete Codespace environments.
