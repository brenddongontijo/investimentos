FROM jupyter/scipy-notebook

COPY . /work
WORKDIR /work

RUN pip3 install lxml

CMD jupyter-notebook --allow-root --NotebookApp.token='' --ip=0.0.0.0 --NotebookApp.password=''