# visulize_ansys_rst_result

A small Python project to load and visualize results from ANSYS `.rst` files (simulation result files).

This tool uses [PyVista](https://github.com/pyvista/pyvista) and [ansys-mapdl-reader](https://github.com/pyansys/ansys-mapdl-reader) to extract and plot stress, displacement, or other FEA results from ANSYS simulations.

---

## Features
- Loads ANSYS `.rst` result files
- Plots nodal displacements, von Mises stress, or custom fields
- Press `a` to activate interactive probe mode (click on mesh to get values)
- Press `s` to clear all probe markers

---

## Installation
Clone this repository and install dependencies:

```bash
git clone https://github.com/yourusername/visulize_ansys_rst_result.git
cd visulize_ansys_rst_result
pip install -r requirements.txt
