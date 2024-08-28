This repository contains a Jupyter notebook for analyzing Open Journal System publication metadata, and whether it has been indexed. The source dataset is:

> Details of publications using software by the Public Knowledge Project
Khanna, Saurabh; Raoni, Jonas; Smecher, Alec; Alperin, Juan Pablo; Ball, Jon; Willinsky, John, 2024, "Details of publications using software by the Public Knowledge Project", https://doi.org/10.7910/DVN/OCZNVY, Harvard Dataverse, V4, UNF:6:gZEARPVQ7u+ewxiX1pWVBQ==

To run the notebooks you will need a Dimensions API username and password which you should add to a `.env` file that looks like:

```txt
DIMENSIONS_USER=MYUSERNAME
DIMENSIONS_PASSWORD=MYPASSWORD
```

Then you will want to [install Poetry](https://python-poetry.org/docs/) and:

```
$ poetry install
$ poetry run jupyter lab
```
