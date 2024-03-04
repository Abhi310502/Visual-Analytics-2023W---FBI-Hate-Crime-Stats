[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/cDZvQwRB)
# Visual Analytics Lab Project
Submission template for the Visual Analytics lab project at the Johannes Kepler University Linz.

**Explanation:**
This `README.md` needs to be updated and pushed to GitHub.
Change/extend the corresponding sections by replacing the [TODO] markers.

For a detailed project spezification look up the [Visual Analytics Moodel page](https://moodle.jku.at/jku/course/view.php?id=25624).

**Tip:** Make yourself familiar with [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

## General Information

### Group Members

| Student ID      | First Name   | Last Name      | E-Mail                   | Workload [%]  |
| ----------------|--------------|----------------|--------------------------|---------------|
| K12137014       | Abhirup      | Mitra          |abhiruponline@gmail.com   |       25      |
| K12333228       | Alexandre    | Agostinho      |escudier@gmail.com        |       25      |
| K12207579       | Michal       | Jeznach        |jeznachmichal1@gmail.com  |       25      |
| K11722874       | Senay        | Mustafa        |senaim98@gmail.com        |       25      |

### Dataset

* What is the dataset about?
* Where did you get this dataset from (i.e., source of the dataset)?
* How big is the dataset?

**Description:**
The datasets are about the hate crime statistics across the United States in the years 2013 and 2019. The crimes are classified under various parameters. There is state-by-state comparison, various motivations for the hate crimes (inlcuding but not limited to race, religion and gender identity) and the time of year when the crimes occurred.


## General Submission Information

* Make sure that you pushed your GitHub repository and not just committed it locally.
* Sending us an email with the code is not necessary.
* Please update the *environment.yml* file if you need additional libraries, otherwise the code is not executeable.
* Save your executed submission notebooks as HTML and add them to your repository.  
  * Select 'File' -> 'Save and Export Notebook As...' -> 'HTML'
* Upload the exported HTML file on Moodle, if it is required for the submission.

## Usage

### Locally
Checkout this repo and change into the folder:

```shell
git clone https://github.com/jku-icg-classroom/va-project-2023-<GROUP_NAME>.git
cd va-project-2023-<GROUP_NAME>
```

Load the conda environment from the `environment.yml` file, if you haven't already in previous assignments:

```sh
conda env create -f environment.yml
```

Activate the loaded conda environment:

```sh
conda activate python-tutorial
```

Install Jupyter Lab extension to use *ipywidgets* in JupyterLab:

```sh
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

Launch Jupyter :

```shell
jupyter lab
```

Jupyter should open a new tab with url http://localhost:8888/ and display the tutorial files.



