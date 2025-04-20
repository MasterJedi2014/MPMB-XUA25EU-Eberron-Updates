# MPMB XUA25EU "Eberron Updates"
This script adds the Artificer & its subclasses from both the 2024 *Unearthed Arcana: The Artificer* article, as well as the Cartographer subclass for the Artificer and the Dragonmark Feats from the *Unearthed Arcana: Eberron Updates* article.

**This script is to be used in conjunction with the 5.24E scripts by ThePokésimmer. It will not work properly without those installed first. You can find those scripts here: https://github.com/thepokesimmer/2024-PHB/tree/main This script supersedes (and is therefore incompatible with) my previous UA Artificer script.**

**Script Credit Note:**
This file has been compiled by MasterJedi2014, though the bones of the script are based on the code from MPMB and those who have contributed to the sheet's existing material in the "all_WotC_pub+UA" script. I am also using code within the script written by the users Shroo, ThePokésimmer, & TrackAtNite. The only things in this script that I can currently take credit for are:
- Alterations made to address changes made by the UA;
- Converting the Homunculus Servant infusion into a spell, along with the needed `CompanionList` & `CreatureList` entries.
- The non-spell granting aspects of the Dragonmark Feats.

This script will allow users to more easily playtest the revised Artificer & Eberron content. It also includes options to re-enable some aspects of the 2019/2020 Artificer that might be needed for an existing character to function.

**Script Patch Notes:**
- **2025-03-01:**
  - Initial upload of script (V2).
- **2025-03-16:**
  - V2 superseded by V7. All of the Dragonmark Feats have been added aside from the Epic Boon *Boon of Siberys*.
- **2025-03-30:**
  - V7 superseded by V8. All of the Greater Dragonmark Feats have had custom `description` attributes added for each ASI choice. The Epic Boon *Boon of Siberys* has been added with coding advice from Joost/MPMB.
- **2025-03-31:**
  - V8 minor update to fix the "Force Strike" attacks within the "Homunculus Servant" `CreatureList` objects.
- **2025-04-03:**
  - V8 minor update to correct an error casued by a missing comma.
- **2025-04-04:**
  - V8 minor update: Reworded the Armorer's Dreadnaught description & the base class' "Replicate Magic Item" feature (rewording provided by user Nod). User Nod also notified me that the "Magical Tinkering" class feature had its name changed to "Tinker's Magic"; As a result, the `AddFeatureChoice` option to bring back the 2019/2020 functions of the "Magical Tinkering" class feature was renamed to match the new name. Added the missing *Mending* cantrip to the "Tinker's Magic" class feature. Combined the 2 Bonus Actions of the "Magic Item Tinker" class feature into a single line to save on space.
- **2025-04-14:**
  - V8 superseded by V9. "Replicate Magic Item" code updated to fix most known issues related to the feature. Updated code at the end of the script to ensure that the "Replicate Magic Item" menus don't disappear upon a PDF save and reload. All credit for this update goes to user TrackAtNite.
- **2025-04-20:**
  - V9 superseded by V10. "Replicate Magic Item" code updated again to fix remaining known issues related to the feature. Cleaned up code at the end of the script to ensure that the "Replicate Magic Item" menus don't disappear upon a PDF save and reload. All credit for this update again goes to user TrackAtNite.

**Known Bugs:**
- ~~V8: Homunculus Servants are not displaying their correct Attack & Damage Modifiers for their Force Strike attacks.~~
- ~~V8: +2 Armor, Shield, Wand of the War Mage, Weapon, & Wraps of Unarmed Power don't appear in their correct menus.~~
- ~~V8: The level 10 "Replicate Magic Item" options are being addd to the level 6 options immediately upon the character attaining level 6.~~

**XUA24A Content Source:**
- https://media.dndbeyond.com/compendium-images/ua/the-artificer/AzQEA72K8EMf9HmU/UA2024-Artificer.pdf

**XUA25EU Content Source:**
- https://media.dndbeyond.com/compendium-images/ua/eberron-updates/Lhg25Ggx5iY3rETH/UA2025-CartographerArtificer.pdf

For instructions on how to add this script to the sheet, please see this page: https://www.flapkan.com/how-to/add-more-content
