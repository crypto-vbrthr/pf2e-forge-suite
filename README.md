# PF2e Forge Suite


# About the PF2E Forge Suite

The **PF2E Forge Suite** is a growing collection of free Foundry VTT modules designed to make life behind the GM screen easier.

Its purpose is to support Game Masters throughout the entire game: from **preparing adventures and creating content**, to **organizing campaigns and managing information**, to **automating repetitive tasks during play**. The individual Forge modules provide focused tools that reduce bookkeeping, improve clarity, and help the GM spend less time fighting interfaces and more time running the game.

At the same time, the Forge Suite is not only about efficiency. Many of its tools are designed to add atmosphere, variety, unexpected moments, and useful narrative support, helping to make sessions more entertaining and enjoyable for **both the Game Master and the players**.

The modules are designed to work independently, so you can use only the tools that fit your game. Where useful, Forge modules can also integrate with one another, allowing them to share information and form a broader toolkit for campaign preparation and play.

The **PF2E Forge Suite is completely free and will remain free**. There are no paid tiers, subscriptions, or premium features.

Below you can find the currently available Forge modules and their add-ons, each with a short description and a link to its project page.



## Campaign Forge

**Campaign Forge** is a comprehensive campaign management module for Foundry VTT. It helps Game Masters organize quests, knowledge, events, key NPCs, reputation values, and long-running story threads while tracking their progress across many sessions. Sessions can be logged, entries linked together, and status changes connected to follow-up actions or rewards. A dedicated player view presents approved information clearly and safely. Through integrations with other Forge modules such as *City Forge*, *NPC Forge*, *Creature Forge*, *Loot Forge*, *Item Forge*, and *Weather Forge*, Campaign Forge can also serve as a central hub for a connected campaign.

The **Campaign Forge** can be found here: https://github.com/crypto-vbrthr/campaign-forge.


## City Forge

**PF2e City Forge** is a settlement management and generation module for Foundry VTT and Pathfinder 2e. It lets GMs create, organize, and maintain structured settlements with population, economy, districts, locations, government, laws, security, factions, special features, and dynamic settlement states such as unrest, shortages, prosperity, or crises. Settlements can be created manually or generated from reusable templates, while remaining fully editable afterwards. City Forge also provides stable integration APIs for other Forge Suite modules, including *Market Forge* for local markets and availability, *Weather Forge* for regional climate context, *Atmosphere Forge* for settlement-aware atmosphere generation, and *Campaign Forge* for campaign-driven settlement changes and state updates.

The **City Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-city-forge


## Critical Forge & Effect Forge

**Critical Forge** is a flexible critical hit and fumble framework for Pathfinder 2e in Foundry VTT. It provides context-aware critical effects for attacks, spells, saving throws, and other situations, allowing dramatic, tactical, serious, or humorous consequences to be integrated directly into the game workflow.

At its core, **Critical Forge** includes the **Effect Forge**, an integrated editor for creating and managing custom critical effects, backed by the **Effect Engine**, which can apply conditions, modifiers, resistances, weaknesses, persistent damage, movement effects, temporary Hit Points, regeneration, and many other PF2e mechanics with configurable durations and triggers.

**Critical Forge** is designed as an extensible platform rather than a closed collection of tables. Additional modules can register their own themed card packs, rules, and effects through its public extension API, allowing the system to grow with specialized expansions such as *martial consequences*, *arcane backlash*, weapon-specific criticals, heroic moments, or darker campaign themes.

The **Critical Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-critical-forge


### Against All Odds

**Against All Odds** is an expansion for the **Critical Forge** that rewards heroes when the battle turns desperate. Its 480 contextual critical-success cards react to situations such as fighting while badly wounded, being surrounded, facing vastly stronger enemies, or escaping imminent disaster.

Effects cover attacks, spell attacks, and all three saving throws, combining automated PF2e effects with tactical and narrative opportunities. Instead of making desperate situations merely more dangerous, *Against All Odds* gives heroes a chance to turn them into memorable moments of defiance, survival, and triumph.

