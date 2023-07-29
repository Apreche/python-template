# Python Template

This is my template for new [Python](https://www.python.org/) projects in [VSCode](https://code.visualstudio.com/).
[VSCode devcontainers](https://code.visualstudio.com/docs/devcontainers/containers) are used for local development.
[Poetry](https://python-poetry.org/) is used for Python dependency management.

## Instructions

1. Install [Docker](https://www.docker.com/products/docker-desktop/)
2. Install VSCode
3. Install the [VSCode Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
4. Copy this directory to the desired location and rename it as appropriate
5. Remove the `.git` directory. Use `git init` to start a new repo
6. Open the directory in VSCode
7. When prompted, choose "Reopen in Container". Alternatively choose `Dev Containers: Rebuild and Reopen in Container` from the command palette
8. If this is a brand new project, a terminal will appear with prompts to initialize Poetry
9. Develop some software!

## Notes

The Python environment will automatically be activated within the VSCode integrated terminal. If for some reason that doesn't work, closing the terminal and opening a new one should fix it.

The [Ruff extension](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff) will automatically lint Python files. Feel free to change this if you don't like it.

The [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) extension is installed, and notebooks will work out of the box. Just make sure to select `.venv/bin/python` as the kernel.