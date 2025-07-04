01_geometry.proj  
Includes original geometry and original shell mesh for leaflets for  
non-uniform thickness distribution.

02_smoothValveShellMesh.proj  
Smoothed shell mesh of aortic valve for non-uniform thickness distribution.

03_smoothValveVolumeMesh.proj  
Smoothed 3D volume mesh consisting of hexahedral elements (non-uniform  
thickness).

04_ValveVolumeSurfaceModel.proj  
Original surface model for aortic root. Perfect fit together with 03.

05_SmoothAorticRoot.proj  
Smoothed aortic root.

06_SmoothAorticRootMesh.proj  
Smoothed aortic root shell mesh (mixed mesh) for deformable aortic root.

07_SmoothAorticRootSurfaceReduced.proj  
Surface model for use with gmsh. Gmsh can be used for creating the triangular  
fluid surface mesh needed for the ICFD solver.

08_gmshImportTest.geo  
Gmsh file used for specifying mesh sizes at important geometry points.

08_gmshImportTest.step  
Import file for gmsh. Needs to have the same name as geo file to work.

09_gmshfluidMesh  
Gmsh export. Needs to be adjusted in LS-PrePost to generate the k. file.

fluidMesh.k  
solidMesh.k  
k.-Files containing the solid mesh of the aortic valve leaflets and the fluid  
surface mesh of the aortic root.

GenerateAorticValveMeshInLSPrePost  
Instructions of how to create the above files.
