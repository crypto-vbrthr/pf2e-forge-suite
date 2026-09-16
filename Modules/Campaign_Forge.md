# Campaign Forge

**Campaign Forge** is a campaign-management and campaign-memory module for Foundry VTT, designed to give Game Masters a central place to organize long-running campaigns, track their development, and automate consequences without scattering important information across dozens of unrelated documents.

Campaigns can be structured into **chapters, groups, quests, knowledge, discoveries, events, plot threads, and other custom entries**. Entries can be searched and filtered, arranged hierarchically, linked to Foundry Journals and Actors, activated or deactivated as the story develops, and assigned different status progressions depending on their purpose.

A flexible **rule system** allows campaign state to react automatically when important developments occur. Entry transitions can trigger further status changes, modify visibility or activity, update campaign values, or call supported integrations. Rules can react either to a specific transition or simply whenever an entry reaches a particular destination status, regardless of the path it took to get there.

Campaign Forge also tracks persistent **campaign values** such as reputation, influence, resources, faction standing, or any other numeric value relevant to the campaign. These values can participate in conditions and automation alongside entry states and chapter progress.

A dedicated **Session system** records the history of the campaign, including session numbers, notes, transactions, rewards, and contextual information. When **Weather Forge** is available, the current weather and temporal context can be captured as a historical snapshot when a session begins or when an important event occurs.

The integrated **Reward system** supports **Experience Points, currency, Items, individual characters, all player characters, and PF2e Team inventories**. Rewards participate in a controlled lifecycle with preview, pending, granted, skipped, failed, reset, and retry states, helping prevent accidental duplicate payouts. Reward rules can also react whenever an entry reaches a configured destination status.

Optional integrations expand the campaign-management workflow without creating hard dependencies. **City Forge** can receive settlement-state changes from campaign consequences, **NPC Forge** can create and register important NPCs, **Creature Forge** can create or link creatures, **Loot Forge** and **Item Forge** can provide generated rewards, **Weather Forge** can supply historical context, and **Chase Forge** can link, launch, resume, and track prepared chases directly from campaign entries.

Campaign Forge includes a dedicated **Player View** that exposes only information explicitly published by the Game Master. Chapters, entries, campaign values, key NPCs, and overview elements can be published independently, while GM notes, hidden clues, transition rules, rewards, provider data, and private campaign state remain protected. Player-facing progress calculations only include information the player is allowed to see.

For larger campaigns, Campaign Forge provides **live search, type and visibility filters, collapsible campaign structures, filtered target selection for automation rules, data-integrity checks, and JSON backup and restore tools**. Canonical GM data is stored in protected Foundry documents, while each player receives a separately filtered projection containing only information they are permitted to access.

A stable **Public API v1** and versioned integration contracts allow other modules to read campaign context or interact with supported systems without taking ownership of Campaign Forge data.

All Forge integrations are optional, and Campaign Forge remains fully usable as a standalone campaign-management tool.

Campaign Forge is available in **English and German**.

**Compatible with Foundry VTT 13 and verified for Foundry VTT 14.**

The **Campaign Forge** can be found here: https://github.com/crypto-vbrthr/campaign-forge.

**Campaign Forge will soon be released on Foundry VTT's module repository.**
