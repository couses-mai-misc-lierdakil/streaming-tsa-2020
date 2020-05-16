Рассчитано на работу с Python 3.7. Используемые библиотеки:

- jupyterlab
- numpy
- plotly
- hyperloglog
- pyprobables
- statsmodels
- ipywidgets

Для поддержки plotly в jupyter lab необходимо расширение jupyterlab-plotly (устанавливается командой `jupyter labextension install jupyterlab-plotly`)

При использовании pipenv, установка и запуск окружения сводится к:

```
pipenv install
pipenv run jupyter labextension install jupyterlab-plotly
pipenv run jupyter lab
```

Можно использовать образ Docker:

```
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "$PWD":/home/jovyan/work lierdakil/tsa-notebook:latest
```
(осторожно, трафик)
