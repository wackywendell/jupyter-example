# Jupyter in a venv

This repo is an example of making a self-contained jupyter virtualenv, in which jupyter is itself in the venv, as well as the kernel.

## Initial Setup

To set this up, I ran:

```sh
$ mise use uv
$ uv init --no-package
$ uv add jupyterlab
```

Then added a couple things to the related files; see git history.
