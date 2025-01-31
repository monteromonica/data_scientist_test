#### RUN FROM LOCAL

docker run -p 8888:8888 -v "${PWD}":/home/jovyan/work  quay.io/jupyter/scipy-notebook:2024-12-23 

This will download the container from Jupyter Notebook the first time and set up a Jupyter environment accessible at `http://localhost:8888`. You can then start working on your data science projects directly from your browser.