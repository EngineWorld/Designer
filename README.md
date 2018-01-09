# Designer Manual

## Introduction
Designer is an Editor Mode created as a plugin for Unreal Engine 4. For more in depth information about plugins inside Unreal Engine 4 read their [documentation](https://docs.unrealengine.com/latest/INT/Programming/Plugins/).

The Designer plugin is licensed under the MIT license. The source code is available on [GitHub](https://github.com/RoelBartstra/Designer). Feel free to make improvements, and when possible, share the changes with the community.

## Download Plugin
Download the [latest version](https://www.unrealengineer.com/designer) and unzip the archive.

## Installing
Plugins are always located in your plugin's directory. In order for plugins to be found, they must be located in one of the valid search paths for plugins in Unreal Engine.

Pasting the Designer folder inside the Engine plugins directory will expose this plugin to all your projects. Any time a new engine version is installed the plugin has to be moved to the new engine versions' folder.
> ### Engine
> /UE4 Root/Engine/Plugins/Designer/

​Pasting the Designer folder inside the Project plugins directory will expose this plugin only to this project.
> ### Project
> /My Project/Plugins/Designer/

Copy the Designer folder extracted from the zip file to the plugin folder fitting your needs.

Open you project. The extra editor mode should now available. If the mode is not visible, open the Plugins window and check if the plugin is enabled under Editor Modes / Designer. If the plugin is disabled, enable it and restart the editor. If the plugin is not showing up, close the editor and check if the plugin is installed in the correct directory.

---
***
___

1. First ordered list item
2. Another item
  * Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.  
   
   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |