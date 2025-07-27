# Digital Dinosaur Museum

This is a digital museum of dinosaurs built with Quarto and GitHub Pages.

## 🚀 How to view the site

Install [Quarto](https://quarto.org/) and run:

```bash
quarto preview
```

Or publish directly to GitHub Pages:

```bash
quarto publish gh-pages
```

Quarto 
* Install quarto (GUI installer)

VS Code Setup 
* VS Code 
    * Install R Extension 
    * Install quarto extension 
    * Install Jupyter extension 

Python setup 
* Install miniconda 
* Create a conda environment 
* Ensure that VS Code uses your conda environment 

R Setup 
* Install R 
* Install xquartz (via brew)
* install.packages("renv")
* In the project directory, run renv::init()
* install.packages("languageserver") 




renv: Project Environments for R

Welcome to renv! It looks like this is your first time using renv.
This is a one-time message, briefly describing some of renv's functionality.

renv will write to files within the active project folder, including:

  - A folder 'renv' in the project directory, and
  - A lockfile called 'renv.lock' in the project directory.

In particular, projects using renv will normally use a private, per-project
R library, in which new packages will be installed. This project library is
isolated from other R libraries on your system.

In addition, renv will update files within your project directory, including:

  - .gitignore
  - .Rbuildignore
  - .Rprofile

Finally, renv maintains a local cache of data on the filesystem, located at:

  - "~/Library/Caches/org.R-project.R/R/renv"

This path can be customized: please see the documentation in `?renv::paths`.

Please read the introduction vignette with `vignette("renv")` for more information.
You can browse the package documentation online at https://rstudio.github.io/renv/.
Do you want to proceed? [y/N]: 
