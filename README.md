# pdf_parser
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mathieuboudreau/pdf_parser/master)

Script to parse a folder of PDFs for certain keywords. Example in notebook are for open source related keywords.

# Getting started

If you want to quickly try out the script, all you need to do is to click the Binder button above and wait for the environment to load in your web browser. Once ready, upload a (or a few) pdfs, and open the Jupyter notebook that's in the 

For a more stable setup (and to avoid uploading a lot of pdfs), you can do one of two things:

1. If you have Anaconda or Jupyter already installed:
  * Clone this repository to your local computer
  * Install the requirements using `pip install -r requirements.txt`
  * Open a Jupyter notebook session within the repo using `jupyter notebook`
  * Copy the pdfs to your repo folder
  * Run the notebook
2. If you prefer to use a Docker container:
  * Have Docker installed and running on your local computer.
  * Install repo2docker using `pip install jupyter-repo2docker`
  * Run repo2docker using `jupyter-repo2docker pdf_parser`, or replace `pdf_parser` to the path of the repo.
  * After the container is done building, copy the provided link to the running server to your browser.
  * Copy the pdfs to your repo folder
  * Run the notebook
