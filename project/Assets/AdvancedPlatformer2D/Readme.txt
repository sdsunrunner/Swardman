﻿**********************************

 ADVANCED PLATFORMER 2D 
(Copyright © 2014 UniPhys)

Online website  : sites.google.com/site/advancedplatformer2d
Youtube channel : www.youtube.com/channel/UC5-rb3KBjgISpaT8bcvqU_g
Unity forum thread : http://forum.unity3d.com/threads/246017-RELEASED-Advanced-Platformer-2D

***********************************

Thank you for your purchase, i'm very happy you are interested by my work!
I'm working hard during my personal time and it's always a pleasure to see someone new :-)

Please have a look at Documentation.pdf file first.
If you have any questions, suggestions, feedback or complain you can contact me at uniphys2d@gmail.com
And if you like this asset, please take time to write a small review on the asset store :-D

**********
CHANGELOG 
**********

Version 1.6 :
- Add Edge Grab feature
- Add Jumper game object
- Add Edge Sliding feature
- Add backward animation support when autorotate is off
- Fix rays penetration value after velocity/position correction on motor move
- Fix jump max height ugly behavior
- fix camera Face Lead stiffness

Version 1.5d :
- Fix stuck sometimes in ranged/melee attack states
- Add animation end detection for melee/ranged attack + remove useless LeaveXXX methods (you may need to update your attack animations)
- Fix front blocking wall detection
- Inputs plugins for PlayMaker

Version 1.5c :
- Carrier script review (you may need to update your animation/script settings, please check online documentation)
  .now handle rotation properly
  .update is now done at fixed timestep
  .collision detection with environment is now valid (no more teleport)
- Ground alignment review : more precise and smooth, prevent imprecision and unstable issues
- Add animation parameters to be used by animator for custom animation behavior (tutorial incoming)

Version 1.5b :
- Fix invalid speed with Stand and InAir animations
- Fix friction issues
- Add StopOnWall feature for walk/run

Version 1.5 :
- Updates to Unity 4.5
- Add character shifting ability 
- Add "OneWayGround" ability (i.e collide only from top of object) + down jumping
- Add AirJump horizontal impulse ability
- Add MaxSlope for ground align
- Fix some jittering when using ground align with complex meshes
- Add EventListeners class object for character events notification + add Audio management sample script
- Refactorize APInput (add Holders & Releasers special button)
- Review some samples scripts (optimization due to fix within Unity 4.5, bugfixes, new features)
- Add new samples for fadeToblack and loading level feature
- Unity inputs & plugin inputs can now be used at the same time during play
- Review uncrouch minspeed feature
- Review Standard state animations launching (now launch animation only once!)
- Reorganize files and folder tree structure
- Lots of bugfixes, refactorizations and tunings

Version 1.4 :
- Review inputs to handle plugin (NB : you must rebind your inputs names)
- Add support for EasyTouch asset plugin for quick and easy touchpad management
- Camera review (v1)
- Allows character rotation and ground alignment
- Down slope sliding
- Air/ground rotation setting
- Review existing samples and add new ones (MovingObject, Spikes, CollectableCoin)
- Start jump animation only when needed (allows in air up/down animation, see incoming Youtube tutorial)
- Add crouch stuck escape feature (thanks to John)
- Fix ranged attack bullet direction
- Carrier script now handles properly fixed time state updates
- Review some internal states management
- Minor bugfixes and tweaks

Version 1.3 :
- Ranged attack mechanism
- Force move
- New level : Ranged Attack
- New samples and prefab : GUI, Collectables (life, ammo)
- Minor bugfixes & reviews

Version 1.2 :
- Double jump
- Glide
- Ground snapping
- Advanced settings
- Wall slide
- New samples (e.g falling platform)
- Bugfixes & tunings (fix motor autobuilder)

Version 1.1 :
- Melee attack mechanism
 (with new demo level and animations)
- Hitable game object
- Friction engine review
- More prefab and scripting samples (npc, life system, scenaric events)
- Minor tweaks & bug fixes

Version 1.0 :
- Initial release
- Character motor
- Character controller & basic moves (jump, slide, walljump...)
- Ladder
- Railings
- Moving platform
- Camera
- Parallax Scrolling
- Material