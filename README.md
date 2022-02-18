# Conference analysis

Notebook repository to demonstrate how to use [Gismo](https://gismo.readthedocs.io/) to analyze the dynamics of conferences.

Each directory is dedicated to a venue. It typically contains:

* Conference specific datasets (typically members of PC committee), usually in json format (possibly compressed)
* A Jupyter Notebook for pre-processing data (typically executed once, can take about an hour if you have no local copy of the DBLP database).
* A Jupyter Notebook for studying the conference.
