# mcMMO Party Information

#I'm going to try to normalize our locale file, forgive the mess for now.

#DO NOT USE COLOR CODES IN THE JSON KEYS
#COLORS ARE DEFINED IN advanced.yml IF YOU WISH TO CHANGE THEM
## JSON Rank
`Rank`
## JSON DescriptionHeader
`Description`
## JSON JWrapper Header
`Details`
## JSON Type Passive
`Passive`
## JSON Type Active
`Active`
## JSON Type SuperAbility
`Super Ability`
## JSON Locked
`-=[LOCKED]=-`
## JSON LevelRequirement
`Level Requirement`
## JSON JWrapper Target Type
`Target Type:`
## JSON JWrapper Target Block
`Block`
## JSON JWrapper Target Player
`Player`
## JSON JWrapper Perks Header
`&6Lucky Perks`
## JSON JWrapper Perks Lucky
`{0}% Better Odds`
## JSON Hover Tips
`Tips`
## JSON Acrobatics
`Acrobatics`
## JSON Alchemy
`Alchemy`
## JSON Archery
`Archery`
## JSON Axes
`Axes`
## JSON Excavation
`Excavation`
## JSON Fishing
`Fishing`
## JSON Herbalism
`Herbalism`
## JSON Mining
`Mining`
## JSON Repair
`Repair`
## JSON Salvage
`Salvage`
## JSON Swords
`Swords`
## JSON Taming
`Taming`
## JSON Unarmed
`Unarmed`
## JSON Woodcutting
`Woodcutting`
## JSON URL Website
`The official mcMMO Website!`
## JSON URL Discord
`The official mcMMO Discord server!`
## JSON URL Patreon
`Support nossr50 and his work for mcMMO on Patreon!`
## JSON URL Spigot
`The official mcMMO Spigot Resource Page!`
## JSON URL Translation
`Translate mcMMO into other languages!`
## JSON URL Wiki
`The official mcMMO wiki!`
## JSON SkillUnlockMessage
`&6[ mcMMO&e @&3{0} &6Rank &3{1}&6 Unlocked! ]`
## JSON Hover Rank
`&e&lRank:&r &f{0}`
## JSON Hover NextRank
`&7&oNext upgrade at level {0}`
# for JSON.Hover.Mystery you can add {0} to insert the level required into the name, I don't like how that looks so I'm not doing that atm
## JSON Hover Mystery
`&7???`
## JSON Hover Mystery2
`&e[&8{0}&e]&8???&r`
## JSON Hover SkillName
`&3{0}&r`
## JSON Hover SuperAbility
`&5{0}&r`
## JSON Hover MaxRankSkillName
`&6{0}&r`
## JSON Hover AtSymbolSkills
`&e@`
## JSON Hover AtSymbolURL
`&e@`

#This is the message sent to players when an ability is activated
## JSON Notification SuperAbility
`{0}`

#These are the JSON Strings used for SubSkills
## JSON.Acrobatics Roll Interaction Activated
`Test &cRolled Test`
## JSON.Acrobatics.SubSkill Roll Details Tips
`If you hold sneak while falling you can prevent up to twice the damage that you would normally take!`
## Anvil SingleItemStack
`&cYou cannot salvage or repair item stacks that have more than one item, split the stack first.`

#DO NOT USE COLOR CODES IN THE JSON KEYS
#COLORS ARE DEFINED IN advanced.yml IF YOU WISH TO CHANGE THEM

## mcMMO Template Prefix
`&6(&amcMMO&6) &7{0}`
# BEGIN STYLING
## Ability Generic Refresh
`&a**ABILITIES REFRESHED!**`
## Ability Generic Template Lock
`&7{0}`
# Skill Command Styling
## Ability Generic Template
`&3{0}: &a{1}`
## Ability Generic Template Custom
`&3{0}`
## Skills Overhaul Header
`&c[]=====[]&a {0} &c[]=====[]`
## Effects Effects
`EFFECTS`
## Effects SubSkills Overhaul
`Sub-Skills`
## Effects Child Overhaul
`&3Child Lv.&e {0}&3: {1}`
## Effects Child ParentList
`&a{0}&6(&3Lv.&e{1}&6)`
## Effects Level Overhaul
`&6LVL: &e{0} &3XP&e(&6{1}&e/&6{2}&e)`
## Effects Parent
`&6{0} -`
## Effects Template
`&3{0}: &a{1}`
## Commands Stats Self Overhaul
`Stats`
## Commands XPGain Overhaul
`&6XP GAIN: &3{0}`
## MOTD Version Overhaul
`&6[mcMMO] &3Overhaul Era&6 - &3{0}`
## Overhaul mcMMO Header
`&c[]=====[]&a mcMMO - Overhaul Era &c[]=====[]`
## Overhaul.mcMMO Url Wrap Prefix
`&c[|`
## Overhaul.mcMMO Url Wrap Suffix
`&c|]`
## Overhaul mcMMO MmoInfo Wiki
`&e[&fView this skill on the wiki!&e]`
# Overhaul.Levelup can take {0} - Skill Name defined in Overhaul.Name {1} - Amount of levels gained {2} - Level in skill
## Overhaul Levelup
`&l{0} increased to &r&a&l{2}&r&f.`
## Overhaul Name Acrobatics
`Acrobatics`
## Overhaul Name Alchemy
`Alchemy`
## Overhaul Name Archery
`Archery`
## Overhaul Name Axes
`Axes`
## Overhaul Name Excavation
`Excavation`
## Overhaul Name Fishing
`Fishing`
## Overhaul Name Herbalism
`Herbalism`
## Overhaul Name Mining
`Mining`
## Overhaul Name Repair
`Repair`
## Overhaul Name Salvage
`Salvage`
## Overhaul Name Smelting
`Smelting`
## Overhaul Name Swords
`Swords`
## Overhaul Name Taming
`Taming`
## Overhaul Name Unarmed
`Unarmed`
## Overhaul Name Woodcutting
`Woodcutting`
# /mcMMO Command Style Stuff
## Commands mcc Header
`&c---[]&amcMMO Commands&c[]---`
## Commands Other
`&c---[]&aSPECIAL COMMANDS&c[]---`
## Commands Party Header
`&c-----[]&aPARTY&c[]-----`
## Commands Party Features Header
`&c-----[]&aFEATURES&c[]-----`
# XP BAR Allows for the following variables -- {0} = Skill Level, {1} Current XP, {2} XP Needed for next level, {3} Power Level, {4} Percentage of Level
# Make sure you turn on Experience_Bars.ThisMayCauseLag.AlwaysUpdateTitlesWhenXPIsGained if you want the XP bar title to update every time a player gains XP!
## XPBar Template
`{0}`
## XPBar Template EarlyGameBoost
`&6Learning a new skill...`
## XPBar Acrobatics
`Acrobatics Lv.&6{0}`
## XPBar Alchemy
`Alchemy Lv.&6{0}`
## XPBar Archery
`Archery Lv.&6{0}`
## XPBar Axes
`Axes Lv.&6{0}`
## XPBar Excavation
`Excavation Lv.&6{0}`
## XPBar Fishing
`Fishing Lv.&6{0}`
## XPBar Herbalism
`Herbalism Lv.&6{0}`
## XPBar Mining
`Mining Lv.&6{0}`
## XPBar Repair
`Repair Lv.&6{0}`
## XPBar Salvage
`Salvage Lv.&6{0}`
## XPBar Smelting
`Smelting Lv.&6{0}`
## XPBar Swords
`Swords Lv.&6{0}`
## XPBar Taming
`Taming Lv.&6{0}`
## XPBar Unarmed
`Unarmed Lv.&6{0}`
## XPBar Woodcutting
`Woodcutting Lv.&6{0}`
#This is just a preset template that gets used if the 'ExtraDetails' setting is turned on in experience.yml (off by default), you can ignore this template and just edit the strings above
## XPBar Complex Template
`{0} &3 {4}&f% &3(&f{1}&3/&f{2}&3)`
# XP BAR Allows for the following variables -- {0} = Skill Level, {1} Current XP, {2} XP Needed for next level, {3} Power Level, {4} Percentage of Level
# Make sure you turn on Experience_Bars.ThisMayCauseLag.AlwaysUpdateTitlesWhenXPIsGained if you want the XP bar title to update every time a player gains XP!
# END STYLING

#ACROBATICS
## Acrobatics Ability Proc
`&a**Graceful Landing**`
## Acrobatics Combat Proc
`&a**Dodged**`
## Acrobatics SubSkill Roll Stats
`&6Roll Chance &e{0}%&6 Graceful Roll Chance&e {1}%`
## Acrobatics SubSkill Roll Stat
`Roll Chance`
## Acrobatics.SubSkill Roll Stat Extra
`Graceful Roll Chance`
## Acrobatics SubSkill Roll Name
`Roll`
## Acrobatics SubSkill Roll Description
`Land strategically to avoid damage.`
## Acrobatics SubSkill Roll Chance
`Roll Chance: &e{0}`
## Acrobatics SubSkill Roll GraceChance
`Graceful Roll Chance: &e{0}`
## Acrobatics SubSkill Roll Mechanics
`&7Rolling is an active Sub-Skill with a passive component.\nWhenever you take fall damage you have a chance to completely negate the damage based on your skill level, at level &e{6}%&7 you have a &e{0}%&7 chance to prevent damage, and &e{1}%&7 if you activate Graceful Roll.\nThe chance for success is scaled against your skill level in a linear curve until level &e{2}&7 where it maxes out, every level in Acrobatics gives you a &e{3}%&7 chance to succeed.\nBy holding the sneak button you can double your odds to avoid fall damage and avoid up to twice the fall damage! Holding sneak will transform a normal roll into a Graceful Roll.\nRolling will only prevent up to &c{4}&7 damage. Graceful Rolls will prevent up to &a{5}&7 damage.`
## Acrobatics SubSkill GracefulRoll Name
`Graceful Roll`
## Acrobatics SubSkill GracefulRoll Description
`Twice as effective as a normal Roll`
## Acrobatics SubSkill Dodge Name
`Dodge`
## Acrobatics SubSkill Dodge Description
`Reduce attack damage by half`
## Acrobatics SubSkill Dodge Stat
`Dodge Chance`
## Acrobatics Listener
`Acrobatics:`
## Acrobatics Roll Text
`&o**Rolled**`
## Acrobatics SkillName
`ACROBATICS`
#ALCHEMY
## Alchemy SubSkill Catalysis Name
`Catalysis`
## Alchemy SubSkill Catalysis Description
`Increases potion brewing speed`
## Alchemy SubSkill Catalysis Stat
`Brewing Speed`
## Alchemy SubSkill Concoctions Name
`Concoctions`
## Alchemy SubSkill Concoctions Description
`Brew potions with more ingredients`
## Alchemy SubSkill Concoctions Stat
`Concoctions Rank: &a{0}&3/&a{1}`
## Alchemy.SubSkill Concoctions Stat Extra
`Ingredients [&a{0}&3]: &a{1}`
## Alchemy Listener
`Alchemy:`
## Alchemy Ability Locked 0
`LOCKED UNTIL {0}+ SKILL (CATALYSIS)`
## Alchemy SkillName
`ALCHEMY`
#ARCHERY


