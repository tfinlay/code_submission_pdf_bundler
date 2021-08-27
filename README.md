# Code Submission PDF Bundler

A handy python script for building a single PDF containing:

* Student Name
* Student ID
* Python source code & file names (formatted, syntax highlighted, in text form)
* Plagiarism Declaration form

Sample output can be found [here](sample/sample_output.pdf).

## Usage

NB: Before running this command, you'll need a PDF of the filled-in plagiarism declaration form. This will be added to the end of bundled PDF.

1. [Download a copy of this repo](https://github.com/tfinlay/code_submission_pdf_bundler/archive/refs/heads/main.zip) and unzip it somewhere.
2. Open a terminal/command line in the unzipped repo.
3. Install dependencies by running `pip install -r requirements.txt`.
4. Run the application by running `python bundler.py`.
5. Follow the steps.
6. Viola! `out.pdf` is your fully bundled PDF ready to hand in.

NB: This assumes that `pip` and `python` refers to Python 3. If your system uses `pip3` and `python3` to refer to Python 3, please adjust accordingly.
