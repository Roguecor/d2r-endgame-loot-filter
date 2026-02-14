# Endgame v1.3.3 Loot Filter

## Instructions

* Load into a game, press ESC and select Loot Filter
* Click the down arrow button to import the filter
* Copy the contents of filter.json
* Then in game, click Copy from Clipboard
* Save
* Select the filter from the dropdown

### Change Log
*   [Changelog](CHANGELOG.md)

---

## Suggestions for filtering
- In Keybinds
* Bind "Message Log" to Shift+M
*  Bind "Show Items" to L
*  Bind "Show Items (Unfiltered) to Alt
*  
- In Gameplay
* Set Show Items to Toggle
* Set Show Items (Unfiltered) to Hold

---

# Filter (translated, formatting will be improved)

```json
{
  "name": "Endgame v1.3.3",
  "rules": [
    {
      "name": "00. Hide All",
      "enabled": true,
      "ruleType": "hide",
      "filterEtherealSocketed": true,
      "equipmentRarity": [
        "rare",
        "lowQuality",
        "magic",
        "set",
        "unique",
        "hiQuality",
        "normal"
      ],
      "equipmentQuality": [
        "normal",
        "exceptional",
        "elite"
      ],
      "equipmentCategory": [
        "acce",
        "armo",
        "weap"
      ],
      "itemCategory": [
        "misc"
      ],
      "goldFilterValue": 100000
    },
    {
      "name": "a1. Items",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "itemCategory": [
        "uberm",
        "runes",
        "terrt",
        "absol"
      ],
      "itemCode": [
        "Perfect Diamond (gpw)",
        "Perfect Sapphire (gpb)",
        "Flawless Saphire (glb)",
        "Flawless Diamond (glw)",
        "Flawless Emerald (glg)",
        "Chipped Saphire (gcb)",
        "Chipped Amethyst (gcv)",
        "Perfect Emerald (gpg)",
        "Perfect Skull (skz)",
        "Flawless Skull (skl)",
        "Flawless Amethyst (gzv)",
        "Chipped Topaz (gcy)",
        "Perfect Ruby (gpr)",
        "Perfect Topaz (gpy)",
        "Flawless Topaz (gly)",
        "Chipped Diamond (gcw)",
        "Chipped Skull (skc)",
        "Chipped Ruby (gcr)",
        "Chipped Emerald (gcg)",
        "Perfect Amethyst (gpv)",
        "Flawless Ruby (glr)"
      ]
    },
    {
      "name": "a2. Gold",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "goldFilterValue": 5000
    },
    {
      "name": "a3. Ammo",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "itemCategory": [
        "ammo"
      ]
    },
    {
      "name": "a4. Rejuvenation Potions",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "itemCode": [
        "Rejuv Potion (rvs)",
        "Full Rejuv Potion (rvl)"
      ]
    },
    {
      "name": "a5. Super Potions",
      "enabled": false,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "itemCode": [
        "Super Mana Potion (mp5)",
        "Super Healing Potion (hp5)"
      ]
    },
    {
      "name": "b1. Uniques",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentRarity": [
        "unique"
      ]
    },
    {
      "name": "b2. Sets",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentRarity": [
        "set"
      ]
    },
    {
      "name": "b3. Rare All Class Equipment",
      "enabled": false,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentRarity": [
        "rare"
      ],
      "equipmentCategory": [
        "sorce",
        "amazo",
        "palad",
        "druid",
        "warlo",
        "necro",
        "barbh",
        "assas"
      ]
    },
    {
      "name": "c1. Charms",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentCategory": [
        "charm"
      ]
    },
    {
      "name": "c2. Jewels",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentCategory": [
        "jewel"
      ]
    },
    {
      "name": "d1. Base Armors",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": true,
      "equipmentRarity": [
        "hiQuality",
        "normal"
      ],
      "equipmentItemCode": [
        "Troll Nest (ush)",
        "Hunter’s Guise (dr8)",
        "Earth Spirit (drd)",
        "Mummified Trphy (ne6)",
        "Lion Helm (ba7)",
        "Savage Helmet (ba9)",
        "Alpha Helm (dr6)",
        "Sky Spirit (dre)",
        "Mage Plate (xtp)",
        "Corona (urn)",
        "Slayer Guard (baa)",
        "Sacred Feathers (dr9)",
        "Sacred Targe (pab)",
        "wab",
        "Rage Mask (ba8)",
        "Cantor Trophy (ne9)",
        "Spired Helm (uhm)",
        "Totemic Mask (dra)",
        "waa",
        "Demonhead (usk)",
        "wa9",
        "wa6",
        "Griffon Headress (dr7)",
        "Fury Visor (bac)",
        "Sexton Trophy (ne8)",
        "Heirophant Trphy (nea)",
        "Tiara (ci2)",
        "Guardian Crown (baf)",
        "Great Hauberk (urs)",
        "Overseer Skull (ned)",
        "Succubae Skull (nee)",
        "wac",
        "Destroyer Helm (bad)",
        "Archon Plate (utp)",
        "Dusk Shroud (uui)",
        "wae",
        "wa8",
        "Dream Spirit (drf)",
        "Scarab Husk (ula)",
        "wa7",
        "waf",
        "Diadem (ci3)",
        "Bloodlord Skull (nef)",
        "Jawbone Visor (ba6)",
        "Sacred Armor (uar)",
        "Conqueror Crown (bae)",
        "Monarch (uit)",
        "Fetish Trophy (ne7)",
        "Blood Spirit (drb)",
        "Bone Visage (uh9)",
        "Minion Skull (neb)",
        "neg",
        "Carnage Helm (bab)",
        "Vortex Shield (paf)",
        "wad",
        "Sun Spirit (drc)",
        "Wire Fleece (utu)",
        "Wyrmhide (uea)"
      ]
    },
    {
      "name": "d2. Base Weapons",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": true,
      "equipmentRarity": [
        "hiQuality",
        "normal"
      ],
      "equipmentItemCode": [
        "Lich Wand (7bw)",
        "Scythe (scy)",
        "Seraph Rod (7qs)",
        "Decapitator (7bt)",
        "Giant Thresher (7wc)",
        "Holy Water Spri (9qs)",
        "Hydra Bow (6lw)",
        "Thresher (7s8)",
        "Berserker Axe (7wa)",
        "Burnt Wand (9wn)",
        "Cryptic Axe (7pa)",
        "9tw",
        "Grnd Matron Bow (amc)",
        "Ghost Wand (7yw)",
        "Greater Claws (9lw)",
        "Matriarchal Bow (amb)",
        "Mighty Sceptre (7sc)",
        "Colossus Blade (7gd)",
        "Suwayyah (7ar)",
        "Unearthed Wand (7gw)",
        "Tomb Wand (9bw)",
        "Grave Wand (9gw)",
        "Ettin Axe (72a)",
        "Fanged Knife (7kr)",
        "Balrog Blade (7gs)",
        "Rune Sceptre (9sc)",
        "Petrified Wand (9yw)",
        "Feral Claws (7lw)",
        "Polished Wand (7wn)",
        "Colossal Sword (7fb)",
        "Cinquedeas (9kr)",
        "Divine Sceptre (9ws)",
        "7tw",
        "Phase Blade (7cr)",
        "Thunder Maul (7gm)",
        "Colossus Voulge (7vo)",
        "Caduceus (7ws)",
        "Crystal Sword (crs)",
        "Archon Staff (6ws)",
        "Great Poleaxe (7h7)"
      ]
    },
    {
      "name": "e1. Magic Rings and Amulets",
      "enabled": false,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentRarity": [
        "magic"
      ],
      "equipmentCategory": [
        "rings",
        "amule"
      ]
    },
    {
      "name": "e2. Magic High Value Equpment",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentRarity": [
        "magic"
      ],
      "equipmentCategory": [
        "wands",
        "circl"
      ],
      "equipmentItemCode": [
        "Earth Spirit (drd)",
        "Hunter’s Guise (dr8)",
        "Maiden Javelin (am5)",
        "Heavenly Stone (obb)",
        "Lion Helm (ba7)",
        "Leather Gloves (lgl)",
        "wab",
        "Winged Knife (7bk)",
        "Light Gauntlets (tgl)",
        "wa9",
        "wa6",
        "Ceremonial Jav (ama)",
        "Griffon Headress (dr7)",
        "Heirophant Trphy (nea)",
        "Destroyer Helm (bad)",
        "Crystalline Glb (ob7)",
        "Dusk Shroud (uui)",
        "Dream Spirit (drf)",
        "Heavy Gloves (vgl)",
        "Bloodlord Skull (nef)",
        "Vampirebone Gl (uvg)",
        "Bramble Mitts (ulg)",
        "Heavy Bracers (xmg)",
        "Eldritch Orb (obc)",
        "Feral Claws (7lw)",
        "Monarch (uit)",
        "Vambraces (umg)",
        "Fetish Trophy (ne7)",
        "Minion Skull (neb)",
        "7tw",
        "Demonhide Glove (xlg)",
        "Wire Fleece (utu)",
        "Wyrmhide (uea)",
        "Vortex Orb (obe)",
        "Mummified Trphy (ne6)",
        "Demon Heart (obd)",
        "Savage Helmet (ba9)",
        "Alpha Helm (dr6)",
        "Flying Axe (7ta)",
        "Swirling Crystl (oba)",
        "Sky Spirit (dre)",
        "9tw",
        "Slayer Guard (baa)",
        "Sacred Feathers (dr9)",
        "Rage Mask (ba8)",
        "Cantor Trophy (ne9)",
        "Battle Gauntlet (xtg)",
        "Totemic Mask (dra)",
        "waa",
        "Greater Claws (9lw)",
        "Fury Visor (bac)",
        "Matriarchal Jav (amf)",
        "Sexton Trophy (ne8)",
        "Suwayyah (7ar)",
        "Guardian Crown (baf)",
        "Glowing Orb (ob6)",
        "Overseer Skull (ned)",
        "Dimensional Shrd (obf)",
        "Cloudy Sphere (ob8)",
        "Great Hauberk (urs)",
        "Succubae Skull (nee)",
        "wac",
        "Archon Plate (utp)",
        "wae",
        "wa8",
        "wa7",
        "Scarab Husk (ula)",
        "waf",
        "Jawbone Visor (ba6)",
        "Conqueror Crown (bae)",
        "Chain Gloves (mgl)",
        "Sharkskin Glove (xvg)",
        "Blood Spirit (drb)",
        "Crusader Gaunt (utg)",
        "neg",
        "Sparkling Ball (ob9)",
        "Carnage Helm (bab)",
        "wad",
        "Sun Spirit (drc)"
      ]
    },
    {
      "name": "f1. Rare Rings and Amulets",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentRarity": [
        "rare"
      ],
      "equipmentCategory": [
        "rings",
        "amule"
      ]
    },
    {
      "name": "f2. Rare High Value Equipment",
      "enabled": true,
      "ruleType": "show",
      "filterEtherealSocketed": false,
      "equipmentRarity": [
        "rare"
      ],
      "equipmentCategory": [
        "glove",
        "necro",
        "warlo",
        "barbh",
        "belts",
        "wands",
        "druid",
        "boots",
        "circl"
      ],
      "equipmentItemCode": [
        "Vortex Orb (obe)",
        "Maiden Javelin (am5)",
        "Heavenly Stone (obb)",
        "Demon Heart (obd)",
        "Swirling Crystl (oba)",
        "9tw",
        "Berserker Axe (7wa)",
        "Winged Knife (7bk)",
        "Greater Claws (9lw)",
        "Flying Knife (7tk)",
        "Matriarchal Jav (amf)",
        "Ceremonial Jav (ama)",
        "Suwayyah (7ar)",
        "Colossus Blade (7gd)",
        "Glowing Orb (ob6)",
        "Dimensional Shrd (obf)",
        "Cloudy Sphere (ob8)",
        "Ettin Axe (72a)",
        "Crystalline Glb (ob7)",
        "Fanged Knife (7kr)",
        "Balrog Blade (7gs)",
        "Dimensional Bld (9cr)",
        "Eldritch Orb (obc)",
        "Feral Claws (7lw)",
        "Colossal Sword (7fb)",
        "Cinquedeas (9kr)",
        "Sparkling Ball (ob9)",
        "7tw",
        "Phase Blade (7cr)",
        "Thunder Maul (7gm)",
        "Crystal Sword (crs)"
      ]
    }
  ]
}
```
