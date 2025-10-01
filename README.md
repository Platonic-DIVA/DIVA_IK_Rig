# DIVA_IK_Rig
A recreation of the Project DIVA IK rig used in game. Compatible with motions from the game, with View Layers for added visibility.

# Usage
This rig is best used with motions ripped straight from the game (NOT MMD). If you need help getting game-ready motions, check https://github.com/h-kidd/noesis-project-diva. 

# How it works
Project DIVA uses a complicated IK setup, (mostly because it comes from an engine used for fighting games primarily). Using constraints, you can get extremely close to results you would see in game. Due to how Blender handles IK chains, the arms do tend to "lock up" and look out of place when fully extended. I have mitigated this with Limits on the IK chains, and by influencing which way the bones will bend. This *should* keep the results accurate, without breaking the model.

# Special thanks
Thanks to WaelProton, Skyth, and Korenkonder for their work in understanding Project DIVA's bone structure, and FlyingSpirits for a refrence on certain bones.
