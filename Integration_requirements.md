# Technical requirements for assembling of the partners’ levels to the joint EMICVL IT project

All partners shall comply with this technical requirements approved by the EU partners, starting October 18, 2017.

1. The final project assembling will be made in __Unity 2017.1.1f1__

2. Only those projects made in __Unity 2017.1.1f1__ will be accepted.

3. Partners should provide level/package file (not asset) in __*.unitypackage__ archive to be assembled to joint IT project 
   
   (see [Export Package](http://docs.unity3d.com/Manual/HOWTO-exportpackage.html) ) from Unity help pages.

4. Archive should be named as the following: EMICVL_IT group name_development version 
    
     (e.g: EMICVL_ONU_Beta3.2.unitypackage, EMICVL_TSU_Beta1.0.unitypackage) 

5. Project should be named as the following: EMICVL_IT group name (e.g.,  EMICVL_ONU, EMICVL_TSU) 

## Example:

    Archive//EMICVL_ONU_Beta3.2
                               |
                       Project |[EMICVL_ONU]


6. Content of the level project should have the following structure (folders) to be used in the project:

  - __Animation__ (level animation files)
  - __Textures__  (level texture files) 
  - __Materials__ (level material files)
  - __Models__    (models used on the level)
  - __Prefabs__   (prefabs used on the level) 
  - __Scenes__    (the game levels including a license text file)
  - __Sounds__    (sound files used on the level)
  - __Scripts__   (scripts used on the level)
  - __Sprites__   (sprites used on the level)
  - __Additional assets__ (as a separate folder including all assets necessary to the scenario to work)

Example:

    //EMICVL_<GROUP_NAME>|
                         |[AdditionalAsset (AssetName)]
                         |[Animation]
                         |[Materials]
                         |[Models]
                         |[Prefabs]
                         |[Scenes]
                         |[Scripts]
                         |[Sound]
                         |[Sprites]
                         |[Textures]
              
7.  All __extra content__ should be __removed__ from the level project (textures, code, models, etc.)

8. If an avatar has some distinctive features different from the standard, this should be mentioned in in-line file. It is recommended to use standard avatar from the first-person point of view taken from the standard asset without any addons.

9. __IN CASE IF LEVEL PROJECT AUTHORS USE THE STANDARD AVATAR FROM THE STANDARD UNITY ASSET, THEY SHOULD PROVIDE FOR ASSEMBLING TWO VERSIONS OF PROJECT LEVEL: ONE WITH AN AVATAR AND THE OTHER ONE WITHOUT AN AVATAR. ALL CONTENT OF THE STANDARD UNITY ASSET SHOULD BE REMOVED FROM THE VERSION “WITHOUT AN AVATAR”. STANDARD ASSET IS ALREADY PRESENT IN THE CORE OF JOINT PROJECT__

10.  Restructured project level should be tested by the developers themselves to be fully working. Assembling group will not be held liable for the non-working level uploaded and assembled, as the core of joint project is organized, as this needed for the direct level upload.

11. Restructured and fully working project level should be provided to the EMICVL project experts to be approved for final assembling.

12. The dead line to provide the final version of level projects to the experts is 5th November.

13. The licences should accompany every level project and should be provided to the experts not later then 5th November. In order to be part of the packages as [Text Asset](http://docs.unity3d.com/Manual/class-TextAsset.html) , save it as a License.txt, then drag and drop inside the Assets/Scene folder in Unity and selected it while creating the export.

14. Level projects, approved by experts should be sent to ONU team for final assembling not later then 9th November.

15. The exported package shall not have any dependency from external programs other than Unity 3D (Blender for example). To achieve this, please test import from a clean computer with just Unity 3D installed.

16. Each team assets should have a __UNIQUE__ identifier, in order to __AVOID NAME CONFLICTS__. Every asset should have the team acronymous as asset name prefix, including ojects, script, texture, etc.... Example: _ONU_table.fbx, AMU_table.dae, BSU_input.cs_ 
