# sklearn
DSD Meetup 4: SKLearn using Python

````
jupyter notebook --generate-config
vi ~/.jupyter/jupyter_notebook_config.py

c = get_config()
c.NotebookApp.ip = '*'
c.NotebookApp.open_browser = False
c.NotebookApp.port = 8000

jupyter-notebook --no-browser --port=8000
````