## Archery SubSkill SkillShot Name
`Skill Shot`
## Archery SubSkill SkillShot Description
`Increases damage done with bows`
## Archery SubSkill SkillShot Stat
`Skill Shot Bonus Damage`
## Archery SubSkill Daze Name
`Daze`
## Archery SubSkill Daze Description
`Disorients foes and deals extra DMG`
## Archery SubSkill Daze Stat
`Daze Chance`
## Archery SubSkill ArrowRetrieval Name
`Arrow Retrieval`
## Archery SubSkill ArrowRetrieval Description
`Chance to retrieve arrows from corpses`
## Archery SubSkill ArrowRetrieval Stat
`Arrow Recovery Chance`
## Archery SubSkill ArcheryLimitBreak Name
`Archery Limit Break`
## Archery SubSkill ArcheryLimitBreak Description
`Breaking your limits. Increased damage against tough opponents. Intended for PVP, up to server settings for whether or not it will boost damage in PVE.`
## Archery SubSkill ArcheryLimitBreak Stat
`Limit Break Max DMG`
## Archery Listener
`Archery:`
## Archery SkillName
`ARCHERY`
#AXES
## Axes Ability Bonus 0
`Axe Mastery`
## Axes Ability Bonus 1
`Bonus {0} damage`
## Axes Ability Bonus 2
`Armor Impact`
## Axes Ability Bonus 3
`Deal {0} Bonus DMG to armor`
## Axes Ability Bonus 4
`Greater Impact`
## Axes Ability Bonus 5
`Deal {0} Bonus DMG to unarmored foes`
## Axes Ability Lower
`&7You lower your Axe.`
## Axes Ability Ready
`&3You &6ready&3 your Axe.`
## Axes Ability Ready Extra
`&3You &6ready&3 your Axe. &7({0} is on cooldown for {1}s)`
## Axes Combat CritStruck
`&4You were CRITICALLY hit!`
## Axes Combat CriticalHit
`CRITICAL HIT!`
## Axes Combat GI Proc
`&a**STRUCK WITH GREAT FORCE**`
## Axes Combat GI Struck
`**HIT BY GREATER IMPACT**`
## Axes Combat SS Struck
`&4Struck by SKULL SPLITTER!`
## Axes SubSkill SkullSplitter Name
`Skull Splitter`
## Axes SubSkill SkullSplitter Description
`Deal AoE Damage`
## Axes SubSkill SkullSplitter Stat
`Skull Splitter Duration`
## Axes SubSkill CriticalStrikes Name
`Critical Strikes`
## Axes SubSkill CriticalStrikes Description
`Double Damage`
## Axes SubSkill CriticalStrikes Stat
`Critical Strike Chance`
## Axes SubSkill AxeMastery Name
`Axe Mastery`
## Axes SubSkill AxeMastery Description
`Adds bonus DMG`
## Axes SubSkill AxesLimitBreak Name
`Axes Limit Break`
## Axes SubSkill AxesLimitBreak Description
`Breaking your limits. Increased damage against tough opponents. Intended for PVP, up to server settings for whether or not it will boost damage in PVE.`
## Axes SubSkill AxesLimitBreak Stat
`Limit Break Max DMG`
## Axes SubSkill ArmorImpact Name
`Armor Impact`
## Axes SubSkill ArmorImpact Description
`Strike with enough force to shatter armor`
## Axes SubSkill GreaterImpact Name
`Greater Impact`
## Axes SubSkill GreaterImpact Description
`Deal bonus damage to unarmored foes`
## Axes Listener
`Axes:`
## Axes SkillName
`AXES`
## Axes Skills SS Off
`**Skull Splitter has worn off**`
## Axes Skills SS On
`&a**Skull Splitter ACTIVATED**`
## Axes Skills SS Refresh
`&aYour &eSkull Splitter &aability is refreshed!`
## Axes.Skills SS Other Off
`Skull Splitter&a has worn off for &e{0}`
## Axes.Skills SS Other On
`&a{0}&2 has used &cSkull Splitter!`
#EXCAVATION
## Excavation Ability Lower
`&7You lower your shovel.`
## Excavation Ability Ready
`&3You &6ready&3 your Shovel.`
## Excavation SubSkill GigaDrillBreaker Name
`Giga Drill Breaker`
## Excavation SubSkill GigaDrillBreaker Description
`3x Drop Rate, 3x EXP, +Speed`
## Excavation SubSkill GigaDrillBreaker Stat
`Giga Drill Breaker Duration`
## Excavation SubSkill Archaeology Name
`Archaeology`
## Excavation SubSkill Archaeology Description
`Unearth the secrets of the land! High skill levels increase your odds of finding experience orbs when you find treasure!`
## Excavation SubSkill Archaeology Stat
`Archaeology Experience Orb Chance`
## Excavation.SubSkill Archaeology Stat Extra
`Archaeology Experience Orb Amount`
## Excavation Listener
`Excavation:`
## Excavation SkillName
`EXCAVATION`
## Excavation Skills GigaDrillBreaker Off
`**Giga Drill Breaker has worn off**`
## Excavation Skills GigaDrillBreaker On
`&a**GIGA DRILL BREAKER ACTIVATED**`
## Excavation Skills GigaDrillBreaker Refresh
`&aYour &eGiga Drill Breaker &aability is refreshed!`
## Excavation.Skills GigaDrillBreaker Other Off
`Giga Drill Breaker&a has worn off for &e{0}`
## Excavation.Skills GigaDrillBreaker Other On
`&a{0}&2 has used &cGiga Drill Breaker!`
#FISHING
## Fishing ScarcityTip
`&e&oThis area is suffering from overfishing, cast your rod in a different spot for more fish. At least {0} blocks away.`
## Fishing Scared
`&7&oChaotic movements will scare fish!`
## Fishing Exhausting
`&c&oImproper use of the fishing rod will cause fatigue and wear out the rod!`
## Fishing LowResourcesTip
`&7You sense that there might not be many fish left in this area. Try fishing at least {0} blocks away.`
## Fishing Ability Info
`Magic Hunter: &7 **Improves With Treasure Hunter Rank**`
## Fishing Ability Locked 0
`LOCKED UNTIL {0}+ SKILL (SHAKE)`
## Fishing Ability Locked 1
`LOCKED UNTIL {0}+ SKILL (ICE FISHING)`
## Fishing Ability Locked 2
`LOCKED UNTIL {0}+ SKILL (MASTER ANGLER)`
## Fishing SubSkill TreasureHunter Name
`Treasure Hunter`
## Fishing SubSkill TreasureHunter Description
`Fish up misc. objects`
## Fishing SubSkill TreasureHunter Stat
`Treasure Hunter Rank: &a{0}&3/&a{1}`
## Fishing.SubSkill TreasureHunter Stat Extra
`Drop Rate: &7Common: &e{0} &aUncommon: &e{1}\n&9Rare: &e{2} &dEpic: &e{3} &6Legendary: &e{4} &bMythic: &e{5}`
## Fishing SubSkill MagicHunter Name
`Magic Hunter`
## Fishing SubSkill MagicHunter Description
`Find Enchanted Items`
## Fishing SubSkill MagicHunter Stat
`Magic Hunter Chance`
## Fishing SubSkill Shake Name
`Shake`
## Fishing SubSkill Shake Description
`Shake items off of mobs or players w/ fishing pole`
## Fishing SubSkill Shake Stat
`Shake Chance`
## Fishing SubSkill FishermansDiet Name
`Fisherman's Diet`
## Fishing SubSkill FishermansDiet Description
`Improves hunger restored from fished foods`
## Fishing SubSkill FishermansDiet Stat
`Fisherman's Diet:&a Rank {0}`
## Fishing SubSkill MasterAngler Name
`Master Angler`
## Fishing SubSkill MasterAngler Description
`Fish are caught more frequently, works better when fishing from a boat.`
## Fishing SubSkill MasterAngler Stat
`Fishing min wait time reduction: &a-{0} seconds`
## Fishing.SubSkill MasterAngler Stat Extra
`Fishing max wait time reduction: &a-{0} seconds`
## Fishing SubSkill IceFishing Name
`Ice Fishing`
## Fishing SubSkill IceFishing Description
`Allows you to fish in icy biomes`
## Fishing SubSkill IceFishing Stat
`Ice Fishing`
## Fishing Chance Raining
`&9 Rain Bonus`
## Fishing Listener
`Fishing:`
## Fishing Ability TH MagicFound
`&7You feel a touch of magic with this catch...`
## Fishing Ability TH Boom
`&7BOOM TIME!!!`
## Fishing Ability TH Poison
`&7Something doesn't smell quite right...`
## Fishing SkillName
`FISHING`
#HERBALISM
## Herbalism Ability GTe NeedMore
`You need more seeds to spread Green Terra.`
## Herbalism Ability GTh Fail
`**GREEN THUMB FAIL**`
## Herbalism Ability GTh
`&a**GREEN THUMB**`
## Herbalism Ability Lower
`&7You lower your Hoe.`
## Herbalism Ability Ready
`&3You &6ready&3 your Hoe.`
## Herbalism Ability ShroomThumb Fail
`**SHROOM THUMB FAIL**`
## Herbalism SubSkill GreenTerra Name
`Green Terra`
## Herbalism SubSkill GreenTerra Description
`Spread the Terra, 3x Drops, Boosts Green Thumb`
## Herbalism SubSkill GreenTerra Stat
`Green Terra Duration`
## Herbalism SubSkill GreenThumb Name
`Green Thumb`
## Herbalism SubSkill GreenThumb Description
`Auto-Plants crops when harvesting with hoe`
## Herbalism SubSkill GreenThumb Stat
`Green Thumb Chance`
## Herbalism.SubSkill GreenThumb Stat Extra
`Green Thumb Stage: &a Crops grow in stage {0}`
## Herbalism Effect 4
`Green Thumb (Blocks)`
## Herbalism.SubSkill GreenThumb Description 2
`Make bricks mossy, or make grass grow`
## Herbalism SubSkill FarmersDiet Name
`Farmer's Diet`
## Herbalism SubSkill FarmersDiet Description
`Improves hunger restored from farmed foods`
## Herbalism SubSkill FarmersDiet Stat
`Farmer's Diet: &aRank {0}`
## Herbalism SubSkill DoubleDrops Name
`Double Drops`
## Herbalism SubSkill DoubleDrops Description
`Double the normal loot`
## Herbalism SubSkill DoubleDrops Stat
`Double Drop Chance`
## Herbalism SubSkill HylianLuck Name
`Hylian Luck`
## Herbalism SubSkill HylianLuck Description
`Gives a small chance of finding rare items`
## Herbalism SubSkill HylianLuck Stat
`Hylian Luck Chance`
## Herbalism SubSkill ShroomThumb Name
`Shroom Thumb`
## Herbalism SubSkill ShroomThumb Description
`Spread mycelium to dirt & grass`
## Herbalism SubSkill ShroomThumb Stat
`Shroom Thumb Chance`
## Herbalism HylianLuck
`&aThe luck of Hyrule is with you today!`
## Herbalism Listener
`Herbalism:`
## Herbalism SkillName
`HERBALISM`
## Herbalism Skills GTe Off
`**Green Terra has worn off**`
## Herbalism Skills GTe On
`&a**GREEN TERRA ACTIVATED**`
## Herbalism Skills GTe Refresh
`&aYour &eGreen Terra &aability is refreshed!`
## Herbalism.Skills GTe Other Off
`Green Terra&a has worn off for &e{0}`
## Herbalism.Skills GTe Other On
`&a{0}&2 has used &cGreen Terra!`
#MINING
## Mining Ability Locked 0
`LOCKED UNTIL {0}+ SKILL (BLAST MINING)`
## Mining Ability Locked 1
`LOCKED UNTIL {0}+ SKILL (BIGGER BOMBS)`
## Mining Ability Locked 2
`LOCKED UNTIL {0}+ SKILL (DEMOLITIONS EXPERTISE)`
## Mining Ability Lower
`&7You lower your Pickaxe.`
## Mining Ability Ready
`&3You &6ready&3 your pickaxe.`
## Mining SubSkill SuperBreaker Name
`Super Breaker`
## Mining SubSkill SuperBreaker Description
`Speed+, Triple Drop Chance`
## Mining SubSkill SuperBreaker Stat
`Super Breaker Length`
## Mining SubSkill DoubleDrops Name
`Double Drops`
## Mining SubSkill DoubleDrops Description
`Double the normal loot`
## Mining SubSkill DoubleDrops Stat
`Double Drop Chance`
## Mining SubSkill BlastMining Name
`Blast Mining`
## Mining SubSkill BlastMining Description
`Bonuses to mining with TNT`
## Mining SubSkill BlastMining Stat
`Blast Mining:&a Rank {0}/{1} &7({2})`
## Mining.SubSkill BlastMining Stat Extra
`Blast Radius Increase: &a+{0}`
## Mining SubSkill BiggerBombs Name
`Bigger Bombs`
## Mining SubSkill BiggerBombs Description
`Increases TNT explosion radius`
## Mining SubSkill DemolitionsExpertise Name
`Demolitions Expertise`
## Mining SubSkill DemolitionsExpertise Description
`Decreases damage from TNT explosions`
## Mining SubSkill DemolitionsExpertise Stat
`Demolitions Expert Damage Decrease`

