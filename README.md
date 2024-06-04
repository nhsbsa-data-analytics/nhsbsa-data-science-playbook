# DALL Playbook

This repository contains the framework for writing and deploying the DALL Playbook. The playbook is used to give detailed guidance on the typical workflow for DALL initiatives.

The playbook can be found [here](https://nhsbsa-data-analytics.github.io/dall-playbook/).

## Requirements

To run the document, open `index.qmd`, within the root folder, using either Rstudio or VS Code and click 'Compile' or 'Preview' respectively. For Rstudio usage, you must also load the `dall-playbook.Rproj` project to be able to compile the document. 

For Rstudio usage, you simply require the latest version of Rstudio. For VS Code, you must install the Quarto extension and install the Quarto CLI. When running Quarto for the first time, you will be prompted with instructions on how to install this. **Please note this is not currently possible with the Azure Virtual Desktop (AVD)**.

## Folder Structure

The playbook is structured into a series of sections and sub-sections. The home page first greets the users with the tabs to navigate to the four main sections. Then, once the user has clicked on a section, they are then provided with additional tabs to navigate to a page about each sub-section. The following folder structure highlights how this is setup up from a coding perspective. Each section and sub-section is populated by a `.qmd` file and supporting `.jpeg` file to provide the image for each tab.

```
dall-playbook
├───guidance ............................# Folder containing all of the playbook content within a series of sections and sub-sections
│   ├───*.{section-name} ................# Series of folders with identical structure that contain the content for each section 
│   │   ├───{section-name}-steps ........# Folder containing the .qmd files of each sub-section content and .jpeg images for the tab navigation
|   |       ├───*.{sub-section-name}.qmd
|   |       ├───*.{sub-section-name}.jpeg
|   |   ├───index.qmd ...................# The .qmd file for each section
|   |   ├───{section-name}.jpeg .........# The .jpeg image for the tab navigation of each section
|   ├───_metadata.yml ...................# Additional settings applied to the quarto document
├───static ..............................# A folder containing the the BSA visual settings for the quarto document
├───_quarto.yml .........................# A file that controls the page layout and settings for the quarto document
├───about.qmd ...........................# An additional .qmd that populates the 'About' button within the document
├───dall-playbook.Rproj .................# The R Project file
├───index.qmd ...........................# The primary .qmd file, used to compile the entire document.
├───README.md ...........................# The README file
├───styles.css ..........................# A file containing some additional settings for the quarto document
```
