You are a surveyor equipped with a print-stone & a small opaque bird that fits in the hallow of your hand. You are blind.

The object of the game is to render the other player's opaque bird with your print-stone. Each level("the board") is a section of topology that is mirrored.

Only the print-stone's owner can view its output. The game immediately ends when you render the cell that the bird placed on.

The game starts in darkness; however, players may mouse over the empty grid-board, Each turn-step a player may make an action.
- move a piece.

### SceneGraph Matrix
| **Piece** | **Script** |
| --- | --- |
| print-stone | PrintStone.cs | 
| bird | Bird.cs | 

### Action Matrix
**The bird can store snapshots of each cell that it moves over to a limit. if the bird moves into the print-stone's square then the stored snapshots are rendered**
| **Piece** | **Action** | 
| --- | --- | 
| print-stone | render | 
| bird | CaptureImage, StoreImage, ReleaseImageStore | 

- each object takes a space on the board; however, the bird may share space with other pieces while player & print-stones cannot.

- At the end of the game. 7 score points are added to the winning players tally while 7 points are deducted from the losing player.
- The winning player may add the captured bird to his aviary. 
- A player may resign at any time resulting in a loss.

  



