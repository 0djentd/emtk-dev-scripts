# emtk-dev-utils
Some scripts and tools that can be useful.

## scripts
### venv-symlink-modules
Creates new venv and symlinks modules in `.config/blender/3.1/scripts/modules`.

### remove-folds
Removes vim folds from all .py files.

## [generate-mod-props/](./generate-mod-props/README.md)
This thing designed to make it easier to create modal Blender operators.

It takes file with json array of names, or dict of arrays as
first positional argument and generates props definitions from it.
