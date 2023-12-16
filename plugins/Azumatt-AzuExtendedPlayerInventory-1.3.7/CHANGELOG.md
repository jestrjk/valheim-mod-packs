| `Version` | `Update Notes`                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1.3.7     | - When you had something like EpicLoot that used custom properties on items, it wasn't properly copying that information for the items in the quickslots (not gear slots, those were fine). That's just not Epic. Well, it's now Epic again as I have fixed the issue. Additionally added some checks for when your inventory is full, just in case you're an overweight Viking.                                                                                                                                           |
| 1.3.6     | - Equipment and Quickslots seamless migration code added. Please see the **_Migration from Equipment And Quickslots_** section for more information.<br/> - Remove hash checking on server connection to speed up connection. AzuAnticheat can handle that instead<br/> - Fix possible issues when using AzuContainerSizes<br/> - Update APIManager <br/> - Other shit I can't remember.                                                                                                                                   |
| 1.3.5     | - Recompile for Valheim 0.217.29 and update APIManager internally.                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 1.3.4     | - Fix for JC Synergy window                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| 1.3.3     | - Ghost slots fixed for when equipping items that would make the row size incorrectly. (thanks Blaxxun)                                                                                                                                                                                                                                                                                                                                                                                                                    |
| 1.3.2     | - Update the API to have the quickslots items exposed for easy access for mods like QuickStackStore. This should allow mods like that to ignore your quickslots easier when you use their auto depositing features.<br/> - Update ServerSync internally                                                                                                                                                                                                                                                                    |
| 1.3.1     | - Expose the funcs in the API for better identification of slots<br/> - Blaxxun's fix for Backpacks closing the UI                                                                                                                                                                                                                                                                                                                                                                                                         |
| 1.3.0     | - Update to allow custom slots. Added an API for the mod. Jewelcrafting now has dedicated slots using this API<br/>- Inventory can now be live updated with the configuration manager without issue<br/> - Code has been moved to a new repository and made public.<br/> - `A huge and special thank you to Blaxxun for working with me on this update.`                                                                                                                                                                   |
| 1.2.4     | - I was tagged in a bug about my shit throwing an error when your inventory was full but your armor breaks. This should fix that issue. If not, let me know I was a dumbass.                                                                                                                                                                                                                                                                                                                                               |
| 1.2.3     | - Update for Valheim latest version.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| 1.2.2     | - Fix some issues with WeightBase compatibility                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| 1.2.1     | - Hildir's Request                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 1.2.0     | - Change some true/false settings to On/Off instead `Regenerate your config file! (you do this by deleting the configuration file and rebooting the game with the mod, so that the file recreates itself based on defaults)`<br/> - Quickslots and display seperate are on by default now. Turns off quickslots if you install RandyKnapps EAQs mod automatically.<br/> - Accept a pull request from Blaxxun that fixes an issue with Backpacks new code.                                                                  |
| 1.1.9     | - Updated for Hildir's Request 0.217.5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 1.1.8     | - Updated for Valheim 0.216.9                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| 1.0.8     | - Fix an issue with the vanilla UI that I created.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 1.0.7     | - Remove my testing code, packaged the wrong DLL,<br/>WHOOPS :D                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| 1.0.6     | - Force disable the quiver in BetterArchery if you have it enabled. A warning will prompt in the logs/console window. Just as that mod's configuration states...you will lose all your arrows in the quiver. Head the warning young padawan.<br/> - Fix overlapping the weight when MinimalUI is installed.                                                                                                                                                                                                                |
| 1.0.5     | - Fix an issue that could occur when attempting to remove broken items from the inventory and add them back. Though the action performed it's job, it could sometimes throw an error to the console.                                                                                                                                                                                                                                                                                                                       |
| 1.0.4     | - Seems some people were having issues on 0.214.2 of the game. I didn't see any, but here is a version compiled against it just in case.                                                                                                                                                                                                                                                                                                                                                                                   |
| 1.0.3     | - Fix a compatibility issue with Cheb's Necromancy which would cause this mod to throw errors. He still needs to fix his code.                                                                                                                                                                                                                                                                                                                                                                                             |
| 1.0.2     | - Use a Keyboard Shortcut fix from Margmas to allow you to walk and use your quickslot keys at the same time. We live in the future now! BepInEx should really handle this better and not need this workaround.                                                                                                                                                                                                                                                                                                            |
| 1.0.1     | - Update to add forgotten chest UI dragging<br/>- Changed the config file a lot. `YOU WILL NEED TO REGENERATE YOUR CONFIG FILE` to make it work properly<br/>- Add command `azuepi fix` to fix your inventory manually if there are issues<br/>- Implement inventory Auto fixer that will attempt to fix your inventory if something is wrong by opening and closing your inventory. Will also run once after "Take All" is used on a chest, just in case. Uses vanilla methods to do this, and shouldn't cause item loss. |
| 1.0.0     | Initial Release                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |