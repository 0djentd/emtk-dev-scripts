# Description
This script designed to make it easier to create modal Blender operators.

It takes file with json array of names, or dict of arrays as
first positional argument and generates props definitions from it.

* If --variations is specified, it will also generate additional properties.
* If --addon_name is specified, it will insert it before all properties.

#### Example
```
--variations=['shift', 'alt', 'ctl']
--addon_name='emtk'

emtk_angle_limit
emtk_angle_limit_shift
emtk_angle_limit_alt
emtk_angle_limit_ctl
```

If --props_names is specified, it creates list of properties names without
variations.
In previous example it looks like this:
props_names = [emtk_angle_limit]