## Mining Listener
`Mining:`
## Mining SkillName
`MINING`
## Mining Skills SuperBreaker Off
`**Super Breaker has worn off**`
## Mining Skills SuperBreaker On
`&a**SUPER BREAKER ACTIVATED**`
## Mining.Skills SuperBreaker Other Off
`Super Breaker&a has worn off for &e{0}`
## Mining.Skills SuperBreaker Other On
`&a{0}&2 has used &cSuper Breaker!`
## Mining Skills SuperBreaker Refresh
`&aYour &eSuper Breaker &aability is refreshed!`
#Blast Mining
## Mining Blast Boom
`&7**BOOM**`
## Mining Blast Cooldown
`x`
## Mining Blast Effect
`+{0} ore yield,  {1}x drops`
## Mining Blast Other On
`&a{0}&2 has used &cBlast Mining!`
## Mining Blast Refresh
`&aYour &eBlast Mining &aability is refreshed!`
#REPAIR
## Repair SubSkill Repair Name
`Repair`
## Repair SubSkill Repair Description
`Repair Tools & Armor`
## Repair SubSkill GoldRepair Name
`Gold Repair ({0}+ SKILL)`
## Repair SubSkill GoldRepair Description
`Repair Gold Tools & Armor`
## Repair SubSkill IronRepair Name
`Iron Repair ({0}+ SKILL)`
## Repair SubSkill IronRepair Description
`Repair Iron Tools & Armor`
## Repair SubSkill StoneRepair Name
`Stone Repair ({0}+ SKILL)`
## Repair SubSkill StoneRepair Description
`Repair Stone Tools`
## Repair SubSkill RepairMastery Name
`Repair Mastery`
## Repair SubSkill RepairMastery Description
`Increased repair amount`
## Repair SubSkill RepairMastery Stat
`Repair Mastery: &aExtra {0} durability restored`
## Repair SubSkill SuperRepair Name
`Super Repair`
## Repair SubSkill SuperRepair Description
`Double effectiveness`
## Repair SubSkill SuperRepair Stat
`Super Repair Chance`
## Repair SubSkill DiamondRepair Name
`Diamond Repair ({0}+ SKILL)`
## Repair SubSkill DiamondRepair Description
`Repair Diamond Tools & Armor`
## Repair SubSkill ArcaneForging Name
`Arcane Forging`
## Repair SubSkill ArcaneForging Description
`Repair magic items`
## Repair SubSkill ArcaneForging Stat
`Arcane Forging: &eRank {0}/{1}`
## Repair.SubSkill ArcaneForging Stat Extra
`&3Arcane Forging Odds:&7 Success &a{0}&7%, Failure &c{1}&7%`
## Repair Error
`&4mcMMO encountered an error attempting to repair this item!`
## Repair Listener Anvil
`&4You have placed an anvil, anvils can repair tools and armor.`
## Repair Listener
`Repair:`
## Repair SkillName
`REPAIR`
## Repair Skills AdeptDiamond
`&4You're not skilled enough to repair Diamond.`
## Repair Skills AdeptGold
`&4You're not skilled enough to repair Gold.`
## Repair Skills AdeptIron
`&4You're not skilled enough to repair Iron.`
## Repair Skills AdeptStone
`&4You're not skilled enough to repair Stone.`
## Repair Skills Adept
`&cYou must be level &e{0}&c to repair &e{1}`
## Repair Skills FeltEasy
`&7That felt easy.`
## Repair Skills FullDurability
`&7That is at full durability.`
## Repair Skills StackedItems
`&4You can't repair stacked items.`
## Repair Pretty Name
`Repair`
#Arcane Forging
## Repair Arcane Downgrade
`Arcane power has decreased for this item.`
## Repair Arcane Fail
`Arcane power has permanently left the item.`
## Repair Arcane Lost
`You were not skilled enough to keep any enchantments.`
## Repair Arcane Perfect
`&aYou have sustained the arcane energies in this item.`
#SALVAGE
## Salvage Pretty Name
`Salvage`
## Salvage SubSkill UnderstandingTheArt Name
`Understanding The Art`
## Salvage SubSkill UnderstandingTheArt Description
`You're not just digging through your neighbors trash, you're taking care of the environment.\nPowers up various properties of Salvaging.`
## Salvage SubSkill ScrapCollector Name
`Scrap Collector`
## Salvage SubSkill ScrapCollector Description
`Salvage materials from an item, a perfect salvage depends on skill and luck.`
## Salvage SubSkill ScrapCollector Stat
`Scrap Collector: &aSalvage up to &e{0}&a items. Some luck is involved.`
## Salvage SubSkill ArcaneSalvage Name
`Arcane Salvaging`
## Salvage SubSkill ArcaneSalvage Description
`Extract enchantments from items`
## Salvage SubSkill ArcaneSalvage Stat
`Arcane Salvaging: &eRank {0}/{1}`
## Salvage Ability Bonus 0
`Scrap Collector`
## Salvage Ability Bonus 1
`Salvage up to &e{0}&a items. Some luck is involved.`
## Salvage Arcane ExtractFull
`&7AS Full-Enchant Chance`
## Salvage Arcane ExtractPartial
`&7AS Partial-Enchant Chance`
## Salvage Skills Success
`&aItem salvaged!`
## Salvage Skills Adept Damaged
`&4You aren't skilled enough to salvage damaged items.`
## Salvage Skills Adept Level
`You must be level &e{0}&c to salvage &e{1}`
## Salvage Skills TooDamaged
`&4This item is too damaged to be salvaged.`
## Salvage Skills ArcaneFailed
`&cYou were unable to extract the knowledge contained within this item.`
## Salvage Skills ArcanePartial
`&cYou were only able to extract some of the knowledge contained within this item.`
## Salvage Skills ArcaneSuccess
`&aYou able to extract all of the knowledge contained within this item!`
## Salvage Listener Anvil
`&4You have placed a Salvage anvil, use this to Salvage tools and armor.`
## Salvage Listener
`Salvage:`
## Salvage SkillName
`SALVAGE`
## Salvage Skills Lottery Normal
`&6You were able to salvage &3{0}&6 materials from &e{1}&6.`
## Salvage Skills Lottery Perfect
`&a&lPerfect!&r&6 You salvaged &3{1}&6 effortlessly, retrieving &3{0}&6 materials.`
## Salvage Skills Lottery Untrained
`&7You aren't properly trained in salvaging. You were only able to recover &c{0}&7 materials from &a{1}&7.`
#Anvil (Shared between SALVAGE and REPAIR)
## Anvil Unbreakable
`This item is unbreakable!`
#SWORDS
## Swords Ability Lower
`&7You lower your sword.`
## Swords Ability Ready
`&3You &6ready&3 your Sword.`
## Swords.Combat.Rupture Note Update One
`&7(Rupture Note): Periodic damage is non-lethal occurring twice a second and bypasses armor`
## Swords Combat Bleeding Started
`&4 You're bleeding!`
## Swords Combat Bleeding Stopped
`&7The bleeding has &astopped&7!`
## Swords Combat Bleeding
`&a**ENEMY BLEEDING**`
## Swords Combat Counter Hit
`&4Hit with a counter-attack!`
## Swords Combat Countered
`&a**COUNTER-ATTACKED**`
## Swords Combat SS Struck
`&4Struck by SERRATED STRIKES!`
## Swords SubSkill CounterAttack Name
`Counter Attack`
## Swords SubSkill CounterAttack Description
`Reflect a portion of damage when attacked!`
## Swords SubSkill CounterAttack Stat
`Counter Attack Chance`
## Swords SubSkill SerratedStrikes Name
`Serrated Strikes`
## Swords SubSkill SerratedStrikes Description
`Deal partial damage in an AOE with a chance to apply Rupture!`
## Swords SubSkill SerratedStrikes Stat
`Serrated Strikes Length`
## Swords SubSkill Rupture Name
`Rupture`
## Swords SubSkill Rupture Description
`A damage over time effect that ends explosively`
## Swords SubSkill Stab Name
`Stab`
## Swords SubSkill Stab Description
`Adds bonus damage to your attacks.`
## Swords SubSkill Stab Stat
`Stab Damage`
## Swords SubSkill SwordsLimitBreak Name
`Swords Limit Break`
## Swords SubSkill SwordsLimitBreak Description
`Breaking your limits. Increased damage against tough opponents. Intended for PVP, up to server settings for whether or not it will boost damage in PVE.`
## Swords SubSkill SwordsLimitBreak Stat
`Limit Break Max DMG`
## Swords SubSkill Rupture Stat
`Rupture Chance`
## Swords.SubSkill Rupture Stat Extra
`[[DARK_AQUA]]Rupture Duration: &e{0}s&a vs Players, &e{1}s&a vs Mobs.`
## Swords.SubSkill Rupture Stat TickDamage
`[[DARK_AQUA]]Rupture Pure Tick Damage: &e{0}&a vs Players, &e{1}&a vs Mobs.`
## Swords.SubSkill Rupture Stat ExplosionDamage
`[[DARK_AQUA]]Rupture Explosion Damage: &e{0}&a vs Players, &e{1}&a vs Mobs`
## Swords Effect 4
`Serrated Strikes Rupture+`
## Swords Effect 5
`{0} Tick Rupture`
## Swords Listener
`Swords:`
## Swords SkillName
`SWORDS`
## Swords Skills SS Off
`**Serrated Strikes has worn off**`
## Swords Skills SS On
`&a**SERRATED STRIKES ACTIVATED**`
## Swords Skills SS Refresh
`&aYour &eSerrated Strikes &aability is refreshed!`
## Swords.Skills SS Other Off
`Serrated Strikes&a has worn off for &e{0}`
## Swords.Skills SS Other On
`&a{0}&2 has used &cSerrated Strikes!`
#TAMING
## Taming Ability Bonus 0
`Environmentally Aware`
## Taming Ability Bonus 1
`Wolves avoid danger`
## Taming Ability Bonus 2
`Thick Fur`
## Taming Ability Bonus 3
`1/{0} Damage, Fire Resistance`
## Taming Ability Bonus 4
`Shock Proof`
## Taming Ability Bonus 5
`Explosives do 1/{0} normal damage`
## Taming Ability Bonus 6
`Sharpened Claws`
## Taming Ability Bonus 7
`+{0} Damage`
## Taming Ability Bonus 8
`Fast Food Service`
## Taming Ability Bonus 9
`{0} Chance for heal on attack`
## Taming Ability Bonus 10
`Holy Hound`
## Taming Ability Bonus 11
`Regain health when damaged by magic or poison`
## Taming Ability Locked 0
`LOCKED UNTIL {0}+ SKILL (ENVIRONMENTALLY AWARE)`
## Taming Ability Locked 1
`LOCKED UNTIL {0}+ SKILL (THICK FUR)`
## Taming Ability Locked 2
`LOCKED UNTIL {0}+ SKILL (SHOCK PROOF)`
## Taming Ability Locked 3
`LOCKED UNTIL {0}+ SKILL (SHARPENED CLAWS)`
## Taming Ability Locked 4
`LOCKED UNTIL {0}+ SKILL (FAST FOOD SERVICE)`
## Taming Ability Locked 5
`LOCKED UNTIL {0}+ SKILL (HOLY HOUND)`
## Taming Combat Chance Gore
`Gore Chance`
## Taming SubSkill BeastLore Name
`Beast Lore`
## Taming SubSkill BeastLore Description
`Bone-whacking inspects wolves & ocelots`
## Taming SubSkill ShockProof Name
`Shock Proof`
## Taming SubSkill ShockProof Description
`Explosive Damage Reduction`
## Taming SubSkill CallOfTheWild Name
`Call of the Wild`
## Taming SubSkill CallOfTheWild Description
`Summon an animal to your side`
## Taming.SubSkill CallOfTheWild Description 2
`&7COTW: Crouch and left-click with\n  {0} {1} (Ocelot), {2} {3} (Wolf), {4} {5} (Horse)`
## Taming SubSkill FastFoodService Name
`Fast Food Service`
## Taming SubSkill FastFoodService Description
`Chance for wolves to heal on attack`
## Taming SubSkill HolyHound Name
`Holy Hound`
## Taming SubSkill HolyHound Description
`Healed by Magic & Poison`
## Taming SubSkill Gore Name
`Gore`
## Taming SubSkill Gore Description
`Critical Strike that applies Rupture`
## Taming SubSkill SharpenedClaws Name
`Sharpened Claws`
## Taming SubSkill SharpenedClaws Description
`Damage Bonus`
## Taming SubSkill EnvironmentallyAware Name
`Environmentally Aware`
## Taming SubSkill EnvironmentallyAware Description
`Cactus/Lava Phobia, Fall DMG Immune`
## Taming SubSkill ThickFur Name
`Thick Fur`
## Taming SubSkill ThickFur Description
`DMG Reduction, Fire Resistance`
## Taming SubSkill Pummel Name
`Pummel`
## Taming SubSkill Pummel Description
`Your Wolves have a chance of knocking back foes`
## Taming SubSkill Pummel TargetMessage
`You've been knocked back by a wolf!`
## Taming Listener Wolf
`&8Your wolf scurries back to you...`
## Taming Listener
`Taming:`
## Taming SkillName
`TAMING`
## Taming.Summon COTW Success WithoutLifespan
`&a(Call Of The Wild) &7You have summoned a &6{0}&7`
## Taming.Summon COTW Success WithLifespan
`&a(Call Of The Wild) &7You have summoned a &6{0}&7 and it has a duration of &6{1}&7 seconds.`
## Taming Summon COTW Limit
`&a(Call Of The Wild) &7You can only have &c{0} &7summoned &7{1} pets at the same time.`
## Taming Summon COTW TimeExpired
`&a(Call Of The Wild) &7Time is up, your &6{0}&7 departs.`
## Taming Summon COTW Removed
`&a(Call Of The Wild) &7Your summoned &6{0}&7 has vanished from this world.`
## Taming Summon COTW BreedingDisallowed
`&a(Call Of The Wild) &cYou cannot breed a summoned animal.`
## Taming Summon COTW NeedMoreItems
`&a(Call Of The Wild) &7You need &e{0}&7 more &3{1}&7(s)`
## Taming Summon Name Format
`&6(COTW) &f{0}'s {1}`
#UNARMED
## Unarmed Ability Bonus 0
`Steel Arm Style`
## Unarmed Ability Bonus 1
`+{0} DMG Upgrade`
## Unarmed Ability IronGrip Attacker
`Your opponent has an iron grip!`
## Unarmed Ability IronGrip Defender
`&aYour iron grip kept you from being disarmed!`
## Unarmed Ability Lower
`&7You lower your fists.`
## Unarmed Ability Ready
`&3You &6ready&3 your fists.`
## Unarmed SubSkill Berserk Name
`Berserk`
## Unarmed SubSkill Berserk Description
`+50% DMG, Breaks weak materials`
## Unarmed SubSkill Berserk Stat
`Berserk Length`
## Unarmed SubSkill Disarm Name
`Disarm`
## Unarmed SubSkill Disarm Description
`Drops the foes item held in hand`
## Unarmed SubSkill Disarm Stat
`Disarm Chance`
## Unarmed SubSkill UnarmedLimitBreak Name
`Unarmed Limit Break`
## Unarmed SubSkill UnarmedLimitBreak Description
`Breaking your limits. Increased damage against tough opponents. Intended for PVP, up to server settings for whether or not it will boost damage in PVE.`
## Unarmed SubSkill UnarmedLimitBreak Stat
`Limit Break Max DMG`
## Unarmed SubSkill SteelArmStyle Name
`Steel Arm Style`
## Unarmed SubSkill SteelArmStyle Description
`Hardens your arm over time`
## Unarmed SubSkill ArrowDeflect Name
`Arrow Deflect`
## Unarmed SubSkill ArrowDeflect Description
`Deflect arrows`
## Unarmed SubSkill ArrowDeflect Stat
`Arrow Deflect Chance`
## Unarmed SubSkill IronGrip Name
`Iron Grip`
## Unarmed SubSkill IronGrip Description
`Prevents you from being disarmed`
## Unarmed SubSkill IronGrip Stat
`Iron Grip Chance`
## Unarmed SubSkill BlockCracker Name
`Block Cracker`
## Unarmed SubSkill BlockCracker Description
`Break rock with your fists`
## Unarmed Listener
`Unarmed:`
## Unarmed SkillName
`UNARMED`
## Unarmed Skills Berserk Off
`**Berserk has worn off**`
## Unarmed Skills Berserk On
`&a**BERSERK ACTIVATED**`
## Unarmed.Skills Berserk Other Off
`Berserk&a has worn off for &e{0}`
## Unarmed.Skills Berserk Other On
`&a{0}&2 has used &cBerserk!`
## Unarmed Skills Berserk Refresh
`&aYour &eBerserk &aability is refreshed!`
#WOODCUTTING
## Woodcutting Ability 0
`Leaf Blower`
## Woodcutting Ability 1
`Blow away leaves`
## Woodcutting Ability Locked 0
`LOCKED UNTIL {0}+ SKILL (LEAF BLOWER)`
## Woodcutting SubSkill TreeFeller Name
`Tree Feller`
## Woodcutting SubSkill TreeFeller Description
`Make trees explode`
## Woodcutting SubSkill TreeFeller Stat
`Tree Feller Length`
## Woodcutting SubSkill LeafBlower Name
`Leaf Blower`
## Woodcutting SubSkill LeafBlower Description
`Blow Away Leaves`
## Woodcutting SubSkill KnockOnWood Name
`Knock On Wood`
## Woodcutting SubSkill KnockOnWood Description
`Find additional goodies when using Tree Feller`
## Woodcutting SubSkill KnockOnWood Stat
`Knock on Wood`
## Woodcutting.SubSkill KnockOnWood Loot Normal
`Standard loot from trees`
## Woodcutting.SubSkill KnockOnWood Loot Rank2
`Standard loot from trees and experience orbs`
## Woodcutting SubSkill HarvestLumber Name
`Harvest Lumber`
## Woodcutting SubSkill HarvestLumber Description
`Skillfully extract more Lumber`
## Woodcutting SubSkill HarvestLumber Stat
`Double Drop Chance`
## Woodcutting SubSkill Splinter Name
`Splinter`
## Woodcutting SubSkill Splinter Description
`Cut down trees more efficiently.`
## Woodcutting SubSkill BarkSurgeon Name
`Bark Surgeon`
## Woodcutting SubSkill BarkSurgeon Description
`Extract useful materials when stripping trees.`
## Woodcutting SubSkill NaturesBounty Name
`Nature's Bounty`
## Woodcutting SubSkill NaturesBounty Description
`Gather experience from nature.`
## Woodcutting Listener
`Woodcutting:`
## Woodcutting SkillName
`WOODCUTTING`
## Woodcutting Skills TreeFeller Off
`**Tree Feller has worn off**`
## Woodcutting Skills TreeFeller On
`&a**TREE FELLER ACTIVATED**`
## Woodcutting Skills TreeFeller Refresh
`&aYour &eTree Feller &aability is refreshed!`
## Woodcutting.Skills TreeFeller Other Off
`Tree Feller&a has worn off for &e{0}`
## Woodcutting.Skills TreeFeller Other On
`&a{0}&2 has used &cTree Feller!`
## Woodcutting Skills TreeFeller Splinter
`YOUR AXE SPLINTERS INTO DOZENS OF PIECES!`
## Woodcutting Skills TreeFeller Threshold
`That tree is too large!`
#ABILITIY

