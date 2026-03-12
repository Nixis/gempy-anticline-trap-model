# 3D Faulted Anticlinal Reservoir Model in GemPy

## Project Overview

This project demonstrates a simple geological modelling workflow using **GemPy**, an open-source Python library for implicit 3D geological modelling.

A synthetic subsurface model is created representing a **shale–sand–shale stratigraphic sequence** folded into a **gentle anticline** and affected by a **normal fault**. The sandstone layer acts as a simplified reservoir interval sealed by shale above and below.

After building the initial model, **two new wells with formation top picks** are introduced to simulate how new subsurface data can update a geological interpretation.

The project concludes with a **gross rock volume (GRV) estimation** for the sandstone reservoir body.

---

## Geological Concept

The synthetic model represents:

- **Upper shale** – top seal  
- **Middle sandstone** – reservoir unit  
- **Lower shale** – base seal  

Structural elements:

- Broad **anticline**
- **Normal fault** offsetting the stratigraphy

This simplified geometry mimics a **faulted anticlinal trap**, a common hydrocarbon trap type.

---

## Project Workflow

1. Build initial geological model using synthetic interface and orientation data  
2. Generate 3D structural model in **GemPy**  
3. Introduce two synthetic wells with formation tops  
4. Update the geological model to honour new well control  
5. Estimate **gross rock volume (GRV)** of the sandstone reservoir  

---

## Repository Structure

```
gempy-anticline-trap-model
│
├── data
│   ├── interface_points.csv
│   ├── orientations.csv
│   └── wells.csv
│
├── notebooks
│   └── 01_build_initial_model.ipynb
│
├── figures
│
├── results
│
└── requirements.txt
```

---

## Tools Used

- Python
- GemPy
- Pandas
- NumPy
- Matplotlib
- PyVista

---

## Author

**Nixis Carrero Candelas**

Geoscientist | Data Science & Subsurface Modelling