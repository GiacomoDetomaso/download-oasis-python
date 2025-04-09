# download-oasis-python
This project aims to provide a Python API to download the OASIS-3 and OASIS-4 dataset from NITRC.
- At the moment you are able to download the FreeSurfer assessments of T1w MRIs


## Content

- Notebook dir: contains example that describes how to use the downloader classes in various situations
- Modules dir: contains the classes to download OASIS data (they must implement the interface inside the file modules/data_manager_abstract.py)
- Data dir: contains the csv files with the id of the experiment to download

## Issues in download
Sometimes it looks like the server does not recognize your NITRC credentials. I personally solved this problem multiple times by chaging NITRC account password.
