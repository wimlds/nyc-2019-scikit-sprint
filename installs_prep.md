# Software Requirements for Sprint

Q:  what version of Anaconda?

Installing Software and Setting up Virtual Environment
have Python installed via Anaconda. (Anaconda includes Jupyter Notebook)


## Install Python via Anaconda
Install [Anaconda](https://docs.anaconda.com/anaconda/install/)
- [Mac](https://docs.anaconda.com/anaconda/install/mac-os/)
- [Linux](https://docs.anaconda.com/anaconda/install/linux/)

## Jupyter Notebook
Jupyter Notebook is included in the Anaconda installation.  Review Jupyter Notebook commands.

## Install Git
- [Mac: git](https://www.atlassian.com/git/tutorials/install-git#mac-os-x)
- [Linux git](https://www.atlassian.com/git/tutorials/install-git#linux)
  
- Confirm Git is installed by typing `git --version` on your terminal

## Sign up for a GitHub Account
- [github.com](https://github.com/)
- Save your user ID and password somewhere you can easily find it

## Join Gitter
Join gitter using your GitHub ID:  gitter.im/scikit-learn/wimlds
  
## Choose a Graphical Editor
- Try Visual Studio Code
	* [Visual Studio Code](https://visualstudio.microsoft.com/downloads/)
- OR one of these other editors
	* [Sublime Text 3](https://www.sublimetext.com/)
 	* [Atom](https://atom.io/)
 	* [Notepad++](https://notepad-plus-plus.org/) (for Windows)
  
 
## Set up Virtual Environment

```bash
# Create virtual environment
conda create --name sklearndev numpy scipy matplotlib pytest sphinx cython ipykernel

# To activate this environment, use
conda activate sklearndev

# To deactivate an active environment, use
conda deactivate
```

---

# Scikit-learn Requirements for Sprint

1) Read thru "Contributing" documentation
- http://scikit-learn.org/stable/developers/contributing.html
- it is approximately 20 pages

2) Review Open Issues
go through some Issues and become familiar with them
https://github.com/scikit-learn/scikit-learn/issues

