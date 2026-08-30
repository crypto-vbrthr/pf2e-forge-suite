# Critical Forge / Effect Forge

**Critical Forge** combines two closely connected tools for Pathfinder 2E in Foundry VTT: the **Effect Forge**, a reusable system for creating mechanical PF2e effects, and the **Critical Forge**, a card-based framework for adding memorable consequences to exceptional rolls.

### Effect Forge

**Effect Forge** provides a visual editor and shared Effect Engine for building reusable PF2e effects without manually assembling Rule Elements. Effects can combine **conditions, modifiers, damage, persistent damage, immunities, resistances, weaknesses, temporary Hit Points, Fast Healing, regeneration, movement changes, granted movement speeds, and other supported mechanics**.

Effects can use global or component-specific durations and are compiled into native PF2e Effect Items wherever possible. Instant components such as damage or death effects can be executed directly, while persistent components remain attached to the affected Actor for their configured duration.

The Effect Engine is always available while the module is active and exposes a stable **public API and embedded editor**. This makes Effect Forge an important shared foundation for other Forge modules such as **Aura Forge, Affliction Forge, Encounter Forge, Chase Forge, and Creature Forge**, which can create and apply mechanical effects without implementing their own effect systems.

### Critical Forge

**Critical Forge** adds configurable critical-result cards for **weapon and unarmed attacks, spell attacks, saving throws, and skill checks**. Critical successes and failures can draw from specialized card decks containing narrative consequences, mechanical effects, or both.

Cards can be filtered using detailed PF2e context such as **damage type, weapon group, attack traits, saving throw, skill, action, item, spell information, source and target traits, battlefield conditions, and other runtime circumstances**. This allows consequences to fit what actually happened rather than being selected from a completely generic table.

Each supported roll category can be configured independently. Critical Forge can remain disabled, **ask the GM before drawing a card**, or automatically select and publish an appropriate result when a matching critical roll occurs. Natural 20 and natural 1 triggers can also be handled separately.

Mechanical consequences are never applied silently. The resulting card is shown first, and the **GM remains in control of whether its Effect Forge effect is actually applied**. Cards can also be redrawn when another result would better fit the situation.

A built-in **Card Pack Editor** allows Game Masters to create their own decks, edit filters and effects, import or export packs, and combine the core system with optional Critical Forge add-ons containing additional themed card collections.

Critical Forge and Effect Forge are available in **English and German**.

The **Critical Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-critical-forge

**Critical Forge is available on Foundry VTT's module repository.**
