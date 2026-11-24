# ROARING Reanimated server port

Minecraft 26.3 resource format 97.1. Uses FreeMinecraftModels 2.15.0 and the
LiveModules RoaringKnight adapter. No client-side mod is required.

/rk toggles the Knight disguise; left click plays the supplied swing animation.
/rk off removes it. /rk list lists clips. /rk play swing2 (or another listed clip)
previews that original clip. Permission: rk.use (default OP).

Geometry and animation override: supplied Roaring_Reanimated.zip, EYE.
Base Knight texture: ROARING 0.3 by H0lySeyhan, official Modrinth project noogFnLJ.
Original animation authors credited by the source pack: H0lySeyhan.
The server port uses a converted 166-cube / 18-bone Blockbench rig and preserves
all available Knight clips. The source references an absent slash effect bone;
that absent geometry cannot be displayed. Two nonnumeric source head rotations
in teleport/aura_farm are treated as zero, matching an undefined expression.

Use third-person camera to inspect the model. This is a visual disguise: player
collision, inventory and combat hitboxes retain normal player behavior.
