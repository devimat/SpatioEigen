# SpatioEigen

## Overview

This repository contains implementations of Non-Equilibrium Green's Function (NEGF) methods for various device geometries, supporting both 2D and 3D structures. It also includes tools for visualizing the results and managing code navigation efficiently.

---

## Navigation

### TC

- `TC.ipynb`: Contains links to all `.ipynb` files along with their descriptions for easier navigation.

---

## NEGF\_Coupled

- **Description:**
  - Implements a coupled spatio-eigen basis, which can be easily modified for different device geometries.

---

## 2DNEGF

- **Description:**
  - Contains the implementation of NEGF for 2D structures, supporting both:
    - Tight-binding basis (`NEGF_TB`)
    - Spatio-eigen basis (`NEGF_SE`)

---

## Coupled

- **Description:**
  - Implements the decoupled spatio-eigen method for a 3D structure. This section consists of two key scripts:

### 1. `H_circle.ipynb`

- **Functionality:**
  - Generates the Hamiltonian for the top and bottom contacts.
  - Applies unitary transformations corresponding to the contacts and saves them as CSV files.
  - Loads the current operator from `NEGF.ipynb` (in EigenBasis) and converts it to the tight-binding basis to obtain the spatial current profile.

### 2. `NEGF.ipynb`

- **Functionality:**
  - A more generic code that takes the Hamiltonian corresponding to the left and right contacts as CSV files.
  - Uses an optimized inverse calculation function to compute the current operator.

---

## FigCollect

- **Description:**
  - Contains a collection of code for generating regular and color plots.

---

## Usage

1. Clone the repository:

```
$ git clone <repository_url>
```

2. Navigate to the desired directory:

```
$ cd <directory_name>
```

3. Launch Jupyter Notebook to run the `.ipynb` files:

```
$ jupyter notebook
```

---

## Requirements

- Python 3.x
- Jupyter Notebook
- NumPy,Cupy, SciPy, and Matplotlib



---

## Contributing

---

## License
