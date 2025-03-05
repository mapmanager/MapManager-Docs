Welcome to the MapMAnager user documentation.

This is intended for end users who want to use the desktop or web based apps.

For users interested in diving deeper, we have three more sets of documentation:

 - MapManagerCore
 - WebMapManager
 - PyMapManager

 ## To edit the documentation locally

    conda create -y -n mapmanager-docs python==3.11
    conda activate mapmanager-docs

    pip install mkdocs mkdocs-material mkdocstrings-python

    mkdocs serve

Now visit http://127.0.0.1:8000/ in your browser

## To push to gh-pages

    mkdocs gh-deploy

Your new documentation will be available at

    https://mapmanager.github.io/MapManager-Docs/