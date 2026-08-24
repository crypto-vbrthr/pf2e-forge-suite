# PF2e Forge Suite


# About the PF2E Forge Suite

The **PF2E Forge Suite** is a growing collection of free Foundry VTT modules designed to make life behind the GM screen easier.

Its purpose is to support Game Masters throughout the entire game: from **preparing adventures and creating content**, to **organizing campaigns and managing information**, to **automating repetitive tasks during play**. The individual Forge modules provide focused tools that reduce bookkeeping, improve clarity, and help the GM spend less time fighting interfaces and more time running the game.

At the same time, the Forge Suite is not only about efficiency. Many of its tools are designed to add atmosphere, variety, unexpected moments, and useful narrative support, helping to make sessions more entertaining and enjoyable for **both the Game Master and the players**.

The modules are designed to work independently, so you can use only the tools that fit your game. Where useful, Forge modules can also integrate with one another, allowing them to share information and form a broader toolkit for campaign preparation and play.

The **PF2E Forge Suite is completely free and will remain free**. There are no paid tiers, subscriptions, or premium features.

Below you can find the currently available Forge modules and their add-ons, each with a short description and a link to its project page.


## Affliction Forge

**Affliction Forge** provides a complete framework for creating, managing, and running **poisons, diseases, curses, and other staged afflictions** in Pathfinder 2E for Foundry VTT.

Afflictions can include **initial exposure checks, onset periods, multiple stages, stage durations, recurring saving throws, recovery rules, persistent effects, periodic effects, restrictions, and lethal outcomes**. Their progression is tracked automatically using Foundry's world time, allowing long-running diseases and poisons to develop naturally without requiring the Game Master to manually remember every interval and saving throw.

The integrated **Affliction Editor** allows Game Masters to create their own reusable afflictions, while searchable libraries can provide additional content from world items, compendia, and external add-ons. Afflictions support different identification states, so their true nature can remain hidden or merely suspected until the characters discover what they are dealing with.

Affliction templates can also be linked directly to **weapons, attacks, abilities, feats, and spells**. Depending on their configuration, they can be applied manually, after confirmation, or automatically when appropriate PF2e events occur, such as a successful hit, applied damage, a failed saving throw, or use of an ability. Injury poisons can even be applied as limited-charge weapon coatings.

Stage mechanics are powered by the **Critical Forge Effect Engine**, allowing Affliction Forge to use the same flexible effect system for conditions, damage, modifiers, restrictions, healing interactions, death effects, and other mechanical consequences.

A public API, semantic tagging system, and provider libraries allow other Forge modules and content add-ons to create, reference, search, and apply afflictions without duplicating their progression logic.

**Affliction Forge requires Critical Forge.**

The **Affliction Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-affliction-forge


### Affliction Forge: Alchemist's Cabinet

**Alchemist's Cabinet** is a content add-on for **Affliction Forge** containing **32 original alchemical afflictions from levels 0 through 20**. Its collection focuses on manufactured toxins, experimental compounds, laboratory accidents, and other hazards born from alchemical ingenuity rather than natural disease alone.

The cabinet contains **weapon coatings, contact poisons, aerosols, ingestible toxins, injections, mutagenic failures, and laboratory diseases**. Twelve entries are true **injury poisons** and integrate directly with Affliction Forge's weapon-coating and charge system.

Its afflictions make extensive use of the Affliction Forge engine, including **persistent damage, virulent progression, concentration restrictions, blocked speech, condition locks, healing restrictions, elemental and unusual damage types, and even a high-level death effect**. This allows the collection to range from relatively simple low-level compounds to dangerous experimental creations capable of becoming major threats in their own right.

Every entry is available in **English and German** and includes standardized semantic tags for creature type, habitat, theme, origin, and delivery method. This allows integrations such as **Creature Forge** to discover suitable afflictions for poison-using humanoids, constructs, alchemical creatures, laboratory creations, aberrations, oozes, fungi, elementals, and other appropriate creatures.

