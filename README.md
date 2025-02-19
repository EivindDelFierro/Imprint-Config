# ZMK Configuration Template
Wireless Cyboard keyboard configuration repository template for using ZMK firmware. [Instructions for use are located on our documentation site](https://docs.cyboard.digital/user-manual/quick-start/configure-layout).

# Current Configuration
1. Uses the imprint_function_row template
2. Has layer 0 for QWERTY and layer 5 for Colemak DH. Colemak uses transparent layers with the default layers for matching keys
4. Added support for directional keys, volume control, numpad, Bluetooth, and B1 controls in numpad_layer
5. Set other keypresses in keyboard_control_layer and numpad_layer to &none to prevent accidental keypresses. Transparent layer maintained for unassigned thumb cluster keys
6. Added custom color hue (though it defaults to undersaturated state) in keyboard_control_layer
