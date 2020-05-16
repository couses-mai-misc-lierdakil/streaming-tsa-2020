FROM jupyter/scipy-notebook:latest
# Install in the default python3 environment
RUN pip install plotly hyperloglog pyprobables && jupyter labextension install jupyterlab-plotly @jupyter-widgets/jupyterlab-manager plotlywidget
