- https://github.com/EloiStree/2026_09_28_rust_steam_os_input_simulation
- https://github.com/EloiStree/2026_09_28_rust_steam_os_input_key_log

## Experiment: Reading Input from SteamOS on Steam Frame

This is an experiment in Rust to read and log keyboard input from SteamOS on the Steam Frame. White-hat project.

On Linux, there is no XInput like on Windows. Instead, keyboard and mouse input can be accessed individually through the system's input interfaces.
This should be an interesting experiment.

The goal is to explore SteamOS tools and APIs on the Frame and determine whether input can be captured by a background service and forwarded to GOMI or another application.
The longer-term idea is to use this as a foundation for experimenting with macro functionality.

This is strictly a white-hat project for research and experimentation. 
I'm not trying to build anything intended for illegal use.