**Requires:** Critical Forge

**Critical Forge: Against All Odds** can be found here: https://github.com/crypto-vbrthr/pf2e-critical-forge-against-all-odds


### Arcane Backlash

**Arcane Backlash** expands the **PF2E Critical Forge** with 120 cards dedicated to the unpredictable extremes of magic. Its four card packs cover critical spell attack successes and failures, as well as critical successes and failures on saving throws against spells.

From unstable magical feedback and defiant reversals to surging spell resonance and overwhelming magical aftereffects, the module adds tactical, narrative, and directly applicable effects for all magical traditions. Many cards integrate with the Critical Forge Effect Engine, while others introduce clear manual consequences that can reshape positioning, reactions, defenses, and the flow of combat.

All four card packs can be enabled or disabled individually.

**Requires:** Critical Forge

**Critical Forge: Arcane Backlash** can be found here: https://github.com/crypto-vbrthr/pf2e-critical-forge-arcane-backlash


### Arsenal

**Arsenal** expands the **PF2E Critical Forge** with 180 cards focused on the brutal consequences of weapon combat. Its six card packs cover critical hits and critical fumbles for **slashing, piercing, and bludgeoning damage**.

From deep cuts, shattered defenses, and crushing impacts to lost footing, weapon mishaps, and painful openings, Arsenal turns exceptional attack rolls into memorable tactical moments. Many cards use the Critical Forge Effect Engine to apply conditions, penalties, persistent damage, movement effects, and other mechanical consequences directly in Foundry VTT.

All six card packs can be enabled or disabled individually.

**Requires:** Critical Forge

**Critical Forge: Arsenal** can be found here: https://github.com/crypto-vbrthr/pf2e-critical-forge-arsenal


### Grim Consequences

**Grim Consequences** is an expansion for **Critical Forge** designed for darker, more serious Pathfinder 2e campaigns. It adds **120 new critical consequences** focused on painful setbacks, loss of control, shattered defenses, physical collapse, and mental strain, without slapstick or deliberately comedic results.

The module contains four separate decks for **Attack**, **Fortitude**, **Reflex**, and **Will**, each with 30 carefully balanced consequences ranging from moderate complications to rare, severe outcomes. Every deck can be enabled or disabled individually through the module settings.

Grim Consequences integrates directly with Critical Forge and its Effect Engine, automating suitable effects where possible while keeping more situational consequences clear and easy to adjudicate at the table.

Ideal for campaigns where critical failures and devastating hits should leave a mark, at least for a little while.

**Requires:** Critical Forge

**Critical Forge: Grim Consequences** can be found here: https://github.com/crypto-vbrthr/pf2e-critical-forge-grim-consequences


### Martial Consequences

**Martial Consequences** expands the **PF2E Critical Forge** with 120 cards dedicated to the shifting momentum of physical combat. Its four card packs cover **Martial Attack Fumbles, Ranged Mishaps, Martial Openings, and Combat Momentum**.

The module adds tactical consequences for weapons, unarmed strikes, and natural attacks, ranging from awkward mistakes and dangerous ranged mishaps to openings created by powerful hits and bursts of battlefield momentum. Effects can alter positioning, defenses, reactions, movement, and opportunities for allies, with many cards integrating directly with the Critical Forge Effect Engine.

All four card packs can be enabled or disabled individually.

**Requires:** Critical Forge

**Critical Forge: Martial Consequences** can be found here: https://github.com/crypto-vbrthr/pf2e-critical-forge-martial-consequences


## PF2E Market Forge

**Market Forge** turns buying and selling equipment in Pathfinder 2e into a fast, convenient, and rules-aware workflow directly inside Foundry VTT.

Players can browse available equipment, inspect item descriptions, add multiple purchases or sales to a cart, and complete the entire transaction in one step. Market Forge automatically handles PF2e prices, quantities, currency changes, inventory transfers, and standard selling values, including special treasure rules.

