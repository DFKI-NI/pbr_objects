pbr_objects
===========

[![Actively Maintained](https://img.shields.io/badge/Maintenance%20Level-Actively%20Maintained-green.svg)](https://gist.github.com/cheerfulstoic/d107229326a01ff0f333a1d3476e068d)

This repo contains mesh models for the physical objects used in the
[DFKI PBR group](https://www.dfki.de/en/web/research/research-departments/plan-based-robot-control).

Some of the models are part of the [YCB Object and Model Set](https://www.ycbbenchmarks.com/object-models/).

pre-commit Formatting Checks
----------------------------

This repo has a [pre-commit](https://pre-commit.com/) check that runs in CI.
You can use this locally and set it up to run automatically before you commit
something. To install, use pip:

```bash
pip3 install --user pre-commit
```

To run over all the files in the repo manually:

```bash
pre-commit run -a
```

To run pre-commit automatically before committing in the local repo, install the git hooks:

```bash
pre-commit install
```
