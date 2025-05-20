# Wave Packet Dispersion Simulation

This project demonstrates the simulation of wave packet dispersion using Python and numerical methods. 
It was created as part of the FYS2130 course at the University of Oslo.

## 🧠 Physics Background

A wave packet can be represented as:

```
ψ(x, t) = cos(kx - ωt) * exp(-((x - vt)^2)/(2σ^2))
```

This simulation visualizes how a wave packet evolves over time in both dispersive and non-dispersive media:

- **Non-dispersive:** ω(k) = c * k
- **Dispersive:** ω(k) = k²

In dispersive media, the phase velocity and group velocity differ, causing the wave packet to spread over time.

## 💻 Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## 🔬 What You Will See

- Comparison of wave packet propagation in dispersive vs. non-dispersive media.
- Animated visualization of wave function ψ(x, t).
- Mathematical explanations with graphical output.

## 🚀 How to Run

1. Clone the repository
2. Open the Jupyter Notebook:
   ```
   jupyter notebook innlevering_computational_essay_dispersjon.ipynb
   ```
3. Run all cells

## 📂 Files

- `innlevering_computational_essay_dispersjon.ipynb`: The main simulation and explanation.
- `README.md`: Project description (this file).

## 📌 Notes

This notebook is focused on conceptual understanding and visualization. Normalization of the wave function is not enforced, as the goal is to analyze dispersion behavior.

## 📷 Screenshots

*Consider adding a few PNG plots here in the future for quick preview.*

## 👩‍🔬 Author

Klaudia M. Pawlak  
[GitHub](https://github.com/klaudiapawlak)

---

Feel free to fork or use this notebook for educational purposes.