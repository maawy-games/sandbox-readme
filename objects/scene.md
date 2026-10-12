[`< Back to main documentation`](../README.md)

## Scene Object

Represents the scene itself.

### Functions

* `create_pin_joint(joint_id: String, id_a: String, id_a: String, softness: float = 0.0)` - Creates a pin joint.
  * `joint_id` - joint its unique identifier.
  * `id_a` - Object A `object_id`.
  * `id_b` - Object A `object_id`.
  * `softness`
* `create_grove_joint(joint_id: String, id_a: String, id_a: String, initial_offset: float = 25.0, length: float = 50.0)` - Creates a grove joint.
  * `joint_id` - joint its unique identifier.
  * `id_a` - Object A `object_id`.
  * `id_b` - Object A `object_id`.
  * `initial_offset`
  * `length`
* `create_damped_spring_joint(joint_id: String, id_a: String, id_b: String, damping: float = 1.0, length: float = 50.0, rest_length: float = 0.0, stiffness: float = 20.0)` - Creates a pin joint.
  * `joint_id` - joint its unique identifier.
  * `id_a` - Object A `object_id`.
  * `id_b` - Object A `object_id`.
  * `damping`
  * `length`
  * `rest_length`
  * `stiffness`
* `destroy_joint(joint_id: String)` - Destroys a joint with `joint_id` unique identifier.
