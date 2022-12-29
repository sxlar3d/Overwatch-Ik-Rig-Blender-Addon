# Overwatch-Ik-Rig-Blender-Addon
Generates a ik rig for overwatch models extracted from datatool/datawatch 

To Install, Download the recent zip file (just select it under the readme file and click download), and go in blender and go to edit > preferences > addons > install and install the zip file and enable it.

Once installed it will pop up on the side of the sidebar and to create the ik just select the armature on a character in object mode and press "Create Ik"

This will Create A Ik rig for the selected character.

Bones are renamed to be easier to know what you're selecting, along with changing the look of the bones.

Important Bones for the Ik: Ik_foot_l/r (Moves the legs), Ik_hand_r/l (Moves the entire arms), Pole_arm_r/l (moving this bone will move the direction of elbow), Pole_leg_r/l (moving this bone will move the direction of the knee)

Note: This is version 1. i still need to add and update things, below are some bugs and upcoming changes to the addon.

Bugs: 
1. Female characters right leg will look twisted, to fix just go to pose mode, select the foot_r bone and go to the bone constraint properties and set the pole angle to 0. of course if the leg does not look twisted for you theres no need for changing it.

2. (Female characters again) when raising the foot_r bone directly upwards with no moving to the sides or anything, it gliches out and does not really go to where it needs to be, to fix you can just rotate the foot_r bone till the leg looks gets to the right spot.

3. Non human like characters (Rammattra, Orisa, Etc) doesnt fully have the ik rig as they have a extra set of bones as they have multiple legs/arms. This will be fixed in the upcoming update/updates.

Upcoming changes:
1. Adding singular buttons for each non human character that will make a unique rig for them
2. renaming more bones and changing the look of more of them
3. Adding a eye rig
4. Adding a facial rig (probably wont be anytime in the upcoming weeks)
5. Adding a button in the panel that which be a shortcut to enabling or disabling Ik and Fk For Each Inverse kinematics bone.

Any ideas or suggestions, or feedback are appreciated!
