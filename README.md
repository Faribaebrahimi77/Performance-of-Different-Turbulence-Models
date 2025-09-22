# Comparative Analysis of RANS Turbulence Models for Curved Hump Flow Simulation

# overview
This research focuses on a comprehensive comparative analysis of various Reynolds-Averaged Navier-Stokes (RANS) turbulence models for simulating turbulent flow over a curved hump geometry. The study aims to evaluate the accuracy, computational efficiency, and predictive capabilities of different RANS approaches using the Greenblatt experimental benchmark as validation reference.

The study evaluates the performance of different RANS turbulence models in predicting complex flow phenomena including separation, reattachment, and adverse pressure gradient effects.

# Geometry Specifications
<img width="806" height="337" alt="image" src="https://github.com/user-attachments/assets/99079d63-405c-4647-b2eb-e8dcdd7e445b" />
# Methodology
Computational Approach
This study utilizes ANSYS Fluent as the primary CFD solver, leveraging its comprehensive RANS turbulence model library and advanced numerical schemes.
Software Configuration:

CFD Platform: ANSYS Fluent 2023 R1

Mesh Generation: ANSYS Meshing with structured/unstructured hybrid approach 

Post-Processing: CFD-Post, Tecplot 360, and custom Python scripts

High-Performance Computing: Parallel processing on multi-core systems

# Results and Conclusion
The exact location of flow separation and reattachment could not be accurately predicted using the applied models, and a higher level of precision is required for reliable reattachment prediction.

The k-ε models generally showed the weakest performance, and some of them were not able to predict flow separation.

The k-ω models, especially the SST model, demonstrated higher accuracy and delivered the best performance in this study.

The RSM model, in some cases, showed lower accuracy compared to the SST model. This might be due to its sensitivity to grid resolution and mesh quality, or because the Linear Pressure-Strain approach was applied in this model.

Ultimately, none of the turbulence models can be considered universally reliable for all cases. A suitable model should be selected for each specific condition, and validation should always be performed after simulation.
![Uploading image.png…]()
<img width="1354" height="847" alt="cont-vel" src="https://github.com/user-attachments/assets/3995933e-5be9-4f10-a5c7-0fd47c8f34de" />
<img width="1354" height="847" alt="meanvelocity" src="https://github.com/user-attachments/assets/c64384e3-63d4-497e-85fe-087fc82abbec" />
<img width="1354" height="847" alt="str-vel" src="https://github.com/user-attachments/assets/5f8af060-bdab-4826-83d6-236f264a5c91" />
<img width="800" height="800" alt="meanvelocity upstream" src="https://github.com/user-attachments/assets/36d8ac90-0938-45f4-974f-568195bac977" />



