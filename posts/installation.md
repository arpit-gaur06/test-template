---
title: "Getting Started"
description: "Installation, Setup and Examples"
author: "Arpit Gaur, Prince A Patel, Monika Nagliya"
date: "2/24/2025"
---

# Installation

**1. Install Pyvista:**

The only prerequisite for installing PyVista is Python itself. We can use Anaconda or Pip as virtual environment and package manager for Python.

PyVista can be installed by `conda-forge`:
```python
conda install -c conda-forge pyvista
```
or can be installed via `pip` by the following command:
```python
pip install pyvista
```
This will automatically install PyVista along with all the necessary dependencies.

**2. Install `vtk` for 3D Visualization:**

PyVista builds on VTK, so if you're running into issues with installation or if you want to manually install VTK, you can install it separately:
```python
pip install vtk
```

**3. Verify the Installation:**

Once installed, you can verify if everything is set up correctly by opening a Python environment (either a Python shell or a Jupyter notebook) and typing:
```python
import pyvista as pv
print(pv.__version__)
```

**4. Optional: Install `trame` for 3D Visualization:**

We will be going to install `trame` library which is an optional dependency for interactive notebook rendering.
```python
pip install trame-vuetify trame-vtk
```

This will open an interactive 3D plot. You can rotate, zoom, and inspect the mesh.

With that, we're ready to use PyVista!