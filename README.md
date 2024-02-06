# Information

This build uses **lazy.vim** as a plugin manager.

The main configurations are kept inside the **lua/ybnbatop** path. 

* **nvim/init.lua** - is responsible for loading the main chunk (ybnbatop directory)
* **lua/ybnbatop** - contains the settings themselves
* **lua/ybnbatop/lazy** - contains plugins and their configurations (ThePrimeagen style)
* **lua/ybnbatop/init.lua** - an initialiser that gets other files, plugins, functions and etc.
* **lua/ybnbatop/set.lua** - an initialiser with settings for vim itself (and not the plugins), like line number, and etc.
* **lua/ybnbatop/remap.lua** - a file that is responsible for remappings (standart vim key remaps, not plugins!)
* **lua/ybnbatop/lazy_init.lua** - a caller that specifies that we are going to use Lazy and that we are giving it the **lazy** directory to get the plugins from

# Installed Plugins

* telescope.nvim = find files and much more
* colors.lua = contains 3 themes and is also a setter for themes (function ColorMyPencils)


