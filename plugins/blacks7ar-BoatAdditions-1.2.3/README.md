# <b># BoatAdditions</b>

Adds 3 small and 3 new large boats with anchors and lamps and a boatyard that can help you on your journey.
<br/>

![](https://i.ibb.co/3TBx1nj/ss5.png)
![](https://i.ibb.co/MsY0jsW/ss4.png)

>## ## Installation (manual)

- extract `BoatAdditions.dll` file to your `BepInEx\Plugins\` folder.

<br/>

>## ## Features

- Adds anchor function to vanilla boats.
- Adds 3 new small boat called Outrigger Karve, Large Raft and Canoe.
- Adds 3 new large boats called Outrigger Skeid, Snekkja and Knarr.
- Each boat has its own lamp that can help you navigate at night.
- Each boat has its own anchors, if you logout while boats are still anchored, if you log back in they will still be anchored.
- Configurable recipe and boat stats.
- Adds a new crafting station called Boatyard, you can use this new crafting station to craft parts of boats which then you can use to build your boats.
- Customizable storage sizes (NOTE: NEVER change the size of the storages if it has items inside, remove items first before changing.)
- Uses ServerSync and built-in ConfigWatcher
- Configurable through config file or [Configuration Manager](https://valheim.thunderstore.io/package/Azumatt/Official_BepInEx_ConfigurationManager/)

<br/>

>## ## How to use anchors
- Hover your mouse to the rudder (ship control)
- Then press the corresponding hotkey (default: Shift+F) to drop/raise the anchor (configurable)

>## ## Changelog
<br/>

v1.2.3
- as requested added config option for boats storage size, you can now customize boats storage sizes (Needs a logout to take effect).
- NOTE: NEVER change the size of the storages if it has items inside, remove items first before changing.

<details>
<summary><b>Changelog History</b> (<i>click to expand</i>)</summary>
<br/>

v1.2.2
- updated to the latest valheim build (217.28)
- updated serversync and dependencies
- updated manifests bepinex dependency string

v1.2.1
- added toggle option to disable boatyard.
- put localization example to a zip package to avoid unnecessary duplicates.

v1.2.0
- fixed minor translation issues
- added toggle option to enable/disable my custom sail (blacks7ar logo)

v1.1.9
- fixed multiplayer version check issues

v1.1.8
- updated to the latest valheim build (217.22)
- added spanish translation

v1.1.7
- removed anchor hotkey from being synced and locked so players can have their own key configuration.

v1.1.6
- removed item manager and piece manager.
- added config option to disable item recipes.
- added config option to customized boat stats (ie. ships speed etc.)
- added german translations (thanks to @BLUBBSON & @icemansparks)

v1.1.5
- updated to the latest valheim build (217.14) hilders request.

v1.1.4
- fixed outrigger karves collider (when damage and broken).

v1.1.3
- fixed icons visual glitch.

v1.1.2
- removed boatyards terrain modifier so it can be built on wooden/stone/marble floors

v1.1.1
- fixed boatyard bug where you can build it on top of a tree.

v1.1.0
- added a new crafting station called boatyard which you can use to craft boat parts which then you can use as materials to build your boats.
- added 3 new craftable materials use to build boats.
- added a new small boat called canoe good for traversing rivers.
- added a new large boat called knarr (norse merchant ship) which is way bigger than the longship or snekkja good for transporting lots of goods.

v1.0.8
- fixed outrigger karve's colliders that prevents the boat from moving on shallow waters.
- fixed outrigger skeid's onboard collider

v1.0.7
- as requested added anchor function to vanilla boats

v1.0.6
- fixed an NRE cause by newly created boats when the mod is just added
- changed anchor hotkey to a combination hotkey (from Y to Shift-F) (configurable)

v1.0.5
- as requested added anchor feature for each boat

v1.0.4
- fixed double outrigger karve storage bug
- changed double outrigger karve name to outrigger karve

v1.0.3
- as requested all lamps now gives fire buff with a small range

v1.0.2
- added large raft which is bigger than vanilla raft, has its own Lamp and small storage
- fixed outrigger skeid and snekkja's water impact effect
- adjusted snekkja's speed a bit to match outrigger skeid's speed

v1.0.1
- reduce build requirements to only use 5 materials instead of 7
- fixed index out of bounds error by having too many requirements
- (huge shoutout @Majestic for the feedback, as always thank you very much.. i swear i tested it with 7 requirements and got no error.. thats weird xD)

v1.0.0
- first release

</details>

