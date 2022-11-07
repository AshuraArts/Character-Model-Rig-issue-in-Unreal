# Character-Model-Rig-issue-in-Unreal
Character Model Rig issue in Unreal
For a project I'm working on i downloaded a model from The Models Resource of Mythra from Smash Bros Ultimate, This character came with a complex rig which was too much to work with for my Current project. 
  
Link to the model: https://www.models-resource.com/nintendo_switch/supersmashbrosultimate/model/40261/

To work around this i deleted the rig and exported the standard UE4 skeleton and put it on the character model in Maya.![Mythra_Skeleton](https://user-images.githubusercontent.com/117665909/200357802-80361189-6ca3-43c7-875a-e66480abb048.png)


Once this was done i exported the charcter as an FBX file and it worked fine in mixamo however when i tried putting the character into UE4 with the standard skeleton everything would work except a single arm that would break and distort.![import setting](https://user-images.githubusercontent.com/117665909/200357853-7c71d499-23ac-4b91-a48a-97dd738cf74e.png)

Character Posed using Mixamo: ![12](https://user-images.githubusercontent.com/117665909/200358085-b938b93f-6687-4f58-a849-1324cec5aac5.jpg)


When Imported an error would appear but im unsure why as i used the exact UE4 skeleton![error](https://user-images.githubusercontent.com/117665909/200357973-7daff8fc-5900-4147-8413-35f694fa8132.png)


However what really confuses me is it breaks the actually skeleton in unreal as even the standard mannequin will distort in the same way after the model has been imported to the file.![Ue broken skeleton](https://user-images.githubusercontent.com/117665909/200357542-ea96fb35-76f1-44ff-b24f-63a011bed5fd.png)

Heres a video of how the character functions in UE4 on top of the standard skeleton: https://www.youtube.com/watch?v=Q10cMoGeCvA

The File for the character model with the unreal skeleton i rigged to it is also in this Github
