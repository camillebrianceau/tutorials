# Clinica and ClinicaDL tutorial

This notebook presents both Clinica and ClinicaDL and show through a simple example how they can be used to run a neuroimaging experiment from raw data to machine learning.

## Get started

Step 1: create a virtual environment:

```
$ conda create -n clinica_tuto python=3.11
$ conda activate clinica_tuto
```

Step 2: Install the dependencies:

```
$ pip install clinica
$ pip install clinicadl
$ pip install jupyterlab
```

Set3: Launch the notebook:

```
$ jupyter lab
```

Running the notebook requires to have DVC and ANTs installed on your system.

Installing DVC should be pretty straightforward:

```
$ pip install dvc
```

Installing ANTs is a bit more involved. Some details can be found [here](https://github.com/ANTsX/ANTs/wiki/Compiling-ANTs-on-Linux-and-Mac-OS).
