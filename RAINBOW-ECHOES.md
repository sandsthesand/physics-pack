# Rainbow sprint echoes

Adds the dotbot_echo namespace to pack1.zip without changing existing asset entries.
Minecraft 26.3 format 97.1; no client mods or custom shaders.

Seven colors, six independently posed display parts, eight opacity levels over 0.8 seconds.
Requires the matching RainbowSprint LiveModules renderer. Head/body facing is sampled from
server state; limb motion uses server walk-animation data where available and a distance-based
estimate otherwise. This cannot guarantee the exact pose rendered by every vanilla client.
