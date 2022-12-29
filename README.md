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

2. (Female characters again) when raising the ik_foot_r/l bone directly upwards with no moving to the sides or anything, it gliches out and does not really go to where it needs to be and rotates out of no where, to fix you can just rotate the foot_r/l bone till the leg looks gets to the right spot.

(Bug 2) at the moment i dont see this really being a problem, but if it gets to bad for people i can always *try* and fix it for female characters, probably would be impossible due to the names being the same as males. but im sure i can make it work, but once again it isnt that bad all you have to do is just rotate the foot_r bone, till the bone is rotated correctly. 

3. Non human like characters (Rammattra, Orisa, Etc) doesnt fully have the ik rig as they have a extra set of bones as they have multiple legs/arms. This will be fixed in the upcoming update/updates.

4. Sometimes the Root bone doesnt scale up, this is due to some root bones being sized differently and when scaled up it just isnt big like its supposed to, to fix you can just go to pose select the root bone at the very bottom, and go to bone properties, and then go to viewport display > custom shape, and then change the scale xyz values to a VERY high number like around 500-700, if thats to big then youc an always scale it to your liking.

Upcoming changes:
1. Adding singular buttons for each non human character that will make a unique rig for them
2. renaming more bones and changing the look of more of them
3. Adding a eye rig
4. Adding a facial rig (probably wont be anytime in the upcoming weeks)
5. Adding a button in the panel that which be a shortcut to enabling or disabling Ik and Fk For Each Inverse kinematics bone.

Any ideas or suggestions, or feedback are appreciated!

*also follow my twitter l o l: sxlar3d*
