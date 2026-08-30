# Weather Forge

**Weather Forge** is a persistent, climate-driven weather simulation for Pathfinder 2E in Foundry VTT, designed to give Game Masters believable weather that develops as part of the campaign world rather than as a series of unrelated random results.

Weather can be generated from configurable **climate zones** and includes interconnected values for **temperature, humidity, cloud cover, wind, and precipitation**. Daily temperature profiles and trends help conditions evolve naturally over time, while **extreme weather** can introduce more dramatic events when appropriate.

The generator uses a **preview and acceptance workflow**, allowing the Game Master to inspect newly generated conditions before they become the world's current weather. Accepted weather is stored persistently, and a **weather history** preserves previous conditions so that the campaign's environmental development can be reviewed later.

Weather Forge can also create **weather forecasts**, providing advance information about upcoming conditions while using the same climate context as normal weather generation. Current weather and forecasts can be shared through **GM-only or public chat output**, making weather useful both as a preparation tool and as an atmospheric element during play.

The module includes its own **internal Golarion calendar fallback**, but can optionally integrate with **Calendar Forge**. When available, Calendar Forge can provide the current date, time, season, moon information, and daypart used by Weather Forge, including automatic or queued weather changes as time progresses.

Weather Forge also integrates optionally with **City Forge**. The module can determine the effective climate from the settlement associated with the active Scene or from a specifically selected City Forge settlement. City Forge can therefore provide the party's current geographic and climate context while Weather Forge remains responsible for actually generating the weather. If no suitable City Forge context is available, Weather Forge automatically falls back to its configured manual climate.

Both integrations can operate together, with **Calendar Forge providing the time and season, City Forge providing the location and climate, and Weather Forge generating the resulting conditions**.

All integrations are optional, and Weather Forge remains fully usable as a standalone module.

Weather Forge is available in **English and German**.

The **Weather Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-weather-forge

**Weather Forge is available on Foundry VTT's module repository.**
