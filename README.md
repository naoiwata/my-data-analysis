# my-data-analysis
my study logs :)

## start

```
$ docker run -it -d --name my-jupyter -p 8888:8888 -v $(pwd):/home/jovyan --restart=always -v ~/.config/gcloud:/home/jovyan/gcloud jupyter/datascience-notebook
$ docker logs my-jupyter
```
