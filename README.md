# chiral-impulse
co-operative game
  You are a group composed of founders, explorers, & sojourners attempting to bring economic prosperity to your country & allies. Adorned with an array of coats, arms, & hats, You must dive into the vast deep, searching for artifacts and resources to fund your colonization complex. 

## Abstract Concepts
### Countries & Allience's
  Each Player must pledge to country. They may Ally with any other country of their choosing, but must take into consideration the downstream political effects. 
### Player Agency
  Each Player must balance the effects of their actions, not withstanding those of maximum harmony or dissonance. 
### Aviary
  Each Player must pledge to a bird house. 
### Monolith 
  recurring set of geometry within the game, represents themes of morality, reflection, and power

## Implemented Game Objects 
#### Globe
  Each Player starts at home. Earth.
#### Vessal
  A cynlindrical vessal composed of different submodules (capsul + cabin + propulsion).
#### SubStation
  A cynlindrical vessal composed of different submodules (cabins). Can house any player; however, each cabin can be configured to suite the needs of the player. Expressed as a series of linked cabins. 

#### [artifact_id][common_name][discovered_by]
_Artifacts are expressed as phantom, Opaque, Objects. They are said to be long lost tools of an ancient extraterristrial race_
They are massless and produce no measureable output besides being visible to only humans. Given enough will a human may tether to it and utilize it's functionality. 
The artifact will follow the tethered player. 

- All artifacts are inviolable
- can interface with the tethered player or other artifacts in a set range.

[^1]: **bold**
[^1]: `code`  
[^1]: _italic_

  | ID |  Name | Class | Disoverer | 
|:-----|:--------:|------:|------:|
| 743   | **dark** | stone | ICN tech | 
| 313   |  **seer** | stone | Talkin.net |
| 273   | **print** | stone | Harken co. |
| 412   | **gate** | stone | Schell corp. |

#### Dark
  _A seemingly sentiant caretaker that controls substation functionality. Linguists have spent decades attempting to decompile its image but little progress has been made_.
  - can carry long thought provoking conversations.
  - Has the same access as a pilot.
  - tablet.

  #### Seer
  _An optical device that can be used to communicate with other seerstones over infinte rang with zero latency_.  
  - Monitors vast volumes. 
  - Must orbit the sphere to gain different pov.
  - Smaller stones have fixed positions** while larger ones have greater fov.
  - sphere. 

  #### Print
  _Player is equipped with a printstone. The relationsip between them is binding_.
  - contains a set of place-able gate stones, move-able only by the owning player.
  - is capable of constructing gate stones in a 1 turn step (ts) & a perfect copy of itself in 4 (ts).
  - cube.

  #### Gate
  _Printers can construct gate stones, given enough elements, these are accounted for as bits by the printer_
   - A stone that can relay interactions between artifacts and players
   - 5 configurations

**Ordered by cost**
 | Name | Vertices | Edges | Unique Hamiltonian Cycles? | Hamiltonian cycle count	|
|:-----:|:-----:|:--------:|:------:|:------:|
| Tetrahedron | 4 | 6 | 1 | |
| Octohedron | 6 | 12 | 2 | |
| Cube | 8 | 12 | 4 | |
| Isohedron | 12 | 30 | 256 | 2560 |
| Dodecahedron | 20 | 30 | 2048 | 2048 |

https://anydice.com/ by Jasper Flick
  - adding the stone's outputs can produce distribution curves.
  - distributions can be shaped by applying functions to logical constraints
  - Each Hamiltonian Path is a collection of vectors that are constrained to the geometry (Open off 0)
  - Each Emiltonian Circuit is a collection of vectors that are constrained to the geometry (Closed on 1)
```

```




  







