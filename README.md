# Component Explorer

For more on how to install and use Component Explorer, see the Wiki: https://noita.wiki.gg/wiki/Mod:Component_Explorer

## Dev Setup

To set up CMake for development, run the following commands:

```sh
python3 -m venv venv/
cmake -G Ninja -S path/to/component-explorer/ -B build/ -DPython_ROOT_DIR=venv/
cmake --build build/
cmake --install build/ --prefix ~/.local/share/Steam/steamapps/common/Noita/mods
```
