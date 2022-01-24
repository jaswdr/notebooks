# Notebooks
> Personal Jupyter notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jaswdr/notebooks/master)

### Getting started

The easier way to start is using the [jaschweder/jupyter](https://github.com/jaswdr/docker-jupyter) Docker image that contains all required dependencies.

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

### License

See [License](LICENSE) file.
