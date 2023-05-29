# Notebooks
> Personal Jupyter notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jaswdr/notebooks/master)

### Getting started

The easier way to start is using the [jaschweder/jupyter](https://github.com/jaswdr/docker-jupyter) Docker image that contains all required dependencies.
C:\Users\jonat\Documents\GitHub\digits-recognizer-kubeflow\digits_recognizer_notebook.ipynb
**Using Docker**

```bash
#!/bin/bash

docker pull jaschweder/jupyter

docker run \
    -d \
    -p 8888:8888 \
    -v $(PWD):/home/jovyan \
    jaschweder/jupyter
```

Open http://localhost:8888

**Using Jupyter***

```bash
jupyter lab
```

New browser window will automatically open, or the link to open the Jupyter lab will be printed.

### License

See [License](LICENSE) file.
