# MG4
## Devlog
The	Start method used in the FloatAnimation script sets the initial value of _timer to the value of _switchSpeed before Update is called which causes it to move in it's first direction. The Update method than constantly has the _timer value being changed, all while checking if it's less than or equal to zero so that it can make use of the _up variable which is tested to determine if the food should be going up or down and it is then set back to _switchSpeed to keep the cycle going. The top if statement is used to go up while the else is used to go down.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [City 3D models](https://assetstore.unity.com/packages/3d/environments/simplepoly-city-low-poly-assets-58899)
- [Bite sound effect](https://freesound.org/people/Jofae/sounds/353067/)