## ANSYS file structure and description

* [3D_components]
	* [3D_Components]
		* These files are ready made and designed to fit together. Pay attention to the notes in the file, they will instruct you on how to assign variables
	* [Circuit_Boards]
		* These are the models that the Circuit Board 3D Components were generated from. Use these to generate modified components.
	* [Helical]
		* Due to complexity in the simulation set up, components have not been generated from these models. If you would like to use a helical in your model, start with a copy of one of these files and build it from there. Please do not modifify these files.
	* [OreSat_Frame]
		* These are the model for the oresat frame the 3D component was generated from. The constructor model has yet to have any of its constructions assigned, makeing it much easier to modify. 
	
* [Helix_Simulation_Sets]
	* [1_Perfect_Brick]
		* Simulations done with perfect electrical conductors.
	* [2_Imperfect_Conductors]
		* Simulations done with some material properties accounted for.
	* [3_Defined_Geometry]
		* Simulations done with a number of geometric definitions from the solidworks Oresat Structure