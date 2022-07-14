# RGDoorLocks

**Version**: 0.1: 13 July 22

**Author:** RatherGood1

[![RGDoorLocks](media/MMOKITModDoorLocks.png)](https://youtu.be/67cGFSlzw0U)


**Description:** 

 Door unlock with keys MMORPG Kit

 Example code for USUPPORTED MOD use at your own risk. Not a complete or working project by itself.

 Working demo scene included.

 Chest/container not working!

 **Compatibility:** Tested on Suriyun MMORPG Kit Version  1.76d2 - July 13, 2022 and Unity 2021.3.6f1
 
**Credits** 

Bonus future credit to the person who gets the chest/container working same as the door. Currently conainers are only usable to the player who places them. 

**Example code**

* "PickUpItem" key changed to "E" from "F" by request on Input settings manager.
Open the "00Init_Shooter_DoorLockRG" and look at the example.
* "DoorKeyLock" placed on doorEntity will set password of door to the Key Item Title (items title is the UNIQUE file name as per MMOKIT convention)
* Set the key item to the item that unlcks the door (can be any item really)
* Use the door events to trigger sounds lock/unlock or open/close.
* Custom ShooterController replaces the "ActivateBuilding" with a new one that checks if player has the key in their inventory.
* Custom Gameplay Canvas replaces UITargetBuilding to display information about the key needed to open a door. See:  "UIDamageableEntity_RGDoorStorageInfo" on GameplayCanvas.


