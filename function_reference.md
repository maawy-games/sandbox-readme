[`< Back to main documentation`](README.md)

These functions are available for all objects.

## Free version

* `console(string: String)` - Prints the string to the stage console.
* `change_scene(scene_name: String)` - Change the current scene to the name specified.
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

## KeyCode reference

Examples of key codes:

* `KEY_C` - "C"
* `KEY_ESCAPE` - "Escape"
* `KEY_MASK_SHIFT | KEY_TAB` - "Shift+Tab"
