[`< Back to main documentation`](README.md)

These functions are available for all objects.

## Free version

* `console(string: String)` - Prints the string to the stage console.
* `show_message(message: String)` - Shows an alert message.
* `change_scene(scene_name: String)` - Change the current scene to the name specified.
* `reload_scene()` - Reloads the current scene.
* `broadcast_message(key: String, value: String)` - Sends a broadcast message to other objects.
* `kill()` - kills the current object.
* `get_object_name()` - name of the current object.
* `get_position_x()` - X coordinate position of the current object.
* `get_position_y()` - Y coordinate position of the current object.
* `get_rotation()` - Gets the rotation of the object in degrees.
* `get_current_scene()` - Gets the name of the current scene.
* `set_variable(key: String, value: Variant)` - Sets the value of a variable.
* `get_variable(key: String)` - Gets the value of an existing variable.
* `get_object_parameters()` - Gets parameter values of an object, if the parameters are set in the properties.
* `get_key_pressed(key: String)` - Checks to see if the specific key is pressed on the keyboard (look at - key press reference).

## Pro version

* `enable_camera(enable: bool)` - Enables or disables the camera to be focussed on the current object.
* `ripple_fx()` - Creates a ripple FX at the object position.
* `start_timer(timer_name: String, interval: float)` - Creates a timer with timer name. It will emit a `timer_timeout` event.
* `set_scene_camera_position(x_position: int, y_position: int)` - Sets the scene camera (if enabled) to X and Y coordinates specified.
* `get_scene_camera_position_x()` - Gets X coordinate of scene camera.
* `get_scene_camera_position_y()` - Gets Y coordinate of scene camera.
* `get_object_id()` - Gets the unique `object_id` of the object.
* `show_gem_counter(show: bool, color: String, initial_count: int)` - Shows / Hide gem counter indicator with `initial_count` gems. Color can be `red`, `green`, `blue` or `yellow`
* `show_coin_counter(show: bool, initial_count: int)` - Shows / Hide coin counter indicator with `initial_count` coins.
* `set_gem_counter(color: String, count: int)` - Sets the gem count of gem color `color` to the `count`.
* `set_coin_counter(count: int)` - Sets the coin count to the `count`.

## Shared functions for rigid bodies

### Rigid bodies

* `block`
* `bomb`
* `destructible_block`
* `explosive`
* `locked_block`
* `player`
* `propulsion`
* `spawner`
* `wheel`

### Shared functions

* `add_constant_force(x: float, y: float)` - Sets a constant force.
* `apply_impulse(x: float, y: float)` - Applies an impulse force.
* `apply_constant_torque(impulse: float)` - Sets a constant rotation force (torque).
* `apply_torque_impulse(torque: float)` - Applies an impulsive rotation force (torque).

## KeyCode reference

Examples of key codes:

* `KEY_C` - "C"
* `KEY_ESCAPE` - "Escape"
* `KEY_MASK_SHIFT | KEY_TAB` - "Shift+Tab"
