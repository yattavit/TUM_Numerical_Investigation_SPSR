# Numerical Investigation of Pressure Drop at Turbulent Flow Conditions in Single Pellet String Reactors [LaTeX, OpenFOAM®, ParaView, Linux, C++]

Written in LaTeX, [Link](https://www.latex-project.org/)

CFD Software used:  
[ParaView, GUI](https://www.paraview.org/)  
[OpenFoam](https://www.openfoam.com/)

Thesis Document:  
[Thesis](Thesis.pdf)

Within this work, an existing investigation of pressure drop in various Single Pellet String Reactor (SPSR) set-ups is extended to cover turbulent flow. Two geometry-based weighting factors previously applied by Fernengel et al. are introduced to scale the influence of the confining wall in an equivalent diameter expression. It was concluded that in such narrow fixed bed reactors, influence of the confining wall on pressure drop must be accounted for and the use of any of the proposed weighting factors on the Ergun equation will shift results closer to parity.


Appropriate adjustments to include turbulent flow are made and ParaView is used to extract the pressure drop in previously proposed SPSR variations by Fernengel et al. With the exception of increasing superficial velocity and scaling factor in SPSR variations, the simulative pressure drop largely follows previously established trends from Fernengel et al.


The extracted simulative pressure drop values were compared against an aggregation of literature pressure drop correlations compiled by Erdim et al. A total of four plots pertaining to friction factor and pressure drop were plotted, and reasons for deviations from simulative values were discussed. It was observed from the results obtained that plotting the friction factor or pressure drop against normal Reynolds will, in general, lead to reduced values of friction factor and pressure drop respectively. It will not, however, change any observed trends when compared to their wall modified Reynolds counterparts. Most literature pressure drop correlations tend to underpredict simulative pressure drop within a SPSR in turbulent flow. This points to a need for specialised correlations relating to SPSR geometries to be developed, should predictions closer to parity be desired.
