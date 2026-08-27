# IMT2113 — Fourier Analysis

This repository contains the final project developed for **IMT2113 — Fourier Analysis**, an elective course in the Mathematical Engineering program at **Pontificia Universidad Católica de Chile (PUC)**.

The course introduces fundamental concepts of **Fourier analysis** and their applications to engineering problems. The final project focuses on the application of the **Radon transform** to seismic imaging and noise reduction.

## Course

**Course:** IMT2113 — Fourier Analysis
**University:** Pontificia Universidad Católica de Chile
**Semester:** Second Semester, 2025
**Program:** Mathematical Engineering

The course focuses primarily on the mathematical foundations of Fourier analysis, including Fourier series, Fourier transforms, and their applications to engineering and signal processing.

## Project — Seismic Image Denoising Using the Radon Transform

Seismic images are an important tool for understanding the subsurface structure of the Earth. They are widely used in applications such as petroleum and groundwater exploration, geological characterization, and the detection of faults and other subsurface discontinuities.

However, seismic data can be affected by **instrumental errors, environmental noise, and unwanted reflections**, resulting in distorted or low-quality images that make subsequent analysis more difficult.

This project explores the use of the **Radon transform** as a tool for identifying and isolating structured patterns in seismic data. Originally introduced by Johann Radon in the early twentieth century, the Radon transform is best known for its role in tomographic image reconstruction, but it also has important applications in seismic data processing and noise reduction.

The central idea is to transform seismic data into a domain where coherent wave propagation patterns become easier to identify and separate from unwanted components. The project then studies the inverse problem and investigates how the Radon transform can be computed and inverted using numerical methods.

## Objectives

The main objectives of the project are:

* Understand key concepts in seismic imaging, including **Normal Moveout (NMO) correction**, **Common Midpoint (CMP) gathers**, and **multiple reflections**.
* Understand the purpose of the **Radon transform** and explain why an inverse transformation is required.
* Derive and implement a **least-squares approach** for computing the Radon transform.
* Study the behavior of the Radon transform through **synthetic simulations**.
* Analyze the potential of the Radon domain for separating coherent seismic signals from unwanted reflections and noise.

## Repository Structure

```text
.
├── Proyecto_Fourier-2.pdf
├── Proyecto_Fourier_Presentación-3.pdf
├── graficos.ipynb
└── README.md
```

### Files

* **`Proyecto_Fourier-2.pdf`** — Final project report containing the mathematical development, methodology, experiments, and results.
* **`Proyecto_Fourier_Presentación-3.pdf`** — Presentation summarizing the project and its main results.
* **`graficos.ipynb`** — Jupyter Notebook containing the code used to generate the project's simulations, figures, and visualizations.
* **`README.md`** — Repository documentation.

## Authors

**Diego Pérez**
Pontificia Universidad Católica de Chile
Mathematical Engineering
