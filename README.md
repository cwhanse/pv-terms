# pv-terms
Standard variable names for PV modeling.  See http://hackingmaterials.lbl.gov/pv-terms/

## Building the documentation

To build the documentation locally, you'll need to install the sphinx
requirements.  It's probably a good idea to be working in a virtual
environment, but not strictly necessary. 

    pip install -r requirements.txt

There are a few ways to build the docs.  The first will generate html files in `source/_build/html`:

    make html

The second does the same thing but then copies the files into `docs/` so that they'll get detected by Github Pages:

    make github
