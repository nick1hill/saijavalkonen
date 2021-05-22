# Suomen teknisen viestinnän yhdistys demonstration repository

This repository is intended to demonstrate a solution based on GitHub for editing DITA files and generating PDF files using GitHub.

The DITA source files are taken from https://github.com/dita-ot/docs repository, which are licensed under the terms of its Apache License 2.0.

This repo also has an Apache License 2.0.

The GitHub Action file uses a Docker image of the Dita Open Toolkit to create a PDF from the source files, without any customization of the base PDF plugin.

## Contents of this repo

README.md - this file
License - Apache License 2.0 for this repo
sequence.ditamap - ditamap used as input for building the documentation.
   - concepts - dita files used by the ditamap
   - image - images used in the document
   - tasks - dita files used by the ditamap
   - .github
     - workflows
       - blank.yml - YAML file that provides instructions for the GitHub Action used to build the PDF
