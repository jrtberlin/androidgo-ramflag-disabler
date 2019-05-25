# Android GO lowram flag disabler

Disabling the lowram flag on Android GO devices adds some features but probably hurts the snappiness of the system.
Depending on the RAM amount of the device, restricting the amount of background processes can help a lot.

Setting the lowram flag to false should enable for example:
- notification listener support (requirement for WearOS and [AsteroidOS](https://asteroidos.org))
- improved multitasking
- picture in picture
- multi window support
