You are a surveyor equipped with a print-stone & a small bird that fits in the hallow of your hand. You are blind.
The object of the game is to navigate a cell matrix. Each level has a beginning & a end. the bird can be commanded to cycle above a given cell. the birds vision can be translated via a sequence of chirps. This wave form can be captured by the print-stone that will print a chiral space. You are only able to perceive this space. The print stone is embedded onto the bird. You can communicate with the print stone however there is a set latency. chiral snapshots can go stale after awhile and may need to be refreshed. 

### SceneGraph Matrix
| **Objects** | **Script** | 
| --- | --- | 
| print-stone | PrintStone.cs |  
| player | Player.cs | 
| bird | Bird.cs | 

### Script Constraints
- inherits from Node.
- able to be dragged onto empty node3D without any other scene graph dependencies.
- accept editor imports.
- make use of signals to communicate state with other objects.

  



