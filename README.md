# RDataPackageTemplate

An R package that can be used as a template for other R Data Packages.

## Preparation

### Install R, RStudio, and Git

### In R, run this command to install the associated packages:

    install.packages(c("devtools"))

### Create a Github account

Create a Github account and (optional) set up ssh keys. 

## Create Github repository

1. Log in to Github.
1. Use + in upper right hand corner and select, "New repository".

 - Name the repository
 - Add a Description
 - Choose Public vs Private (likely Private)
 - Check "Initialize this repository with a README"
 - Set "Add .gitignore: R"
 - Set "Add a license:" to whatever license you want, I typically use GNU General Public License v3.0

1. Click "Create Repository.


## Clone Github repository onto local computer

1. Click green "Clone or download".
1. Click on Copy to Clipboard icon.
1. Open RStudio and, in the upper right, select "New Project"
1. Select "Version Control"
1. Select "Git"
1. Paste into "Repository URL:"
1. Change "Create project as subdirectory of:" to whever you want on your computer.
1. Click "Create Project".
1. Add "*.Rproj" to .gitignore and commit and change.
