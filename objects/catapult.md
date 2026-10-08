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