#COMBAT
## Combat ArrowDeflect
`&f**ARROW DEFLECT**`
## Combat BeastLore
`&a**BEAST LORE**`
## Combat BeastLoreHealth
`&3Health (&a{0}&3/{1})`
## Combat BeastLoreOwner
`&3Owner (&c{0}&3)`
## Combat BeastLoreHorseSpeed
`&3Horse Movement Speed (&a{0} blocks/s&3)`
## Combat BeastLoreHorseJumpStrength
`&3Horse Jump Strength (&aMax {0} blocks&3)`
## Combat Gore
`&a**GORED**`
## Combat StruckByGore
`**YOU HAVE BEEN GORED**`
## Combat TargetDazed
`Target was &4Dazed`
## Combat TouchedFuzzy
`&4Touched Fuzzy. Felt Dizzy.`
#COMMANDS
##generic
## mcMMO Description
`&3About the &emcMMO&3 Project:,&6mcMMO is an &copen source&6 RPG mod created in February 2011,&6by &9nossr50&6. The goal is to provide a quality RPG experience.,&3Tips:,&6 - &aUse &c/mcmmo help&a to see commands,&6 - &aType &c/SKILLNAME&a to see detailed skill info,&3Developers:,&6 - &anossr50 &9(Creator & Project Lead),&6 - &aelectronicboy &9(Dev),&6 - &akashike &9(Dev),&6 - &at00thpick1 &9(Classic Maintainer)`
## mcMMO Description FormerDevs
`&3Former Devs: &aGJ, NuclearW, bm01, TfT_02, Glitchfinder`
## Commands addlevels AwardAll 1
`&aYou were awarded {0} levels in all skills!`
## Commands addlevels AwardAll 2
`All skills have been modified for {0}.`
## Commands addlevels AwardSkill 1
`&aYou were awarded {0} levels in {1}!`
## Commands addlevels AwardSkill 2
`{0} has been modified for {1}.`
## Commands addxp AwardAll
`&aYou were awarded {0} experience in all skills!`
## Commands addxp AwardSkill
`&aYou were awarded {0} experience in {1}!`
## Commands Ability Off
`Ability use toggled &coff`
## Commands Ability On
`Ability use toggled &aon`
## Commands Ability Toggle
`Ability use has been toggled for &e{0}`
## Commands AdminChat Off
`Admin Chat only &cOff`
## Commands AdminChat On
`Admin Chat only &aOn`
## Commands AdminToggle
`&a- Toggle admin chat`
## Commands Chat Console
`*Console*`
## Commands Cooldowns Header
`&6--= &amcMMO Ability Cooldowns&6 =--`
## Commands Cooldowns Row N
`\  &c{0}&f - &6{1} seconds left`
## Commands Cooldowns Row Y
`\  &b{0}&f - &2Ready!`
## Commands Database CooldownMS
`You must wait {0} milliseconds before using this command again.`
## Commands Database Cooldown
`You must wait {0} seconds before using this command again.`
## Commands Database Processing
`Your previous command is still being processed. Please wait.`
## Commands Disabled
`This command is disabled.`
## Commands DoesNotExist
` &cPlayer does not exist in the database!`
## Commands GodMode Disabled
`mcMMO Godmode Disabled`
## Commands GodMode Enabled
`mcMMO Godmode Enabled`
## Commands AdminChatSpy Enabled
`mcMMO Party Chat Spy Enabled`
## Commands AdminChatSpy Disabled
`mcMMO Party Chat Spy Disabled`
## Commands AdminChatSpy Toggle
`mcMMO Party Chat has been toggled for &e{0}`
## Commands AdminChatSpy Chat
`&6[SPY: &a{0}&6] &f{1}`
## Commands GodMode Forbidden
`[mcMMO] God Mode not permitted on this world (See Permissions)`
## Commands GodMode Toggle
`God mode has been toggled for &e{0}`
## Commands Healthbars Changed HEARTS
`[mcMMO] Your healthbar display type was changed to &cHearts&f.`
## Commands Healthbars Changed BAR
`[mcMMO] Your healthbar display type was changed to &eBoxes&f.`
## Commands Healthbars Changed DISABLED
`[mcMMO] Your mob healthbars have been &7disabled&f.`
## Commands Healthbars Invalid
`Invalid healthbar type!`
## Commands Inspect
`<player> &a- View detailed player info`
## Commands Invite Success
`&aInvite sent successfully.`
## Commands Leaderboards
`<skill> <page> &a- Leaderboards`
## Commands mcgod
`&a- Toggle GodMode`
## Commands mchud Invalid
`That is not a valid HUD type.`
## Commands mcpurge Success
`&aThe database was successfully purged!`
## Commands mcrank Heading=&6-=PERSONAL RANKINGS
`-`
## Commands mcrank Overall
`Overall&a - &6Rank &f#&a{0}`
## Commands mcrank Player
`&eRankings for &f{0}`
## Commands mcrank Skill
`&e{0}&a - &6Rank &f#&a{1}`
## Commands mcrank Unranked
`&fUnranked`
## Commands mcrefresh Success
`{0}''s cooldowns have been refreshed.`
## Commands mcremove Success
`&a{0} was successfully removed from the database!`
## Commands mctop Tip
`&6Tip: Use &c/mcrank&6 to view all of your personal rankings!`
## Commands mmoedit
`[player] <skill> <newvalue> &a - Modify target`
## Commands mmoedit AllSkills 1
`&aYour level in all skills was set to {0}!`
## Commands mmoedit Modified 1
`&aYour level in {0} was set to {1}!`
## Commands mmoedit Modified 2
`{0} has been modified for {1}.`
## Commands mcconvert Database Same
`You are already using the {0} database!`
## Commands mcconvert Database InvalidType
`{0} is not a valid database type.`
## Commands mcconvert Database Start
`&7Starting conversion from {0} to {1}...`
## Commands mcconvert Database Finish
`&7Database migration complete; the {1} database now has all data from the {0} database.`
## Commands mmoshowdb
`The currently used database is &a{0}`
## Commands mcconvert Experience Invalid
`Unknown formula type! Valid types are: &aLINEAR &cand &aEXPONENTIAL.`
## Commands mcconvert Experience Same
`Already using formula type {0}`
## Commands mcconvert Experience Start
`&7Starting conversion from {0} to {1} curve`
## Commands mcconvert Experience Finish
`&7Formula conversion complete; now using {0} XP curve.`
## Commands ModDescription
`&a- Read brief mod description`
## Commands NoConsole
`This command does not support console usage.`
## Commands Notifications Off
`Ability notifications toggled &coff`
## Commands Notifications On
`Ability notifications toggled &aon`
## Commands Offline
`This command does not work for offline players.`
## Commands NotLoaded
`Player profile is not loaded yet.`
## Commands Party Status
`&8NAME: &f{0} {1} &8LEVEL: &3{2}`
## Commands Party Status Alliance
`&8ALLY: &f{0}`
## Commands Party UnlockedFeatures
`&8Unlocked Features: &7&o{0}`
## Commands Party ShareMode
`&8SHARE MODE:`
## Commands Party ItemShare
`&7ITEM &3({0})`
## Commands Party ExpShare
`&7EXP &3({0})`
## Commands Party ItemShareCategories
`&8Sharing Items: &7&o{0}`
## Commands Party MembersNear
`&8NEAR YOU &3{0}&8/&3{1}`
## Commands Party Accept
`&a- Accept party invite`
## Commands Party Chat Off
`Party Chat only &cOff`
## Commands Party Chat On
`Party Chat only &aOn`
## Commands Party Commands
`&c---[]&aPARTY COMMANDS&c[]---`
## Commands Party Invite 0
`&cALERT: &aYou have received a party invite for {0} from {1}`
## Commands Party Invite 1
`&eType &a/party accept&e to accept the invite`
## Commands Party Invite
`&a- Send party invite`
## Commands Party Invite Accepted
`&aInvite Accepted. You have joined party {0}`
## Commands Party Join
`&7Joined Party: {0}`
## Commands Party PartyFull
`&6{0}&c is full!`
## Commands Party PartyFull Invite
`You cannot invite &e{0}&c to &a{1}&c because it already has &3{2}&c players in it!`
## Commands Party PartyFull InviteAccept
`You cannot join &a{0}&c because it already has &3{1}&c players in it!`
## Commands Party Create
`&7Created Party: {0}`
## Commands Party Rename
`&7Party name changed to: &f{0}`
## Commands Party SetSharing
`&7Party {0} sharing set to: &3{1}`
## Commands Party ToggleShareCategory
`&7Party item sharing for &6{0} &7has been &3{1}`
## Commands Party AlreadyExists
`&4Party {0} already exists!`
## Commands Party Kick
`&cYou were kicked from party &a{0}&c!`
## Commands Party Leave
`&eYou have left that party`
## Commands Party Members Header
`&c-----[]&aMEMBERS&c[]-----`
## Commands Party None
`&cYou are not in a party.`
## Commands Party Quit
`&a- Leave your current party`
## Commands Party Teleport
`&a- Teleport to party member`
## Commands Party Toggle
`&a- Toggle Party Chat`
## Commands Party1
`&a- Create a new party`
## Commands Party2
`&a- Join a players party`
## Commands Party Alliance Header
`&c-----[]&aPARTY ALLIANCE&c[]-----`
## Commands Party Alliance Ally
`&f{0} &8IS ALLIED WITH: &f{1}`
## Commands.Party Alliance Members Header
`&c-----[]&aALLIANCE MEMBERS&c[]-----`
## Commands.Party Alliance Invite 0
`ALERT: &aYou have received a party alliance invite for {0} from {1}`
## Commands.Party Alliance Invite 1
`Type &a/party alliance accept&e to accept the invite`
## Commands.Party Alliance Invite Accepted
`&aAlliance invite Accepted.`
## Commands Party Alliance None
`&cYour party does not have an ally.`
## Commands Party Alliance AlreadyAllies
`&cYour party already has an ally. Disband with &3/party alliance disband`
## Commands.Party Alliance Help 0
`&cThis party hasn't formed an alliance. Invite a party leader`
## Commands.Party Alliance Help 1
`&c to an alliance with &3/party alliance invite <player>&c.`
## Commands ptp Enabled
`Party teleporting &aenabled`
## Commands ptp Disabled
`Party teleporting &cdisabled`
## Commands ptp NoRequests
`&cYou have no teleport requests at this time`
## Commands ptp NoWorldPermissions
`&c[mcMMO] You do not have permission to teleport to the world {0}.`
## Commands ptp Request1
`&e{0} &ahas requested to teleport to you.`
## Commands ptp Request2
`&aTo teleport, type &e/ptp accept&a. Request expires in &c{0} &aseconds.`
## Commands ptp AcceptAny Enabled
`Party teleport request confirmation &aenabled`
## Commands ptp AcceptAny Disabled
`Party teleport request confirmation &cdisabled`
## Commands ptp RequestExpired
`&cParty teleport request has expired!`
## Commands PowerLevel Leaderboard
`&e--mcMMO&9 Power Level &eLeaderboard--`
## Commands PowerLevel Capped
`&4POWER LEVEL: &a{0} &4MAX LEVEL: &e{1}`
## Commands PowerLevel
`&4POWER LEVEL: &a{0}`
## Commands Reset All
`&aAll of your skill levels have been reset successfully.`
## Commands Reset Single
`&aYour {0} skill level has been reset successfully.`
## Commands Reset
`&a- Reset a skill's level to 0`
## Commands Scoreboard Clear
`&3mcMMO scoreboard cleared.`
## Commands Scoreboard NoBoard
`&cThe mcMMO scoreboard is not active.`
## Commands Scoreboard Keep
`&3The mcMMO scoreboard will stay up until you use &a/mcscoreboard clear&3.`
## Commands Scoreboard Timer
`&3The mcMMO scoreboard will clear &6{0}&3 seconds from now.`
## Commands Scoreboard Help 0
`&6 == &aHelp for &c/mcscoreboard&6 ==`
## Commands Scoreboard Help 1
`&3/mcscoreboard&b clear &f - clear the McMMO scoreboard`
## Commands Scoreboard Help 2
`&3/mcscoreboard&b keep &f - keep the mcMMO scoreboard up`
## Commands Scoreboard Help 3
`&3/mcscoreboard&b time [n] &f - clear the McMMO scoreboard after &dn&f seconds`
## Commands Scoreboard Tip Keep
`&6Tip: Use &c/mcscoreboard keep&6 while the scoreboard is shown to keep it from going away.`
## Commands Scoreboard Tip Clear
`&6Tip: Use &c/mcscoreboard clear&6 to get rid of the scoreboard.`
## Commands XPBar Reset
`&6XP Bar settings for mcMMO have been reset.`
## Commands XPBar SettingChanged
`&6XP Bar setting for &a{0}&6 is now set to &a{1}`
## Commands Skill Invalid
`That is not a valid skillname!`
## Commands Skill ChildSkill
`Child skills are not valid for this command!`
## Commands Skill Leaderboard
`--mcMMO &9{0}&e Leaderboard--`
## Commands SkillInfo
`&a- View detailed information about a skill`
## Commands Stats
`&a- View your mcMMO stats`
## Commands ToggleAbility
`&a- Toggle ability activation with right click`
## Commands Usage 0
`&cProper usage is /{0}`
## Commands Usage 1
`&cProper usage is /{0} {1}`
## Commands Usage 2
`&cProper usage is /{0} {1} {2}`
## Commands Usage 3
`&cProper usage is /{0} {1} {2} {3}`
## Commands Usage 3 XP
`&cProper usage is /{0} {1} {2} {3}&7 (You can include -s at the end to execute the command without informing the player, effectively silencing it)`
## Commands Usage FullClassName
`classname`
## Commands Usage Level
`level`
## Commands Usage Message
`message`
## Commands Usage Page
`page`
## Commands Usage PartyName
`name`
## Commands Usage Password
`password`
## Commands Usage Player
`player`
## Commands Usage Rate
`rate`
## Commands Usage Skill
`skill`
## Commands Usage SubSkill
`subskill`
## Commands Usage XP
`xp`
## Commands Description mmoinfo
`Read details about a skill or mechanic.`
## Commands MmoInfo Mystery
`&7You haven't unlocked this skill yet, but when you do you will be able to read details about it here!`
## Commands MmoInfo NoMatch
`That subskill doesn't exist!`
## Commands MmoInfo Header
`&3-=[]=====[]&6 MMO Info &3[]=====[]=-`
## Commands MmoInfo SubSkillHeader
`&6Name:&e {0}`
## Commands MmoInfo DetailsHeader
`&3-=[]=====[]&a Details &3[]=====[]=-`
## Commands MmoInfo OldSkill
`&7mcMMO skills are being converted into an improved modular skill system, unfortunately this skill has not been converted yet and lacks detailed stats. The new system will allow for faster release times for new mcMMO skills and greater flexibility with existing skills.`
## Commands MmoInfo Mechanics
`&3-=[]=====[]&6 Mechanics &3[]=====[]=-`
## Commands MmoInfo Stats
`STATS: {0}`
## Commands Mmodebug Toggle
`mcMMO Debug Mode is now &6{0}&7, use this command again to toggle. With debug mode true, you can punch blocks to print useful information used for support.`
## mcMMO NoInvites
`&cYou have no invites at this time`
## mcMMO NoPermission
`&4Insufficient permissions.`
## mcMMO NoSkillNote
`&8If you don't have access to a skill it will not be shown here.`
##party
## Party Forbidden
`[mcMMO] Parties not permitted on this world (See Permissions)`
## Party Help 0
`&cProper usage is &3{0} <player> [password].`
## Party Help 1
`&cTo create a party, use &3{0} <name> [password].`
## Party Help 2
`&cConsult &3{0} &cfor more information`
## Party Help 3
`&cUse &3{0} <player> [password] &cto join or &3{1} &cto quit`
## Party Help 4
`&cTo lock or unlock your party, use &3{0}`
## Party Help 5
`&cTo password protect your party, use &3{0} <password>`
## Party Help 6
`&cTo kick a player from your party, use &3{0} <player>`
## Party Help 7
`&cTo transfer ownership of your party, use &3{0} <player>`
## Party Help 8
`&cTo disband your party, use &3{0}`
## Party Help 9
`&cUse &3{0} &cto share items with party members`
## Party Help 10
`&cUse &3{0} &cto enable XP sharing with party members`
## Party InformedOnJoin
`{0} &ahas joined your party`
## Party InformedOnQuit
`{0} &ahas left your party`
## Party InformedOnNameChange
`&6{0} &ahas set the party name to &f{1}`
## Party InvalidName
`&4That is not a valid party name.`
## Party Invite Self
`&cYou can't invite yourself!`
## Party IsLocked
`&cThis party is already locked!`
## Party IsntLocked
`&cThis party is not locked!`
## Party Locked
`&cParty is locked, only party leader may invite.`
## Party NotInYourParty
`&4{0} is not in your party`
## Party NotOwner
`&4You are not the party leader.`
## Party Target NotOwner
`&4{0} is not the party leader.`
## Party Owner New
`&a{0} is the new party leader.`
## Party Owner NotLeader
`&4You are no longer the party leader.`
Party.Owner.Player =&aYou are now the party leader.
## Party Password None
`&cThis party is password protected. Please provide a password to join.`
## Party Password Incorrect
`&cParty password is incorrect.`
## Party Password Set
`&aParty password set to {0}`
## Party Password Removed
`&aParty password has been cleared.`
## Party Player Invalid
`&cThat is not a valid player.`
## Party NotOnline
`&4{0} is not online!`
## Party Player InSameParty
`&c{0} already is in your party!`
## Party PlayerNotInParty
`&4{0} is not in a party`
## Party Specify
`&cYou must specify a party.`
## Party Teleport Dead
`&cYou can't teleport to a dead player.`
## Party Teleport Hurt
`&cYou have been hurt in the last {0} seconds and cannot teleport.`
## Party Teleport Player
`&aYou have teleported to {0}.`
## Party Teleport Self
`&cYou can't teleport to yourself!`
## Party Teleport Target
`&a{0} has teleported to you.`
## Party Teleport Disabled
`&c{0} doesn't allow party teleportation.`
## Party Rename Same
`&cThat is already the name of your party!`
## Party Join Self
`&cYou can't join yourself!`
## Party Unlocked
`&7Party is unlocked`
## Party Disband
`&7The party has been disbanded`
## Party Alliance Formed
`&7Your party is now allies with &a{0}`
## Party Alliance Disband
`&7Your party is no longer allies with &c{0}`
## Party Status Locked
`&4(INVITE-ONLY)`
## Party Status Unlocked
`&2(OPEN)`
## Party LevelUp
`&eParty level increased by {0}. Total ({1})`
## Party Feature Chat
`Party Chat`
## Party Feature Teleport
`Party Teleport`
## Party Feature Alliance
`Alliances`
## Party Feature ItemShare
`Item Sharing`
## Party Feature XpShare
`XP Sharing`
## Party Feature Locked Chat
`LOCKED UNTIL {0}+ (PARTY CHAT)`
## Party Feature Locked Teleport
`LOCKED UNTIL {0}+ (PARTY TELEPORT)`
## Party Feature Locked Alliance
`LOCKED UNTIL {0}+ (ALLIANCES)`
## Party Feature Locked ItemShare
`LOCKED UNTIL {0}+ (ITEM SHARING)`
## Party Feature Locked XpShare
`LOCKED UNTIL {0}+ (XP SHARING)`
## Party Feature Disabled 1
`&cParty chat is not unlocked yet.`
## Party Feature Disabled 2
`&cParty teleport is not unlocked yet.`
## Party Feature Disabled 3
`&cParty alliances are not unlocked yet.`
## Party Feature Disabled 4
`&cParty item sharing is not unlocked yet.`
## Party Feature Disabled 5
`&cParty XP sharing is not unlocked yet.`
## Party ShareType Xp
`XP`
## Party ShareType Item
`ITEM`
## Party ShareMode None
`NONE`
## Party ShareMode Equal
`EQUAL`
## Party ShareMode Random
`RANDOM`
## Party ItemShare Category Loot
`Loot`
## Party ItemShare Category Mining
`Mining`
## Party ItemShare Category Herbalism
`Herbalism`
## Party ItemShare Category Woodcutting
`Woodcutting`
## Party ItemShare Category Misc
`Misc`
##xp
## Commands XPGain Acrobatics
`Falling`
## Commands XPGain Alchemy
`Brewing Potions`
## Commands XPGain Archery
`Attacking Monsters`
## Commands XPGain Axes
`Attacking Monsters`
## Commands XPGain Child
`Gains levels from Parent Skills`
## Commands XPGain Excavation
`Digging and finding treasures`
## Commands XPGain Fishing
`Fishing (Go figure!)`
## Commands XPGain Herbalism
`Harvesting Herbs`
## Commands XPGain Mining
`Mining Stone & Ore`
## Commands XPGain Repair
`Repairing`
## Commands XPGain Swords
`Attacking Monsters`
## Commands XPGain Taming
`Animal Taming, or combat w/ your wolves`
## Commands XPGain Unarmed
`Attacking Monsters`
## Commands XPGain Woodcutting
`Chopping down trees`
## Commands XPGain
`&8XP GAIN: &f{0}`
## Commands xplock locked
`&6Your XP BAR is now locked to {0}!`
## Commands xplock unlocked
`&6Your XP BAR is now &aUNLOCKED&6!`
## Commands xprate modified
`&cThe XP RATE was modified to {0}`
## Commands xprate over
`&cmcMMO XP Rate Event is OVER!!`
## Commands xprate proper 0
`&cProper usage to change the XP rate is /xprate <integer> <true/false>`
## Commands xprate proper 1
`&cProper usage to restore the XP rate to default is /xprate reset`
## Commands xprate proper 2
`&cPlease specify true or false to indicate if this is an xp event or not`
## Commands NegativeNumberWarn
`Don't use negative numbers!`
## Commands Event Start
`&amcMMO&6 Event!`
## Commands Event Stop
`&amcMMO&3 Event Over!`
## Commands Event Stop Subtitle
`&aI hope you had fun!`
## Commands Event XP
`&3XP Rate is now &6{0}&3x`
## Commands xprate started 0
`&6XP EVENT FOR mcMMO HAS STARTED!`
## Commands xprate started 1
`&6mcMMO XP RATE IS NOW {0}x!`

