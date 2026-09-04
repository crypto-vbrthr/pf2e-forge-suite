## Calendar Forge

**Calendar Forge** is the Forge Suite's calendar and temporal-context framework for Foundry VTT, designed to turn Foundry's world time into a complete, setting-aware representation of **dates, seasons, moon phases, astronomical events, holidays, regional context, and campaign chronology**.

Foundry's own `game.time.worldTime` remains the single authoritative clock. Calendar Forge does not introduce a second independent time system. Instead, it interprets that existing world time through the currently selected calendar, ensuring that other modules and the Game Master always refer to the same moment in the campaign world.

The main calendar provides detailed **month and year views**, date navigation, direct jumps to specific dates, and visual markers for **seasons, moon events, astronomy, holidays, historical entries, and externally supplied campaign events**. Calendars can use their own month and weekday names while optionally displaying alternate names for easier real-world reference.

Calendar Forge can model much more than the date itself. Configurable **season profiles, moon profiles, regional contexts, astronomical events, holidays, and historical chronology** allow a setting's passage of time to become part of the campaign rather than merely a number on the Foundry clock.

The integrated **Chronicle** provides a searchable timeline for historical and campaign events. Entries can retain different levels of historical precision, allowing an event to be known only by year or month without inventing an artificial exact date. Events can also be located directly in the calendar for easier navigation between history and the current campaign timeline.

Calendar Forge is intentionally **system- and setting-agnostic at its core**. Setting-specific calendar data can be supplied through external content providers rather than being permanently built into the module. Providers can contribute complete calendars, seasons, moons, regions, holidays, astronomy, historical events, and recommended world defaults while remaining cleanly separated from the core engine.

A dedicated **Content Provider system and public API** allow other modules to contribute temporal data safely or consume Calendar Forge's current temporal context. Provider content is validated, versioned, and tracked by source, while Game Masters remain in control of whether suggested defaults are applied to an existing world.

Within the Forge Suite, Calendar Forge can act as a shared temporal foundation for other modules. **Weather Forge**, for example, can use Calendar Forge to determine the current date, season, moon state, and daypart while continuing to own weather generation itself. Other Forge modules can use the same temporal context for events, histories, durations, and future integrations without creating competing clocks.

Calendar Forge is available in **English and German**.

The **Calendar Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-calendar-forge

**Calendar Forge is available on Foundry VTT's module repository.**
