# MachineLearning - Docker mod for code-server

This mod adds `scikit-learn` and `jupyter` to code-server, to be installed/updated during container start.

Incode-server docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:code-server-machinelearning`. but make sure you are using `linuxserver/mods:code-server-python3` before adding this entry.

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:code-server-python3|linuxserver/mods:code-server-machinelearning`

# Requirements

**You need to install `linuxserver/mods:code-server-python3` before this mod**