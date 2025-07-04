# Aortic Valve Geometry Versions

This directory contains two different versions of the reconstructed aortic valve  
geometry, each located in a separate subfolder:

## Loose-Geometry

The `Loose-Geometry` folder contains the **first version** of the valve geometry.  
- It does **not include the nodulus**.  
- A more **generous smoothing** was applied.  
- This leads to a **wider gap between the valve leaflets**.

This version may be more suitable for exploratory simulations where exact  
coaptation is less critical.

## Tight-Geometry

The `Tight-Geometry` folder contains the **second version** of the geometry.  
- It includes the **nodulus**.  
- Smoothing was applied more selectively to better **preserve the original shape**.  
- The **leaflets are positioned closer together**, especially around the nodulus.

This version is recommended for cases requiring more accurate leaflet closure.
