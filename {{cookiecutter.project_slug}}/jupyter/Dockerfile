FROM jupyter/base-notebook

COPY ./binder/environment.yml environment.yml
RUN conda env update -n base --file environment.yml
