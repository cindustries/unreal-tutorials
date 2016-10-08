# 01 - MakeHuman

![alt text](01-MakeHumanToUE.jpg "Screenshot")

## 01.1

Select Tab "Pose/Animate"


## 01.2

In "Pose/Animate": Select Tab "Skeleton"


## 01.3

Select Rig Preset "Game Engine"


# 02 - MakeHuman

![alt text](02-MakeHumanToUE.jpg "Screenshot")

## 02.1

Select Tab "Files"


## 02.2

In "Files": Select Tab "Export"


## 02.3

Select Mesh Format: Filmbox (fbx)


## 02.4

Select Scale Unit: centimeter


## 02.5

Click "Export"


# 03 - Unreal Engine

![alt text](03-MakeHumanToUE.jpg "Screenshot")

## 03.1

On source file change detection: Click "Import" (in upcoming Window "Import all")


# 04 - Unreal Engine

![alt text](04-MakeHumanToUE.jpg "Screenshot")

## 04.1

Open imported Skeletal Mesh


# 05 - Unreal Engine

![alt text](05-MakeHumanToUE.jpg "Screenshot")

## 05.1

Open Skeleton Editor


## 05.2

Click "Retarget Manager"


# 06 - Unreal Engine

![alt text](06-MakeHumanToUE.jpg "Screenshot")

## 06.1

Open Drop Down "Select Rig"


## 06.2

Select "Select Humanoid Rig"


# 07 - Unreal Engine

![alt text](07-MakeHumanToUE.jpg "Screenshot")

## 07.1

Click "Save Pose" (Bones from MH are named same as the ones in UE => no change needed)

# 08 - Unreal Engine

![alt text](08-MakeHumanToUE.jpg "Screenshot")

## 08.1

Open Animation you want to retarget


# 09 - Unreal Engine

![alt text](09-MakeHumanToUE.jpg "Screenshot")

## 09.1

Open Skeleton Editor


## 09.2

Click "Retarget Manager"


# 10 - Unreal Engine

![alt text](10-MakeHumanToUE.jpg "Screenshot")

## 10.1

Open Drop Down "Select Rig"


## 10.2

Select "Select Humanoid Rig"


# 11 - Unreal Engine

![alt text](11-MakeHumanToUE.jpg "Screenshot")

## 11.1

Click "Save Pose"


# 12 - Unreal Engine

![alt text](12-MakeHumanToUE.jpg "Screenshot")

## 12.1 

Right Click Animation you want to retarget


## 12.2

Select "Retarget Anim Asset" => "Duplicate Anmim Assets and Retarget"


# 13 - Unreal Engine

![alt text](13-MakeHumanToUE.jpg "Screenshot")

## 13.1

Select your target Skeleton


## 13.2

Click "Retarget"


# 14 - Unreal Engine

![alt text](14-MakeHumanToUE.jpg "Screenshot")

## 14.1

Open the new Anim Asset next to your target Skeleton


# 15 - Unreal Engine

![alt text](15-MakeHumanToUE.jpg "Screenshot")

There might be Glitches in the Animation. To fix them:

# 16 - Unreal Engine

![alt text](16-MakeHumanToUE.jpg "Screenshot")

## 16.1 

Open Skeleton Editor


## 16.2

Make sure Box next to "Show Advanced Options" is checked


## 16.3

Right click the "Root" bone of your Skeleton (or the broken one itself if you want to go step by step)


## 16.4

Click "Recursively Set Translation Retargeting Skeleton" in upcoming menu


# 17 - Unreal Engine

![alt text](17-MakeHumanToUE.jpg "Screenshot")

The final result without Glitches



