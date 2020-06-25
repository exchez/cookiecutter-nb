[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/master) [![NBViewer](https://raw.githubusercontent.com/jupyter/design/bfbff5d7eec8bd8be413deffecff0f4de29fd5cf/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/blob/master/{{ cookiecutter.notebook_name }}.ipynb)

# {{ cookiecutter.project_name }}

### Motivation
1.
2.
3.

### Run with Docker on your machine (must have Docker installed)
1. `git clone https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.git`
2. `cd {{ cookiecutter.project_slug }}`
3. `docker-compose up`
4. make sure to run `docker-compose down` when you're done

### Run on Binder
1. Click the link to binder above
2. Get up and grab a coffee (optional). It may take ~15 minutes to build the image if it's not cached.
3. Replace "tree" at the end of the url with "lab" to run in Jupyter Lab (optional). Though I actually think it looks nicer in a notebook.
