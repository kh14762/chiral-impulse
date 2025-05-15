You are a surveyor equipped with a print-stone & a small opaque bird that fits in the hallow of your hand. You are blind.

The object of the game is to find the other players opaque bird. Each level is a section of topology that is mirrored.

the bird can be commanded to cycle above a given cell. the birds vision can be translated via a sequence of chirps. This wave form can be captured by the print-stone that will print a chiral cell. You are only able to perceive this space. The print stone is linked to the bird. You can communicate with the print stone however there is a rendering latency. chiral snapshots can go stale after awhile and may need to be refreshed. 

The game starts in darkness; however, players may hover over the grid-board, Each turn-step a player may make an action.
- move a piece.
- render a cell.

### SceneGraph Matrix
| **Objects** | **Script** | **Tertiary Function** |
| --- | --- | --- |
| print-stone | PrintStone.cs | OrbitCamera |
| player | Player.cs | Knight/Bishop |
| bird | Bird.cs | Phantom |

### Script Constraints
- inherits from Node.
- able to be dragged onto empty Node without any other scene graph dependencies.
- accept editor imports.
- make use of signals to communicate state with other objects.

  



