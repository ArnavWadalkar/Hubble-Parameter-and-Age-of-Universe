# Estimating the Hubble Parameter and Age of the Universe Using Type Ia Supernovae

This project analyzes the Pantheon+SH0ES Type Ia supernova dataset to estimate the Hubble constant \( H_0 \) and the age of the Universe \( t_0 \) within the ΛCDM cosmological model. It implements data visualization, curve fitting, and numerical integration techniques using Python.

---

## Objectives

- Construct the Hubble diagram using redshift \( z \) and distance modulus.
- Fit theoretical models (ΛCDM) to the data to extract the Hubbke constant.
- Use the fitted Hubble constant to numerically compute the age of the Universe.

---

## Background

Type Ia supernovae serve as **standard candles** in cosmology. By comparing observed magnitudes with redshifts, we reconstruct the universe’s expansion history and constrain cosmological parameters.

Key concepts:
- Luminosity Distance 
- Distance Modulus
- Hubble’s Law and ΛCDM dynamics

---

## Tools

- `NumPy`, `SciPy`, `Matplotlib`, `Pandas`
- Curve fitting (`scipy.optimize.curve_fit`)
- Numerical integration (`scipy.integrate.quad`)

---

## Repository Structure

- Pantheon+SH0ES.dat # Supernova data file
- Hubble_Fit.ipynb # Main analysis notebook
- plots/ # Hubble diagram and fitted curves
- README.md # Project overview



---

##  Results

- Estimated Hubble constant:  H_0 =  72.97 ± 0.26 km/s/Mpc  
- Estimated age of the universe: t_0 =  12.37 billion years  
- Comparison with Planck (CMB) and SH0ES (local) values shown in final plots.

---

## References

- Riess et al., Pantheon+SH0ES Compilation, 2022  
- David Tong, Statistical Physics & Cosmology
- S. Weinberg, Cosmology  

---

> Author: Arnav Wadalkar | BSc Physics | NIT Rourkela
> 
> This project was completed as part of the Indian Space Academy, Department of Space Education Summer Internship 2025.