# Admin Notifications
## Server ConsoleName
`&e[Server]`
## Notifications.Admin XPRate Start Self
`&7You have set the global XP rate multiplier to &6{0}x`
## Notifications.Admin XPRate End Self
`&7You ended the XP rate event.`
## Notifications.Admin XPRate End Others
`{0} &7has ended the XP rate event`
## Notifications.Admin XPRate Start Others
`{0} &7has started or modified an XP rate event with global multiplier {1}x`
## Notifications Admin Format Others
`&6(&amcMMO &3Admin&6) &7{0}`
## Notifications Admin Format Self
`&6(&amcMMO&6) &7{0}`

# Event
## XPRate Event
`&6mcMMO is currently in an XP rate event! XP rate is {0}x!`

#GUIDES
## Guides Available
`&7Guide for {0} available - type /{1} ? [page]`
## Guides Header=&6-=&a{0} Guide&6
`-`
## Guides Page Invalid
`Not a valid page number!`
## Guides Page OutOfRange
`That page does not exist, there are only {0} total pages.`
## Guides Usage
` Usage is /{0} ? [page]`
##Acrobatics
## Guides Acrobatics Section 0
`&3About Acrobatics:\n&eAcrobatics is the art of moving Gracefuly in mcMMO.\n&eIt provides combat bonuses and environment damage bonuses.\n\n&3XP GAIN:\n&eTo gain XP in this skill you need to perform a dodge\n&ein combat or survive falls from heights that damage you.`
## Guides Acrobatics Section 1
`&3How does Rolling work?\n&eYou have a passive chance when you take fall damage\n&eto negate the damage done. You can hold the sneak button to\n&edouble your chances during the fall.\n&eThis triggers a Graceful Roll instead of a standard one.\n&eGraceful Rolls are like regular rolls but are twice as likely to\n&eoccur and provide more damage safety than regular rolls.\n&eRolling chance is tied to your skill level`
## Guides Acrobatics Section 2
`&3How does Dodge work?\n&eDodge is a passive chance when you are\n&einjured in combat to halve the damage taken.\n&eIt is tied to your skill level.`
##Alchemy
## Guides Alchemy Section 0
`[[DARK_AQUA]]About Alchemy:\n[[YELLOW]]Alchemy is about brewing potions.\n[[YELLOW]]It provides a speed increase in the potion brew time, as well\n[[YELLOW]]as the addition of new (previously) unobtainable potions.\n\n\n[[DARK_AQUA]]XP GAIN:\n[[YELLOW]]To gain XP in this skill you need to brew potions.`
## Guides Alchemy Section 1
`[[DARK_AQUA]]How does Catalysis work?\n[[YELLOW]]Catalysis speeds of the brewing process, with a\n[[YELLOW]]max speed of 4x at level 1000.\n[[YELLOW]]This ability is unlocked at level 100 by default.`
## Guides Alchemy Section 2
`[[DARK_AQUA]]How does Concoctions work?\n[[YELLOW]]Concoctions allows brewing of more potions with custom ingredients.\n[[YELLOW]]Which special ingredients are unlocked is determined\n[[YELLOW]]by your Rank. There are 8 ranks to unlock.`
## Guides Alchemy Section 3
`[[DARK_AQUA]]Concoctions tier 1 ingredients:\n[[YELLOW]]Blaze Powder, Fermented Spider Eye, Ghast Tear, Redstone,\n[[YELLOW]]Glowstone Dust, Sugar, Glistering Melon, Golden Carrot,\n[[YELLOW]]Magma Cream, Nether Wart, Spider Eye, Suplhur, Water Lily,\n[[YELLOW]]Pufferfish\n[[YELLOW]](Vanilla Potions)`
## Guides Alchemy Section 4
`[[DARK_AQUA]]Concoctions tier 2 ingredients:\n[[YELLOW]]Carrot (Potion of Haste)\n[[YELLOW]]Slimeball (Potion of Dullness)\n\n[[DARK_AQUA]]Concoctions tier 3 ingredients:\n[[YELLOW]]Quartz (Potion of Absorption)\n[[YELLOW]]Rabbit's Foot (Potion of Leaping)`
## Guides Alchemy Section 5
`[[DARK_AQUA]]Concoctions tier 4 ingredients:\n[[YELLOW]]Apple (Potion of Health Boost)\n[[YELLOW]]Rotten Flesh (Potion of Hunger)\n\n[[DARK_AQUA]]Concoctions tier 5 ingredients:\n[[YELLOW]]Brown Mushroom (Potion of Nausea)\n[[YELLOW]]Ink Sack (Potion of Blindness)`
## Guides Alchemy Section 6
`[[DARK_AQUA]]Concoctions tier 6 ingredients:\n[[YELLOW]]Fern (Potion of Saturation)\n\n[[DARK_AQUA]]Concoctions tier 7 ingredients:\n[[YELLOW]]Poisonous Potato (Potion of Decay)\n\n[[DARK_AQUA]]Concoctions tier 8 ingredients:\n[[YELLOW]]Regular Golden Apple (Potion of Resistance)`

