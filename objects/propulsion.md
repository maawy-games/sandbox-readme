[`< Back to main documentation`](README.md)

## Propulsion Object

### Functions

* `push(force: float)` - Pushes the object it faces with `force` force.
* `get_distance(message_name: String)` - gets the distance of the object it faces. Sends the distance to `broadcast_message` event with `message_name = {message_name parameter}`
* `range_alert(range_from: int, range_to: int, alert_name: String)` - senses object for distance between `range_from` and `range_to` and if so - sends `propulsion_distance_alert` to `broadcast_message` event with a `message_value` of `{alert_name}`.
* `set_enabled(status: bool)` - Enables / disables the propulsion object's ability to push objects.
