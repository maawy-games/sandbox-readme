[`< Back to main documentation`](../README.md)

## Catapult Object

### Functions

* `spawn(object_type: String, force: float)` - spawn an object `object_type` with a force of `force`. Valid object types:
  * `bomb`
  * `explosive`
  * `block`
  * `player`
* `rotate_to(rot_degrees: float, duration: float)` - rotate to angle `rot_degrees` in `duration` time.
* `is_rotating()` - Checks to see if its actively rotating.
* `set_object_position(x_coord: float, y_coord: float, is_tween: bool = false, duraction: float = 0.25)` - Moves the object to a specific position, and can do it as a tween with a duration or without tween (immediate)