The add-on integrates with the public **Affliction Forge Library API** and provides its content through a managed, read-only library while retaining the shared progression and automation systems of Affliction Forge.

All afflictions contained in **Alchemist's Cabinet** are original homebrew content created specifically for the Forge Suite.

**Requires Affliction Forge 0.1.63 or later.**

**Affliction Forge: The Alchemist's Cabinet** can be found here: https://github.com/crypto-vbrthr/pf2e-affliction-forge-alchemists-cabinet


### Affliction Forge: The Black Archive

**The Black Archive** is a prestige content add-on for **Affliction Forge**, containing **24 original rare and unusual afflictions from levels 1 through 20**. Rather than simply expanding the library with more conventional diseases and poisons, the Black Archive explores some of the deeper possibilities of the Affliction Forge engine.

Its collection includes **diseases, poisons, and curses** with mechanics such as **periodic stage effects, event-driven reactions, timed effects that can persist beyond their original stage, alternative stage outcomes, numeric modifiers, concentration gates, blocked speech, healing restrictions, condition locks, Virulent and stubborn progression**.

Some afflictions can react dynamically to events during play, including **damage taken, increasing conditions, initiative, or the beginning of a creature's turn**. The archive also contains a true **injury poison** using Affliction Forge's weapon-coating and charge system, as well as a unique high-level affliction whose final stage can become a genuine **death effect**.

Every entry is available in **English and German** and uses standardized semantic tags, allowing integrations such as **Creature Forge** to discover appropriate afflictions by creature, habitat, theme, origin, and delivery method.

The Black Archive deliberately uses the existing capabilities of Affliction Forge rather than introducing special rules that only work inside the add-on, making its contents fully compatible with the shared affliction runtime and progression system.

All afflictions contained in **The Black Archive** are original homebrew content created specifically for the Forge Suite.

**Requires Affliction Forge 0.1.63 or later.**

**Affliction Forge: The Black Archive** can be found here: https://github.com/crypto-vbrthr/pf2e-affliction-forge-black-archive


### Affliction Forge: Curses & Damnations

**Affliction Forge: Curses & Damnations** is a content add-on for **Affliction Forge** that expands its libraries with **32 original staged curses and supernatural damnations** covering levels 0 through 20.

The collection ranges from fast, combat-adjacent curses to lingering afflictions that unfold over **hours or days**. Individual curses can feature different saving throws and progression rules as well as mechanics such as **onset periods, locked conditions, healing restrictions, suppressed speech, restrictions on concentrate actions, virulent progression, and even lethal final stages**.

More persistent curses can use a **stubborn progression**, where an ordinary success merely prevents the curse from worsening while a critical success is required to reduce its stage.

Every entry is available in **English and German** and uses standardized semantic tags, allowing modules such as **Creature Forge** to find suitable curses according to creature type, habitat, origin, delivery method, and theme.

The add-on integrates directly with the **Affliction Forge Library API** and provides its content as a managed, read-only library while still allowing Game Masters to create editable copies for their own campaigns.

All curses contained in **Curses & Damnations** are original homebrew content created specifically for the Forge Suite.

**Requires Affliction Forge.**

**Affliction Forge: Curses & Damnations** can be found here: https://github.com/crypto-vbrthr/pf2e-affliction-forge-curses-damnations


### Affliction Forge: Remastered Rules Library

**Remastered Rules Library** is the official-rules content add-on for **Affliction Forge**, bringing a growing collection of **Pathfinder 2E Remastered diseases, poisons, curses, and creature afflictions** into the Forge Suite's automated affliction framework.

The library currently contains **124 reviewed affliction definitions** drawn from sources including **GM Core, Player Core 2, Treasure Vault Remastered, and Howl of the Wild**. Entries preserve their original mechanical behavior wherever Affliction Forge can represent it reliably, including **staged progression, saving throws, onset and maximum durations, virulent afflictions, injury-poison delivery, persistent conditions, periodic effects, formula-based timing, event reactions, and other supported mechanics**.