Game Masters can create multiple **market profiles** with their own item and spell compendium sources, rarity restrictions, price modifiers, and maximum available item levels. Availability can use a fixed level or scale dynamically with the party, making it easy to represent everything from a small village shop to a well-stocked magical metropolis.

Market Forge also supports the automatic creation and purchase of **scrolls and standard wands**, including spell selection, heightened ranks, appropriate item levels, prices, and spell rarity.

Transactions work with both **character inventories and the shared Party inventory** and are validated authoritatively by the GM, including protection against conflicting multiplayer transactions.

### Highlights

* Buy and sell PF2e equipment directly from an intuitive marketplace
* Shopping and selling carts with quantity controls and live totals
* Automatic currency deduction, proceeds, inventory transfer, and stacking
* Support for character and Party inventories
* Configurable market profiles with independent compendium sources and pricing rules
* Dynamic or fixed maximum item levels
* Rarity and availability controls
* Search, filters, expandable descriptions, and direct access to item sheets
* Automatic generation of scrolls and standard wands from available spells
* GM-authoritative and multiplayer-safe transactions

Market Forge removes the bookkeeping from shopping without taking control away from the Game Master, leaving more time for the part everyone actually came for: adventuring.

**Market Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-market-forge


## NPC Forge

**NPC Forge** is a comprehensive NPC generator for Pathfinder 2e, designed to create believable, game-ready characters in just a few clicks.

Rather than producing simple stat blocks, NPC Forge builds complete personalities with ancestry, profession, class profile, role, appearance, personality, background, social standing, relationships, equipment, abilities, attacks, and spellcasting. Generated NPCs use level-appropriate PF2e statistics and equipment, including fundamental runes for higher-level characters.

The Forge is equally suited for creating an important recurring character or quickly filling the world with guards, merchants, scholars, criminals, priests, nobles, artisans, and many other professions.

### Features

- Extensive ancestry, profession, class, specialization, and role system
- Level-appropriate PF2e statistics, skills, attacks, abilities, and equipment
- Prepared and spontaneous spellcasting with real PF2e spells
- Ancestry-aware and localized name generation
- Appearance, personality, motivations, flaws, quirks, and secrets
- Backgrounds, social context, reputation, and structured relationships
- Profession-specific equipment and personal possessions
- Level-scaled fundamental weapon, armor, and shield runes
- Real PF2e compendium items wherever possible
- Deterministic generation and selective section rerolls
- Full German and English localization
- Reusable embedded editor and public API for other modules

NPC Forge can also cooperate with other members of the **Forge Suite**. **Affliction Forge** can provide poisons for suitable NPC weapons, while **Item Forge** can generate personal valuables and art objects. Its public generation and editor APIs are designed so modules such as **Encounter Forge** and **Crowd Forge** can use NPC Forge as a shared NPC-generation engine.

Like the rest of the Forge Suite, NPC Forge is designed to reduce preparation work while giving the GM more useful material to bring the game world to life.

**NPC Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-npc-forge


## Weather Forge

**Weather Forge** provides persistent, evolving weather for Pathfinder 2E campaigns in Foundry VTT. Instead of generating isolated random conditions, it simulates weather that develops naturally over time, taking **climate, season, time of day, temperature trends, humidity, clouds, wind, precipitation, and extreme weather** into account.

Game Masters can generate and preview current conditions, create **1–7 day forecasts**, review a persistent **weather history**, and publish detailed GM reports or immersive player-facing weather descriptions directly to chat. Extreme events such as storms, heatwaves, and cold waves can develop over several stages rather than appearing and disappearing without warning.

Weather Forge includes multiple climate zones and an internal Golarion calendar, but can also integrate with other Forge modules. **Calendar Forge** can provide the current date, season, moon phase, and daypart while Foundry world time remains authoritative. **City Forge** can provide the climate of the current or a specifically selected settlement, allowing weather generation to reflect where the party actually is.

All integrations are optional, and Weather Forge remains fully usable as a standalone module.

**Weather Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-weather-forge
