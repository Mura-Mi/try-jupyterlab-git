# jupyter-lab-git-trial

```shell
docker run --name jupyter-lab-git-trial -e POSTGRES_PASSWORD=password -p 5432:5432 -d postgres
```

```shell
poetry install
poetry run jupyter notebook
```
