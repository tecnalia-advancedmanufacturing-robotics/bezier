# keepUpperPartofDilatedMesh

This function is implemented with the `VTK` library. In order to generate "accessible" trajectories only the upper part of the dilated mesh is kept. This ensures that the extrication trajectories are collision free with the scanned mesh.

![dilate](dilate.png)  | ![keep_upper_part_of_dilated_mesh](keep_upper_part_of_dilated_mesh.png)
---------------------- | ------------------------------
Dilated mesh in grey   | Filtered dilated mesh in grey
