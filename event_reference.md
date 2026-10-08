[`< Back to main documentation`](README.md)

## General events

### Free version

* `broadcast_message(key: String, value: String)` - A broadcast message is sent from another object.
* `collided(param: String, this_object: String, with_object: String)` - when 2 objects collide.

### Pro version

* `timer_timeout(timer_name: String)` - when a timer times out.
* `object_spawned(object_type: String, object_name: String)` - when a new object is created - by the spawner.

## Bomb events (pro version)

* `bomb_exploded(param: String, object_name: String)`

## Coin events

* `coin_picked(coin_name: String, picker_name: String)`

## Explosive events (pro version)

* `explosive_exploded(param: String, object_name: String)`

## Gem events

* `gem_picked(color: String, gem_name: String, picker_name: String)`

## Key events

* `key_picked(color: String, key_name: String, picker_name: String)`

## Lever events (pro version)

* `lever_switched(param: String, direction: String, lever_name: String, object_name: String)`

## Impulse grid events (pro version)

* `impulse_grid_engaged(param: String, grid_name: String, body_name: String)`

## Propulsion object events (pro version)

* `propulsion_object_detected(param: String, object_name: String)`
* `propulsion_object_pushed(param: String, object_name: String)`

## Spring events

* `spring_engaged(param: String, spring_name: String, body_name: String)`

## Switch events (pro version)

* `switch_on(param: String, color: String, object_name: String, body_name: String)`
* `switch_off(param: String, color: String, object_name: String, body_name: String)`

## Variable events (pro version)

* `variable_changed(var_name: String, var_value: String)`
