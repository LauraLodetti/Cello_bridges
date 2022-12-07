# Cello_bridges
Master thesis work - FEM cello bridges simulations

The repository contains significant data and code (Matlab).
Folders are organized in this way:
* Cello_bridges/Bridge Models contains the 3D models in .sat format of Model 0, 
also referred to as _Normal Model_, and all the other models numbered progressively up to Model 30. Model 0 is the model most similar to a 
traditional French Cello Bridge and Model 30 is the model most similar to a Model X Cello Bridge.
* Cello_bridge/Bridge CAD contains the complete Autodesk Fusion files for Model 0 and Model 30, and a file with the sketches for 
bridges from 0 to 30.
* Cello_bridges/Simulations contains the COMSOL simulations. Filenames contain the type of study (Eigenfrequency/Stationary), the model (0/30) 
and the boundary conditions (a free / b fixed feet / c feet supported on springs / d feet supported on springs and constraints in the upper arch) 
Boundary condition c is referred to as "spring A" while boundary condition d as "spring B" in the files.
To import correctly geometries, please check the path in Component>Geometry 1>Import 1.
When inserting geometries different from Model 0 and Model 30, the Solid Mechanics node could require to select again boundaries and domains.  
* ModeShapes.mp4 collects and compares for Model 0 (left) and Model 30 (right) animations of the mode shapes of the first 10 vibrational modes, in the four boundary conditions considered.
  