Where an official rule depends on highly specialized behavior that would require a one-off subsystem, the library deliberately avoids approximating it incorrectly. Instead, the supported mechanics remain automated while the remaining rule is presented clearly to the Game Master as a localized **GM Note**.

All content is available in **English and German** and is provided through a managed, read-only Affliction Forge library with stable source information and deterministic entries.

The library follows a **mechanics-only content policy** under the **ORC License**, providing the rules needed for automation while avoiding unnecessary reproduction of source material.

**Requires Affliction Forge 0.1.61 or later.**

**Affliction Forge: Remastered Rules Library** can be found here: https://github.com/crypto-vbrthr/affliction-forge-remastered-rules


## Aura Forge

**Aura Forge** is the Forge Suite's framework for creating, assigning, and automating **PF2E auras** in Foundry VTT. It allows Game Masters to build reusable auras whose effects respond dynamically to creatures entering, remaining within, or leaving their area of influence.

Auras can contain persistent **Presence Effects** that are automatically applied while a valid target remains inside the aura and removed again when it leaves. In addition, configurable event triggers can react to **entering, leaving, the start of a turn, or the end of a turn**, allowing auras to cause conditions, damage, other mechanical effects, or even immediate death where appropriate.

Triggers can use native PF2E **saving throws with degree-of-success outcomes**, including automatic rolls, GM-controlled resolution, or requests sent directly to the player controlling the affected character. Aura Forge also supports **temporary immunity periods**, preventing repeated effects from triggering again until the configured immunity expires.

Auras can be stored in a central **Aura Library**, assigned to Actors through drag and drop, enabled or disabled individually, and given Actor-specific radius overrides. Generated creatures can instead carry their own **Actor-local aura definitions**, allowing modules such as **Creature Forge** to create self-contained creature abilities without filling the world's shared Aura Library.

Assigned auras integrate with PF2E's native canvas aura display, while Aura Forge handles the actual targeting, presence tracking, event detection, saving throws, immunity, and effect automation behind the scenes.

Aura effects are created using the integrated **Critical Forge Effect Editor and Effect Engine**, giving them access to the same flexible system for conditions, modifiers, persistent effects, damage, restrictions, and other mechanical consequences.

Aura Forge also provides an embedded editor and public API, allowing other Forge modules to create and manage auras while sharing the same runtime and automation system.

**Requires Critical Forge.**

**Aura Forge: Remastered Rules Library** can be found here: https://github.com/crypto-vbrthr/pf2e-aura-forge


## Campaign Forge

**Campaign Forge** is a campaign-management and campaign-memory module for Foundry VTT, designed to give Game Masters a central place to organize the many moving parts of a long-running campaign.

It can track **quests, campaign chapters, knowledge, discoveries, events, long-term plot threads, sessions, reputation and other numeric campaign values, important NPCs, Journal references, rewards, and campaign progress**. Entries can be organized hierarchically, searched and filtered, linked to Foundry documents, and selectively published to players.

A dedicated **Player View** provides a clean, read-only campaign overview containing only information explicitly released by the Game Master. Hidden notes, unpublished entries, GM-only data, transition rules, and other private information remain concealed, allowing Campaign Forge to serve both as a GM workspace and as a persistent campaign reference for the group.

Campaign Forge can also automate campaign development through **conditional transition rules and rewards**. Completing quests, changing campaign values, or reaching other defined states can trigger further changes, allowing campaign consequences and progression to be represented directly in the campaign structure.

Rewards can include ordinary PF2E rewards as well as optional integrations with **Loot Forge** and **Item Forge**, while other Forge modules can contribute additional campaign context. **City Forge, NPC Forge, Creature Forge, Loot Forge, Item Forge, and Weather Forge** remain independent modules, but Campaign Forge can reference or orchestrate their public functionality when they are installed. Weather conditions can even be captured as historical snapshots for sessions and events, preserving the circumstances in which they occurred.

Campaign Forge also includes **Journal integration, data-integrity checks, backup and restore tools, protected GM storage, privacy-safe player projections, and a stable public API** for integration with other modules.

