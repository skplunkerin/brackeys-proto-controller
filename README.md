# Proto Controller
Simple first-person Character Controller for prototyping games in Godot.

It's designed to be simple.

It has options for:

- Jumping
- Sprinting
- Free-fly mode

## Installation
Drag proto_controller folder into the "addons" folder at the root of your Godot project. If no addons folder, create one manually.

## License
This repo is freely available under the CC0 license. For more info see LICENSE file.

## Changelog
- v1.1
  - Add "Wasd Keys" bool to Input Actions exported group with default false
  - Programmatically add WASD key presses to ui_up, ui_left, ui_down, ui_right if wasd_keys is true