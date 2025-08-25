# Modelling the Safety Zone Around Playground Swings

**Author:** Emilia Zabrzanska  
**Date:** December 2024  

This repository contains the mathematical modelling project *"Safety Zone around Playground Swings"*, originally developed as part of Open University coursework (TMA07). The aim of this project is to determine the minimum safety zone required around a playground swing, ensuring that if a child (or object) falls from the swing, the landing area is sufficient to minimise risk of injury.

---

## 📘 Project Overview

The model predicts the distance a child could travel if released from a swing in motion. This distance is then used to define a minimum safety zone length. The project combines principles of **pendulum motion** and **projectile motion**.

---

## 🎯 Objectives

- Model a playground swing as a pendulum.  
- Use **conservation of energy** to determine velocity at the release point.  
- Apply **projectile motion** equations to calculate landing distance.  
- Compare results with the **British and European Standard BS EN 1176** for playground equipment.  
- Propose revisions to improve realism by considering external factors.

---

## 🧮 Methods

1. **Pendulum Model**  
   - Swing treated as a simple pendulum of length *l*.  
   - Energy conservation applied to find velocity at release angle θ.  

2. **Projectile Motion**  
   - Calculated horizontal and vertical displacement from release point.  
   - Derived formula for maximum landing distance *D*.  
   - Safety zone proposed as **2D × w**, where *w* is swing width.

3. **Validation**  
   - Compared predictions against EN 1176 standard and real manufacturer data.  

---

## 📊 Key Results

- Maximum travel distance occurs when the swing is released at ~39–40°.  
- For swing lengths between **2.0–4.0 m**, predicted maximum landing distances (one side) ranged from **5.08 m to 9.87 m**.  
- Safety zone lengths therefore ranged from **10.2 m to 19.8 m**.  
- Model predictions were **longer than real-world standards**, as air resistance, friction, and child dimensions were not considered.

---

## ⚖️ Limitations & Revisions

- Assumed child is a point particle.  
- Neglected air resistance, friction, and external forces.  
- Proposed revision: include child’s body dimensions, resistive forces, and more realistic swing mechanics.  

---

## 📄 Files in This Repository

- `TMA07.pdf` – Full modelling report with equations, assumptions, results, and evaluation.  
- `README.md` – Project summary (this file).  
- (Optional future additions: Python/Matlab code to simulate the model and generate graphs.)

---

## 📚 References

- **BS EN 1176** – Playground equipment and surfacing safety standard.  
- The Playground Centre (manufacturer specifications for comparison).  
- Open University MST210 – Mathematical Modelling course materials.

---

## 📬 Contact

If you’d like to discuss this project further:  

- 📧 [emiliazabrzanska02@gmail.com](mailto:emiliazabrzanska02@gmail.com)  
- 💼 [LinkedIn – Emilia Zabrzanska](https://www.linkedin.com/in/emilia-zabrzanska/)  

---

## 📜 License

This project is made available under the MIT License. You are free to use, adapt, and share the modelling approach with attribution.
