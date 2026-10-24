[`< Back to main documentation`](../README.md)

## Scene Object

Represents the scene itself.

### Functions

* `create_fixed_joint(joint_id: String, id_a: String, id_b: String)` - Creates a fixed joint.
* `create_pin_joint(joint_id: String, id_a: String, id_b: String, softness: float = 0.0, allow_rotate: bool = true, center_joint: bool = true, place_at_initial_position: bool = true)` - Creates a pin joint.
  * `softness`
* `create_grove_joint(joint_id: String, id_a: String, id_a: String, initial_offset: float = 25.0, length: float = 50.0)` - Creates a grove joint.
  * `initial_offset`
  * `length`
* `create_damped_spring_joint(joint_id: String, id_a: String, id_b: String, damping: float = 1.0, length: float = 50.0, rest_length: float = 0.0, stiffness: float = 20.0)` - Creates a damped spring joint.
  * `damping`
  * `length`
  * `rest_length`
  * `stiffness`
* `create_rope_joint(joint_id: String, id_a: String, id_b: String, max_distance: float, center_joint: bool = true, place_at_initial_position: bool = true)` - Creates a rope joint.
  * `max_distance` - Maximum rope distance.
* `destroy_joint(joint_id: String)` - Destroys a joint with `joint_id` unique identifier.
* `spawn_object(object_type: String, position_x: int, position_y: int, object_id: String = "")` - Creates an object of `object_type` type at position X and Y with `object_id` equal to the `object_id` parameter.

### Shared joint parameters

  * `joint_id` - joint's unique identifier.
  * `id_a` - Object A `object_id`.
  * `id_b` - Object A `object_id`.
  * `center_joint` - If the joint should be placed between the 2 objects.
  * `place_at_initial_position` - If `center_joint` is false, should the joint be placed on the initial object ID (`true`) or with the second object ID (`false`)