All integrations are optional, and Campaign Forge remains fully usable on its own.

Campaign Forge is available in **English and German**.

The **Campaign Forge** can be found here: https://github.com/crypto-vbrthr/campaign-forge.


## City Forge

## City Forge

**City Forge** is a structured settlement-management and generation module for Pathfinder 2E in Foundry VTT. It gives Game Masters a central framework for creating and maintaining everything from small hamlets and villages to major towns and sprawling metropolises.

Settlements can contain detailed information about their **identity, level, population, ancestries, languages, religions, geography, climate, economy, industries, imports, exports, government, laws, security, factions, threats, districts, locations, NPCs, and special features**. Foundry Actors, Scenes, and Journal Entries can be linked directly to the appropriate parts of a settlement, keeping campaign information connected instead of scattered across unrelated documents.

The integrated **Settlement Generator** provides reusable starting points for common settlement types such as **frontier settlements, agricultural villages, trade towns, ports, fortified towns, religious or arcane centers, mining settlements, and metropolises**. Existing settlements can also be saved as custom templates and reused as foundations for new locations.

City Forge separates the permanent definition of a settlement from its **current dynamic state**. Prosperity, supply, security, order, public mood, and health can change over time, while temporary conditions such as **unrest, sieges, epidemics, festivals, shortages, occupations, disasters, or economic booms** can influence the settlement without rewriting its underlying data. Faction influence, market conditions, access rules, and active threats can change dynamically as the campaign develops.

Its economy system can define **item availability, rarity access, settlement-level limits, special markets, price modifiers, spellcasting services, and feature-based market rules**. When **Market Forge** is installed, settlements can act as live market providers, allowing local economic conditions to influence what characters can actually buy.

City Forge also supports optional integration with other Forge modules. **Weather Forge** can use settlement climate and geography, **Atmosphere Forge** can use districts, locations, politics, threats, and current conditions when creating narrative atmosphere, and **Campaign Forge** can react to campaign events by applying controlled changes to settlement state.

A stable public API and versioned integration contracts allow other Forge modules to use settlement, economy, location, political, and state information without taking ownership of City Forge data.

All integrations are optional, and City Forge remains fully usable as a standalone settlement-management tool.

City Forge is available in **English and German**.

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


## Loot Forge

**Loot Forge** is a treasure and inventory generator for Pathfinder 2E in Foundry VTT, designed to help Game Masters create **believable, level-appropriate, and thematically fitting loot** without manually assembling every coin, valuable, and equipment item.

Loot generation can be configured by **level, party size, budget, treasure profile, item-level range, rarity, theme, environment, and loot style**. Different themes such as **Dragon Hoard, Dwarven Ruin, Pirate Hideout, Temple, Mage Tower, Alchemist Laboratory, Undead Crypt, Bandit Camp, or Goblin Den** influence what kinds of treasures are generated, while environments can further affect their composition and condition.

Loot Forge combines ordinary PF2E equipment with procedurally generated valuables and story objects, including **artworks, jewelry, collectibles, curiosities, documents, textiles, instruments, beverages, craftsmanship items, statues, and coins**. Generated treasure receives descriptive details and value information so that a hoard can feel like part of the world rather than merely a collection of price tags.

A preview allows the Game Master to **edit coins and treasure values, remove entries, re-roll individual generated treasures, and review the total value against the intended budget** before anything is added to the game. The completed result can then be placed directly into an existing Actor or used to create a dedicated Loot Actor.

Loot Forge also provides an **embedded editor and public API**, allowing other Forge modules to reuse its generation system while retaining control over how the resulting loot is applied. If **Item Forge** is installed, Loot Forge can optionally delegate individual item and treasure construction to it while continuing to control the overall budget, composition, theme, environment, and final inventory.

All integrations are optional, and Loot Forge remains fully functional as a standalone module.

Loot Forge is available in **English and German**.

**Loot Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-loot-forge


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
