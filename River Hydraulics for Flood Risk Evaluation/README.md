# River Hydraulics for Flood Risk Evaluation

## Case Study
14 km reach of the **Oglio River** (Lombardy, Italy) between Ostiano and Canneto sull'Oglio. The reach includes two bridges, a weir, and sections where flow splits into two branches during flood events.

**1D Steady flow**
- Geometry completion: modelled bridges and weir from surveyed cross-sections
- Manning's coefficient: selected from USGS reference tables, validated against aerial photos, sensitivity tested with min/normal/max values
- Boundary conditions: tested all four combinations of normal/critical depth at upstream and downstream ends
- Levees: identified sections where HEC-RAS incorrectly flooded dry areas, corrected using aerial photo verification
- Geometry: identified cross-sections that lose perpendicularity to flow during large floods and assessed their impact

**1D Unsteady flow**
- Input: design hydrograph for T = 20 years (peak Q = 450 m³/s)
- Same sensitivity analyses repeated: Manning's, levees, spatial discretization (200 m vs 100 m), time step (30 min vs 15 min)
- Compared results to 1D steady at equivalent discharge

**2D modelling**
- Two simulations with different floodplain configurations
- Compared water surface and velocity profiles against 1D results at two cross-sections
- Discussed why 2D gives a more realistic velocity distribution across each section


## Preview

![2D velocity map](images/velocity_2D_colormap.png)
