# Notebooks
> Personal Jupyter notebooks

### Getting started

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
