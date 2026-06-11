# Structural Evaluation of Bicycle Frame Materials Under High Load

🎓 FEA Course Project (MEE 503L) | Al Maaref University — Mechanical Engineering

## 📌 Project Overview
This project evaluates the structural performance of a bicycle frame under
high loading conditions using Finite Element Analysis in Abaqus. Three 
materials were compared under identical geometry, boundary conditions, and 
loading to determine the most failure-resistant frame material.

## 🎯 Objectives
- Apply a conservative design load simulating a heavy rider with dynamic effects
- Compare stress distribution and deformation across three frame materials
- Evaluate structural safety using the Von Mises failure criterion and Factor of Safety

## 🛠️ Tools & Software
- Abaqus/Standard 2022
- Static Structural Analysis
- Von Mises Stress Criterion

## ⚙️ Loading Conditions
| Parameter | Value |
|---|---|
| Rider + Cargo Mass | 150–180 kg |
| Base Load | 1765 N |
| Dynamic Amplification Factor | 2× |
| **Design Load** | **3500 N** |

## 📊 Materials Compared
| Material | Young's Modulus (GPa) | Yield Strength (MPa) |
|---|---|---|
| Aluminum Alloy 7005 | 72 | 350 |
| Titanium Alloy Ti-6Al-4V | 110 | 830 |
| High-Strength Steel AISI 4130 | 210 | 435 |

## 📈 Key Results
| Material | Max Von Mises Stress (MPa) | Factor of Safety | Outcome |
|---|---|---|---|
| Aluminum Alloy 7005 | 1199 | 0.29 | ❌ Failure |
| Titanium Alloy Ti-6Al-4V | 1092 | 0.76 | ❌ Yielding |
| High-Strength Steel AISI 4130 | 10.9 | ~39.9 | ✅ Safe |

## 🏆 Conclusion
High-Strength Steel (AISI 4130) proved to be the most suitable material,
exhibiting the lowest deformation and highest factor of safety. Aluminum 
and Titanium both exceeded their yield limits under the applied load without 
geometric reinforcement.

## 📁 Repository Contents
- 📄 Full simulation report (PDF)
- 📊 Displacement and Von Mises stress contour plots (Abaqus)

## 🔮 Future Work
- Fatigue and nonlinear material analysis
- Weld modeling and geometry optimization
- Validation against international bicycle frame standards
