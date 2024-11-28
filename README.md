This mod is for the Extended Tooltips [tt] mod to extend item tooltips with the following
basic info:

* Tool digging times
* Weapon stats
* Food stats
* Node damage
* Node light level
* Node info: climbable, slippery, bouncy, jumping restriction

This mod assumes that the default gameplay behavior of Luanti is used.

This mod introduces support for new item definition fields:

* `_tt_food`: If `true`, item is a food item that can be consumed by the player
* `_tt_food_hp`: Health increase (in HP) for player when consuming food item

Because there is no standard way in Luanti to mark an item as food, these fields
are required for food items to be recognized as such.

## Version
1.0.0

This mod requires Luanti 5.10.0 or later.

## License
MIT License.
