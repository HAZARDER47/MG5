# MG5
## Devlog
Put your Devlog here.
In a top-down game like League of Legends, I would use a NavMesh for click-to-move controls. The player picks a destination, and the character can find a route around walls and other obstacles on its own. In a physics-based platformer like Celeste, I would script the movement and collisions because the player directly controls when to jump, dash, and land. Those actions depend on timing and momentum.

The loop in BirdManager starts at index 0 and visits every entry in the birds array. Vector3.Distance measures the distance between the current bird and the Pudu in world units. A bird runs away if its distance is less than or equal to the interaction distance. Each bird is checked separately, so several nearby birds can run away at the same time.
## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)