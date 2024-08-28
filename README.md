This repository contains a Jupyter notebook for analyzing Open Journal System publication metadata, and whether it has been indexed. 

To run the notebooks you will need a Dimensions API username and password which you should add to a `.env` file that looks like:

```txt
DIMENSIONS_USER=MYUSERNAME
DIMENSIONS_PASSWORD=MYPASSWORD
```

Then you will want to install Poetry and:

```
$ poetry install
$ poetry run jupyter lab
```
