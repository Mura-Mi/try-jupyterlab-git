# try-jupyterlab-git

A sample repository of jupytelab and/or jupyter notebook + git extension + nbspritout.

## Preparation

Install via poetry.

```shell
poetry install
poetry run jupyter notebook # run notebook
poetry run jupyter lab      # run Jupyter Lab
poetry run nbstripout       # clean ipynb metadata and output
```

Just a sample to manipulate postgresql.

```shell
docker run --name jupyter-lab-git-trial -e POSTGRES_PASSWORD=password -p 5432:5432 -d postgres
```