##Archery
## Guides Archery Section 0
`&3About Archery:\n&eArchery is about shooting with your bow and arrow.\n&eIt provides various combat bonuses, such as a damage boost\n&ethat scales with your level and the ability to daze your\n&eopponents in PvP. In addition to this, you can retrieve\n&esome of your spent arrows from the corpses of your foes.\n\n\n&3XP GAIN:\n&eTo gain XP in this skill you need to shoot mobs or\n&eother players.`
## Guides Archery Section 1
`&3How does Skill Shot work?\n&eSkill Shot provides additional damage to your shots.\n&eThe bonus damage from Skill Shot increases as you\n&elevel in Archery.\n&eWith the default settings, your archery damage increases 10%\n&eevery 50 levels, to a maximum of 200% bonus damage.`
## Guides Archery Section 2
`&3How does Daze work?\n&eYou have a passive chance to daze other players when\n&eyou shoot them. When Daze triggers it forces your opponents\n&eto look straight up for a short duration.\n&eA Daze shot also deals an additional 4 damage (2 hearts).`
## Guides Archery Section 3
`&3How does Arrow Retrieval work?\n&eYou have a passive chance to retrieve some of your arrows\n&ewhen you kill a mob with your bow.\n&eThis chance increases as you level in Archery.\n&eBy default, this ability increases by 0.1% per level, up to 100%\n&eat level 1000.`
##Axes
## Guides Axes Section 0
`&3About Axes:\n&eWith the Axes skill you can use your axe for much more then\n&ejust deforesting! You can hack and chop away at mobs\n&eand players to gain XP, hitting mobs with the effect of\n&eknockback and inflicting DEADLY criticals on mobs and players.\n&eYour axe also becomes a hand-held woodchipper,\n&ebreaking down the enemy's armor with ease as your level\n&eincreases.\n&3XP GAIN:\n&eTo gain XP in this skill you need hit other mobs or players\n&ewith an Axe.`
## Guides Axes Section 1
`&3How does Skull Splitter work?\n&eThis ability allows you to deal an AoE (Area of Effect) hit.\n&eThis AoE hit will deal half as much damage as you did to the\n&emain target, so it's great for clearing out large piles of mobs.`
## Guides Axes Section 2
`&3How does Critical Strikes work?\n&eCritical Strikes is a passive ability which gives players a\n&echance to deal additional damage.\n&eWith the default settings, every 2 skill levels in Axes awards a\n&e0.1% chance to deal a Critical Strike, causing 2.0 times damage\n&eto mobs or 1.5 times damage against other players.`
## Guides Axes Section 3
`&3How does Axe Mastery work?\n&eAxe Mastery is a passive ability that will add additional damage\n&eto your hits when using Axes.\n&eBy default, the bonus damage increases by 1 every 50 levels,\n&eup to a cap of 4 extra damage at level 200.`
## Guides Axes Section 4
`&3How does Armor Impact work?\n&eStrike with enough force to shatter armor!\n&eArmor Impact has a passive chance to damage your\n&eopponent's armor. This damage increases as you level in Axes.`
## Guides Axes Section 5
`&3How does Greater Impact work?\n&eYou have a passive chance to achieve a greater impact when\n&ehitting mobs or players with your axe.\n&eBy default this chance is 25%. This passive ability has an\n&eextreme knockback effect, similar to the Knockback II\n&eenchantment. In addition, it deals bonus damage to the target.`
##Excavation
## Guides Excavation Section 0
`&3About Excavation:\n&eExcavation is the act of digging up dirt to find treasures.\n&eBy excavating the land you will find treasures.\n&eThe more you do this the more treasures you can find.\n\n&3XP GAIN:\n&eTo gain XP in this skill you must dig with a shovel in hand.\n&eOnly certain materials can be dug up for treasures and XP.`
## Guides Excavation Section 1
`&3Compatible Materials:\n&eGrass, Dirt, Sand, Clay, Gravel, Mycelium, Soul Sand, Snow`
## Guides Excavation Section 2
`&3How to use Giga Drill Breaker:\n&eWith a shovel in hand right click to ready your tool.\n&eOnce in this state you have about 4 seconds to make\n&econtact with Excavation compatible materials this will\n&eactivate Giga Drill Breaker.`
## Guides Excavation Section 3
`&3What is Giga Drill Breaker?\n&eGiga Drill Breaker is an ability with a cooldown\n&etied to Excavation skill. It triples your chance\n&eof finding treasures and enables instant break\n&eon Excavation materials.`
## Guides Excavation Section 4
`&3How does Archaeology work?\n&eEvery possible treasure for Excavation has its own\n&eskill level requirement for it to drop, as a result it's\n&edifficult to say how much it is helping you.\n&eJust keep in mind that the higher your Excavation skill\n&eis, the more treasures that can be found.\n&eAnd also keep in mind that each type of Excavation\n&ecompatible material has its own unique list of treasures.\n&eIn other words you will find different treasures in Dirt\n&ethan you would in Gravel.`
## Guides Excavation Section 5
`&3Notes about Excavation:\n&eExcavation drops are completely customizeable\n&eSo results vary server to server.`
##Fishing
## Guides Fishing Section 0
`&3About Fishing:\n&eWith the Fishing skill, Fishing is exciting again!\n&eFind hidden treasures, and shake items off mobs.\n\n&3XP GAIN:\n&eCatch fish.`
## Guides Fishing Section 1
`&3How does Treasure Hunter work?\n&eThis ability allows you to find treasure from fishing \n&ewith a small chance of the items being enchanted.\n&eEvery possible treasure for Fishing has a chance\n&eto drop on any level. It depends however\n&ewhat the rarity of the item is how often it will drop.\n&eThe higher your Fishing skill is, the better\n&eyour chances are to find better treasures.`
## Guides Fishing Section 2
`&3How does Ice Fishing work?\n&eThis passive skill allows you to fish in ice lakes!\n&eCast your fishing rod in an ice lake and the ability will\n&ecreate a small hole in the ice to fish in.`
## Guides Fishing Section 3
`&3How does Master Angler work?\n&eThis passive skill increases the bite chance while fishing.\n&eWhen you've unlocked this ability, fishing while in\n&ea boat improves odds of catching a fish.`
## Guides Fishing Section 4
`&3How does Shake work?\n&eThis active ability allows you to shake items loose from mobs\n&eby hooking them with the fishing rod. \n&eMobs will drop items they would normally drop on death.\n&eIt is also possible to acquire mob skulls, which are normally \n&eunobtainable in survival mode.`
## Guides Fishing Section 5
`&3How does Fisherman's Diet work?\n&eThis passive skill increases the amount of hunger restored \n&efrom eating fish.`
## Guides Fishing Section 6
`&3Notes about Fishing:\n&eFishing drops are completely customizable,\n&eso results vary server to server.`
##Herbalism
## Guides Herbalism Section 0
`&3About Herbalism:\n&eHerbalism is about collecting herbs and plants.\n\n\n&3XP GAIN:\n&eCollect plants and herbs.`
## Guides Herbalism Section 1
`&3Compatible Blocks\n&eWheat, Potatoes, Carrots, Melons, \n&ePumpkins, Sugar Canes, Cocoa Beans, Flowers, Cacti, Mushrooms,\n&eNether Wart, Lily Pads, and Vines.`
## Guides Herbalism Section 2
`&3How does Green Terra work?\n&eGreen Terra is an active ability, you can right-click\n&ewhile holding a hoe to activate Green Terra.\n&eGreen Terra grants players a chance to get 3x drops from\n&eharvesting plants. It also gives players the ability to\n&espread life into blocks and transform them using seeds\n&efrom your inventory.`
## Guides Herbalism Section 3
`&3How does Green Thumb (Crops) work?\n&eThis passive ability will automatically replant crops when\n&eharvesting.\n&eYour chance of success depends on your Herbalism skill.`
## Guides Herbalism Section 4
`&3How does Green Thumb (Cobble/Stone Brick/Dirt) work?\n&eThis active ability allows you to turn blocks into their\n&e"plant-related" counterparts. You can do this by right-clicking\n&ea block, while holding seeds. This will consume 1 seed.`
## Guides Herbalism Section 5
`&3How does Farmer's Diet work?\n&eThis passive skill increases the amount of hunger restored \n&ewhen eating Bread, Cookies, Melons, Mushroom Soup, Carrots,\n&eand Potatoes.`
## Guides Herbalism Section 6
`&3How does Hylian Luck work?\n&eThis passive ability gives you a chance to find rare items\n&ewhen certain blocks are broken with a sword.`
## Guides Herbalism Section 7
`&3How do Double Drops work?\n&eThis passive ability gives players more yield from their\n&eharvests.`
##Mining
## Guides Mining Section 0
`&3About Mining:\n&eMining consists of mining stone and ores. It provides bonuses\n&eto the amount of materials dropped while mining.\n\n&3XP GAIN:\n&eTo gain XP in this skill, you must mine with a pickaxe in hand.\n&eOnly certain blocks award XP.`
## Guides Mining Section 1
`&3Compatible Materials:\n&eStone, Coal Ore, Iron Ore, Gold Ore, Diamond Ore, Redstone Ore,\n&eLapis Ore, Obsidian, Mossy Cobblestone, Ender Stone,\n&eGlowstone, and Netherrack.`
## Guides Mining Section 2
`&3How to use Super Breaker:\n&eWith a pickaxe in your hand, right click to ready your tool.\n&eOnce in this state, you have about 4 seconds to make contact\n&ewith Mining compatible materials, which will activate Super\n&eBreaker.`
## Guides Mining Section 3
`&3What is Super Breaker?\n&eSuper Breaker is an ability with a cooldown tied to the Mining\n&eskill. It triples your chance of extra items dropping and\n&eenables instant break on Mining materials.`
## Guides Mining Section 4
`&3How to use Blast Mining:\n&eWith a pickaxe in hand,\n&ecrouch and right-click on TNT from a distance. This will cause the TNT\n&eto instantly explode.`
## Guides Mining Section 5
`&3How does Blast Mining work?\n&eBlast Mining is an ability with a cooldown tied to the Mining\n&eskill. It gives bonuses when mining with TNT and allows you\n&eto remote detonate TNT. There are three parts to Blast Mining.\n&eThe first part is Bigger Bombs, which increases blast radius.\n&eThe second is Demolitions Expert, which decreases damage\n&efrom TNT explosions. The third part simply increases the\n&eamount of ores dropped from TNT and decreases the\n&edebris dropped.`
##Repair
## Guides Repair Section 0
`&3About Repair:\n&eRepair allows you to use an iron block to repair armor and\n&etools.\n\n&3XP GAIN:\n&eRepair tools or armor using the mcMMO Anvil. This is an\n&eiron block by default and should not be confused with\n&ethe Vanilla Minecraft Anvil.`
## Guides Repair Section 1
`&3How can I use Repair?\n&ePlace down a mcMMO Anvil and right-click to repair the item \n&eyou're currently holding. This consumes 1 item on every use.`
## Guides Repair Section 2
`&3How does Repair Mastery work?\n&eRepair Mastery increases the repair amount. The extra amount\n&erepaired is influenced by your Repair skill level.`
## Guides Repair Section 3
`&3How does Super Repair work?\n&eSuper Repair is a passive ability. When repairing an item,\n&eit grants players a chance to repair an item with\n&edouble effectiveness.`
## Guides Repair Section 4
`&3How does Arcane Forging work?\n&eThis passive ability allows you to repair items with a certain\n&echance of maintaining its enchantments. The enchants may be\n&ekept at their existing levels, downgraded to a lower level,\n&eor lost entirely.`
##Salvage
## Guides Salvage Section 0
`&3About Salvage:\n&eSalvage allows you to use a gold block to salvage armor and\n&etools.\n\n&3XP GAIN:\n&eSalvage is a child skill of Repair and Fishing, your Salvage\n&eskill level is based on your Fishing and Repair skill levels.`
## Guides Salvage Section 1
`&3How can I use Salvage?\n&ePlace down a mcMMO Salvage Anvil and right-click to salvage\n&ethe item you're currently holding. This will break apart the item,\n&eand give back materials used to craft the item.\n\n&eFor example, salvaging an iron pickaxe will give you iron bars.`
## Guides Salvage Section 2
`&3How does Advanced Salvage work?\n&eWhen unlocked, this ability allows you to salvage damaged items.\n&eThe yield percentage increases as you level up. A higher yield\n&emeans that you can get more materials back.\n&eWith advanced salvage you will always get 1 material back,\n&eunless the item is too damaged. So you don't have to worry\n&eabout destroying items without getting anything in return.`
## Guides Salvage Section 3
`&3To illustrate how this works, here's an example:\n&eLet's say we salvage a gold pickaxe which is damaged for 20%,\n&ethis means that the maximum amount you could get is only 2\n&e(because the pick is crafted with 3 ingots - each worth\n&e33,33% durability) which is equal to 66%. If your yield\n&epercentage is below 66% you are not able to get 2 ingots.\n&eIf it is above this value you are able to gain the "full amount",\n&ewhich means that you will get 2 ingots.`
## Guides Salvage Section 4
`&3How does Arcane Salvage work?\n&eThis ability allows you to get enchanted books when salvaging\n&eenchanted items. Depending on your level the chance of\n&esuccessfully extracting a full or partial enchantment varies.\n\n&eWhen an enchantment is partially extracted, the enchantment\n&ebook will have a lower level enchantment compared to what\n&eit was on the item.`
##Smelting
## Guides Smelting Section 0
`Coming soon...`
##Swords
## Guides Swords Section 0
`&3About Swords:\n&eThis skill awards combat bonuses to anyone fighting with a\n&esword.\n\n&3XP GAIN:\n&eXP is gained based on the amount of damage dealt to mobs or \n&eother players when wielding a sword.`
## Guides Swords Section 1
`&3How does Serrated Strikes work?\n&eSerrated Strikes is an active ability, you can activate it by\n&eright-clicking with a sword. This ability allows you to deal \n&ean AoE (Area of Effect) hit. This AoE will do a bonus 25%\n&edamage and may apply Rupture`
## Guides Swords Section 2
`&3How does Counter Attack work?\n&eCounter Attack is an active ability. When blocking and taking\n&ehits from mobs, you will have a chance to reflect 50% of \n&ethe damage that was taken.`
## Guides Swords Section 3
`&3How does Rupture work?\n&eRupture causes enemies to take damage every two seconds. The \n&etarget will bleed until the effect wears off, or death, \n&ewhichever comes first.\n&eThe duration of the bleed is increased by your sword skill.`
##Taming
## Guides Taming Section 0
`&3About Taming:\n&eTaming will give players various combat bonuses when using\n&etamed wolves.\n\n&3XP GAIN:\n&eTo gain XP in this skill, you need to tame wolves/ocelots or\n&eget into combat with your wolves.`
## Guides Taming Section 1
`&3How does Call of the Wild work?\n&eCall of the Wild is an active ability that will allow you to summon\n&ea wolf or an ocelot by your side. You can do this by\n&esneaking + left-clicking while holding bones or fish.`
## Guides Taming Section 2
`&3How does Beast Lore work?\n&eBeast Lore allows players to inspect pets and to check the\n&estats of wolves and ocelots. Left-click a wolf or ocelot to use\n&eBeast Lore.`
## Guides Taming Section 3
`&3How does Gore work?\n&eGore is a passive ability that has a chance of inflicting a\n&ebleeding effect on your wolves' targets.`
## Guides Taming Section 4
`&3How does Sharpened Claws work?\n&eSharpened Claws provides a damage bonus to damage dealt\n&eby wolves. The damage bonus depends on your Taming level.`
## Guides Taming Section 5
`&3How does Environmentally Aware work?\n&eThis passive ability will allow wolves to teleport to you when\n&ethey get near hazards, such as Cacti/Lava. It will also give\n&ewolves fall damage immunity.`
## Guides Taming Section 6
`&3How does Thick Fur work?\n&eThis passive ability will reduce damage and make wolves\n&efire resistant.`
## Guides Taming Section 7
`&3How does Shock Proof work?\n&eThis passive ability reduces damage done to wolves\n&efrom explosions.`
## Guides Taming Section 8
`&3How does Fast Food Service work?\n&eThis passive ability gives wolves a chance to heal whenever\n&ethey perform an attack.`
##Unarmed
## Guides Unarmed Section 0
`&3About Unarmed:\n&eUnarmed will give players various combat bonuses when using\n&eyour fists as a weapon. \n\n&3XP GAIN:\n&eXP is gained based on the amount of damage dealt to mobs \n&eor other players when unarmed.`
## Guides Unarmed Section 1
`&3How does Berserk work?\n&eBeserk is an active ability that is activated by\n&eright-clicking. While in Beserk mode, you deal 50% more\n&edamage and you can break weak materials instantly, such as\n&eDirt and Grass.`
## Guides Unarmed Section 2
`&3How does Steel Arm Style work?\n&eSteel Arm Style increases the damage dealt when hitting mobs or\n&eplayers with your fists.`
## Guides Unarmed Section 3
`&3How does Arrow Deflect work?\n&eArrow Deflect is a passive ability that gives you a chance\n&eto deflect arrows shot by Skeletons or other players.\n&eThe arrow will fall harmlessly to the ground.`
## Guides Unarmed Section 4
`&3How does Iron Grip work?\n&eIron Grip is a passive ability that counters disarm. As your\n&eunarmed level increases, the chance of preventing a disarm increases.`
## Guides Unarmed Section 5
`&3How does Disarm work?\n&eThis passive ability allows players to disarm other players,\n&ecausing the target's equipped item to fall to the ground.`
##Woodcutting
## Guides Woodcutting Section 0
`&3About Woodcutting:\n&eWoodcutting is all about chopping down trees.\n\n&3XP GAIN:\n&eXP is gained whenever you break log blocks.`
## Guides Woodcutting Section 1
`&3How does Tree Feller work?\n&eTree Feller is an active ability, you can right-click\n&ewhile holding an ax to activate Tree Feller. This will\n&ecause the entire tree to break instantly, dropping all\n&eof its logs at once.`
## Guides Woodcutting Section 2
`&3How does Leaf Blower work?\n&eLeaf Blower is a passive ability that will cause leaf\n&eblocks to break instantly when hit with an axe. By default,\n&ethis ability unlocks at level 100.`
## Guides Woodcutting Section 3
`&3How do Double Drops work?\n&eThis passive ability gives you a chance to obtain an extra\n&eblock for every log you chop.`
#INSPECT
## Inspect Offline
` &cYou do not have permission to inspect offline players!`
## Inspect OfflineStats
`mcMMO Stats for Offline Player &e{0}`
## Inspect Stats
`&amcMMO Stats for &e{0}`
## Inspect TooFar
`You are too far away to inspect that player!`
#ITEMS
## Item ChimaeraWing Fail
`&c**CHIMAERA WING FAILED!**`
## Item ChimaeraWing Pass
`**CHIMAERA WING**`
## Item ChimaeraWing Name
`Chimaera Wing`
## Item ChimaeraWing Lore
`&7Teleports you to your bed.`
## Item ChimaeraWing NotEnough
`You need &e{0}&c more &6{1}&c!`
## Item NotEnough
`You need &e{0}&c more &6{1}&c!`
## Item Generic Wait
`You need to wait before you can use this again! &e({0}s)`
## Item Injured Wait
`You were injured recently and must wait to use this. &e({0}s)`
## Item FluxPickaxe Name
`Flux Pickaxe`
## Item FluxPickaxe Lore 1
`&7Has a chance of instantly smelting ores.`
## Item FluxPickaxe Lore 2
`&7Requires Smelting level {0}+`
#TELEPORTATION
## Teleport Commencing
`&7Commencing teleport in &6({0}) &7seconds, please stand still...`
## Teleport Cancelled
`&4Teleportation canceled!`
#SKILLS
## Skills Child
`&6(CHILD SKILL)`
## Skills Disarmed
`&4You have been disarmed!`
## Skills Header
`-----[] &a{0}&c []-----`
## Skills NeedMore
`&4You need more &7{0}`
## Skills NeedMore Extra
`&4You need more &7{0}{1}`
## Skills Parents
` PARENTS`
## Skills Stats
`{0}&a{1}&3 XP(&7{2}&3/&7{3}&3)`
## Skills ChildStats
`{0}&a{1}`
## Skills MaxXP
`Max`
## Skills TooTired
`You are too tired to use that ability again. &e({0}s)`
## Skills TooTired Named
`&7(&6{0}&e {1}s&7)`
## Skills TooTired Extra
`&6{0} &eSuper Ability CDs - {1}`
## Skills Cancelled
`&6{0} &ccancelled!`
## Skills ConfirmOrCancel
`&aRight-click again to confirm &6{0}&a. Left-click to cancel.`
## Skills AbilityGateRequirementFail
`&7You require &e{0}&7 more levels of &3{1}&7 to use this super ability.`
#STATISTICS
## Stats Header Combat=&6-=COMBAT SKILLS
`-`
## Stats Header Gathering=&6-=GATHERING SKILLS
`-`
## Stats Header Misc=&6-=MISC SKILLS
`-`
## Stats Own Stats
`&a[mcMMO] Stats`
#PERKS
## Perks XP Name
`Experience`
## Perks XP Desc
`Receive boosted XP in certain skills.`
## Perks Lucky Name
`Luck`
## Perks Lucky Desc
`Gives {0} skills and abilities a 33.3% better chance to activate.`
## Perks Lucky Desc Login
`Gives certain skills and abilities a 33.3% better chance to activate.`
## Perks Lucky Bonus
`&6 ({0} with Lucky Perk)`
## Perks Cooldowns Name
`Fast Recovery`
## Perks Cooldowns Desc
`Cuts cooldown duration by {0}.`
## Perks ActivationTime Name
`Endurance`
## Perks ActivationTime Desc
`Increases ability activation time by {0} seconds.`
## Perks ActivationTime Bonus
`&6 ({0}s with Endurance Perk)`
#HARDCORE
## Hardcore Mode Disabled
`&6[mcMMO] Hardcore mode {0} disabled for {1}.`
## Hardcore Mode Enabled
`&6[mcMMO] Hardcore mode {0} enabled for {1}.`
## Hardcore DeathStatLoss Name
`Skill Death Penalty`
## Hardcore DeathStatLoss PlayerDeath
`&6[mcMMO] &4You have lost &9{0}&4 levels from death.`
## Hardcore DeathStatLoss PercentageChanged
`&6[mcMMO] The stat loss percentage was changed to {0}.`
## Hardcore Vampirism Name
`Vampirism`
## Hardcore Vampirism Killer Failure
`&6[mcMMO] &e{0}&7 was too unskilled to grant you any knowledge.`
## Hardcore Vampirism Killer Success
`&6[mcMMO] &3You have stolen &9{0}&3 levels from &e{1}.`
## Hardcore Vampirism Victim Failure
`&6[mcMMO] &e{0}&7 was unable to steal knowledge from you!`
## Hardcore Vampirism Victim Success
`&6[mcMMO] &e{0}&4 has stolen &9{1}&4 levels from you!`
## Hardcore Vampirism PercentageChanged
`&6[mcMMO] The stat leech percentage was changed to {0}.`
#MOTD
## MOTD Donate
`&3Donation Info:`
## MOTD Hardcore Enabled
`&6[mcMMO] &3Hardcore Mode enabled: &4{0}`
## MOTD Hardcore DeathStatLoss Stats
`&6[mcMMO] &3Skill Death Penalty: &4{0}%`
## MOTD Hardcore Vampirism Stats
`&6[mcMMO] &3Vampirism Stat Leech: &4{0}%`
## MOTD PerksPrefix
`&6[mcMMO Perks]`
## MOTD Version
`&6[mcMMO] Running version &3{0}`
## MOTD Website
`&6[mcMMO] &a{0}&e - mcMMO Website`
#SMELTING
## Smelting SubSkill UnderstandingTheArt Name
`Understanding The Art`
## Smelting SubSkill UnderstandingTheArt Description
`Maybe you're spending a bit too much time smelting in the caves.\nPowers up various properties of Smelting.`
## Smelting SubSkill UnderstandingTheArt Stat
`Vanilla XP Multiplier: &e{0}x`
## Smelting Ability Locked 0
`LOCKED UNTIL {0}+ SKILL (VANILLA XP BOOST)`
## Smelting Ability Locked 1
`LOCKED UNTIL {0}+ SKILL (FLUX MINING)`
## Smelting SubSkill FuelEfficiency Name
`Fuel Efficiency`
## Smelting SubSkill FuelEfficiency Description
`Increase the burn time of fuel used in furnaces when smelting`
## Smelting SubSkill FuelEfficiency Stat
`Fuel Efficiency Multiplier: &e{0}x`
## Smelting SubSkill SecondSmelt Name
`Second Smelt`
## Smelting SubSkill SecondSmelt Description
`Double the resources gained from smelting`
## Smelting SubSkill SecondSmelt Stat
`Second Smelt Chance`
## Smelting Effect 4
`Vanilla XP Boost`
## Smelting Effect 5
`Increase vanilla XP gained while smelting`
## Smelting SubSkill FluxMining Name
`Flux Mining`
## Smelting SubSkill FluxMining Description
`Chance for ores to be instantly smelted while mining`
## Smelting SubSkill FluxMining Stat
`Flux Mining Chance`
## Smelting Listener
`Smelting:`
## Smelting SkillName
`SMELTING`
#COMMAND DESCRIPTIONS
## Commands Description addlevels
`Add mcMMO levels to a user`
## Commands Description adminchat
`Toggle mcMMO admin chat on/off or send admin chat messages`
## Commands Description addxp
`Add mcMMO XP to a user`
## Commands Description hardcore
`Modify the mcMMO hardcore percentage or toggle hardcore mode on/off`
## Commands Description inspect
`View detailed mcMMO info on another player`
## Commands Description mcability
`Toggle mcMMO abilities being readied on right-click on/off`
## Commands Description mccooldown
`View all of the mcMMO ability cooldowns`
## Commands Description mcchatspy
`Toggle mcMMO party chat spying on or off`
## Commands Description mcgod
`Toggle mcMMO god-mode on/off`
## Commands Description mchud
`Change your mcMMO HUD style`
## Commands Description mcmmo
`Show a brief description of mcMMO`
## Commands Description mcnotify
`Toggle mcMMO abilities chat display notifications on/off`
## Commands Description mcpurge
`Purge users with no mcMMO levels and users who have not connected in over {0} months from the mcMMO database.`
## Commands Description mcrank
`Show mcMMO ranking for a player`
## Commands Description mcrefresh
`Refresh all cooldowns for mcMMO`
## Commands Description mcremove
`Remove a user from the mcMMO database`
## Commands Description mcscoreboard
`Manage your mcMMO Scoreboard`
## Commands Description mcstats
`Show your mcMMO levels and XP`
## Commands Description mctop
`Show mcMMO leader boards`
## Commands Description mmoedit
`Edit mcMMO levels for a user`
## Commands Description mmodebug
`Toggle a debug mode which prints useful information when you hit blocks`
## Commands Description mmoupdate
`Migrate mcMMO database from an old database into the current one`
## Commands Description mcconvert
`Converts database types or experience formula types`
## Commands Description mmoshowdb
`Show the name of the current database type (for later use with /mmoupdate)`
## Commands Description party
`Control various mcMMO party settings`
## Commands Description partychat
`Toggle mcMMO party chat on/off or send party chat messages`
## Commands Description ptp
`Teleport to an mcMMO party member`
## Commands Description Skill
`Display detailed mcMMO skill info for {0}`
## Commands Description skillreset
`Reset mcMMO levels for a user`
## Commands Description vampirism
`Modify the mcMMO vampirism percentage or toggle vampirism mode on/off`
## Commands Description xplock
`Lock your mcMMO XP bar to a specific mcMMO skill`
## Commands Description xprate
`Modify the mcMMO XP rate or start an mcMMO XP event`
#UPDATE CHECKER
## UpdateChecker Outdated
`You are using an outdated version of mcMMO!`
## UpdateChecker NewAvailable
`There is a new version available on Spigot.`
#SCOREBOARD HEADERS
## Scoreboard Header PlayerStats
`&emcMMO Stats`
## Scoreboard Header PlayerCooldowns
`&emcMMO Cooldowns`
## Scoreboard Header PlayerRank
`&emcMMO Rankings`
## Scoreboard Header PlayerInspect
`&emcMMO Stats: {0}`
## Scoreboard Header PowerLevel
`&cPower Level`
## Scoreboard Misc PowerLevel
`&6Power Level`
## Scoreboard Misc Level
`&3Level`
## Scoreboard Misc CurrentXP
`&aCurrent XP`
## Scoreboard Misc RemainingXP
`&eRemaining XP`
## Scoreboard Misc Cooldown
`&dCooldown`
## Scoreboard Misc Overall
`&6Overall`
## Scoreboard Misc Ability
`Ability`
#DATABASE RECOVERY
## Profile PendingLoad
`&cYour mcMMO player data has not yet been loaded.`
## Profile Loading Success
`&aYour mcMMO profile has been loaded.`
## Profile Loading FailurePlayer
`&cmcMMO is having trouble loading your data, we have attempted to load it &a{0}&c times.&c You may want to contact the server admins about this issue. mcMMO will attempt to load your data until you disconnect, you will not gain XP or be able to use skills while the data is not loaded.`
## Profile Loading FailureNotice
`&4[A]&c mcMMO was unable to load the player data for &e{0}&c. &dPlease inspect your database setup. Attempts made so far {1}.`
#Holiday
## Holiday AprilFools Levelup
`&6{0} is now level &a{1}&6!`
## Holiday Anniversary
`&9Happy {0} Year Anniversary!\n&9In honor of all of nossr50's work and all the devs, here's a firework show!`
#Reminder Messages
## Reminder Squelched
`&7Reminder: You are currently not receiving notifications from mcMMO, to enable notifications please run the /mcnotify command again. This is an automated hourly reminder.`
#Locale
## Locale Reloaded
`&aLocale reloaded!`
#Player Leveling Stuff
## LevelCap PowerLevel
`&6(&amcMMO&6) &eYou have reached the power level cap of &c{0}&e. You will cease to level in skills from this point on.`
## LevelCap Skill
`&6(&amcMMO&6) &eYou have reached the level cap of &c{0}&e for &6{1}&e. You will cease to level in this skill from this point on.`
## Commands XPBar Usage
`Proper usage is /mmoxpbar <skillname | reset> <show | hide>`
## Commands Description mmoxpbar
`Player settings for mcMMO XP bars`
## Commands Description mmocompat
`Information about mcMMO and whether or not its in compatibility mode or fully functional.`
## Compatibility Layer Unsupported
`&6Compatibility for &a{0}&6 is not supported by this version of Minecraft.`
## Compatibility Layer PartialSupport
`&6Compatibility for &a{0}&6 is not fully supported by this version of Minecraft, but mcMMO is running a secondary system to emulate some of the missing features.`
## Commands XPBar DisableAll
`&6 All mcMMO XP bars are now disabled, use /mmoxpbar reset to restore default settings.`
#Modern Chat Settings
## Chat Style Admin
`&b(A) &r{0} &b\u2192 &r{1}`
## Chat Style Party
`&a(P) &r{0} &a\u2192 &r{1}`
## Chat Style Party Leader
`&a(P) &r{0} &6\u2192 &r{1}`
## Chat Identity Console
`&6* Console *`
## Chat Channel On
`&6(&amcMMO-Chat&6) &eYour chat messages will now be automatically delivered to the &a{0}&e chat channel.`
## Chat Channel Off
`&6(&amcMMO-Chat&6) &7Your chat messages will no longer be automatically delivered to specific chat channels.`
## Chat Spy Party
`&6[&eSPY&6-&a{2}&6] &r{0} &b\u2192 &r{1}`
## Broadcasts LevelUpMilestone
`&6(&amcMMO&6) {0}&7 has reached level &a{1}&7 in &3{2}&7!`
## Broadcasts PowerLevelUpMilestone
`&6(&amcMMO&6) {0}&7 has reached a Power level of &a{1}&7!`
## Scoreboard Recovery
`Attempting to recover mcMMO scoreboard...`