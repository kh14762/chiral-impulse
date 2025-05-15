You are a surveyor equipped with a print-stone & a small opaque bird that fits in the hallow of your hand. You are blind.

The object of the game is to render the other player's opaque bird. Each level is a section of topology that is mirrored.

The birds vision can be translated via a sequence of chirps. This wave form can be captured by the print-stone and output a chiral cell. There is a latency with this action. Only the print-stone's owner can view this output. The print stone is linked to the bird. chiral snapshots can go stale after awhile and may need to be refreshed. The game immediately ends when you render the cell that the bird placed on.

The game starts in darkness; however, players may mouse over the empty grid-board, Each turn-step a player may make an action.
- move a piece.
- render a cell.

### SceneGraph Matrix
| **Objects** | **Script** | **Tertiary Function** |
| --- | --- | --- |
| print-stone | PrintStone.cs | Camera |
| player | Player.cs | Knight/Bishop |
| bird | Bird.cs | Phantom |

- each object takes a space on the board; however, the bird may share space with pieces while player & print-stone 

  



