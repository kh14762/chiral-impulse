You are a surveyor equipped with a print-stone & a small bird that fits in the hallow of your hand. You are blind.


### SceneGraph Matrix
| **Objects** | **Script** | 
| --- | --- | 
| print-stone | PrintStone.cs |  
| player | Player.cs | 
| bird | Bird.cs | 

### Script Associations
???

### Script Constraints
- inherits from Node3D.
- able to be dragged onto empty node3D without any other scene graph dependencies.
- accept editor imports.
- make use of an abstract factory / builder that is responsible for customizable-instantiation only.
- make use of signals to communicate state with other objects.

  



