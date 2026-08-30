# Aura Forge

**Aura Forge** is the Forge Suite's framework for creating, assigning, and automating **PF2E auras** in Foundry VTT. It allows Game Masters to build reusable auras whose effects respond dynamically to creatures entering, remaining within, or leaving their area of influence.

Auras can contain persistent **Presence Effects** that are automatically applied while a valid target remains inside the aura and removed again when it leaves. In addition, configurable event triggers can react to **entering, leaving, the start of a turn, or the end of a turn**, allowing auras to cause conditions, damage, other mechanical effects, or even immediate death where appropriate.

Triggers can use native PF2E **saving throws with degree-of-success outcomes**, including automatic rolls, GM-controlled resolution, or requests sent directly to the player controlling the affected character. Aura Forge also supports **temporary immunity periods**, preventing repeated effects from triggering again until the configured immunity expires.

Auras can be stored in a central **Aura Library**, assigned to Actors through drag and drop, enabled or disabled individually, and given Actor-specific radius overrides. Generated creatures can instead carry their own **Actor-local aura definitions**, allowing modules such as **Creature Forge** to create self-contained creature abilities without filling the world's shared Aura Library.

Assigned auras integrate with PF2E's native canvas aura display, while Aura Forge handles the actual targeting, presence tracking, event detection, saving throws, immunity, and effect automation behind the scenes.

Aura effects are created using the integrated **Critical Forge Effect Editor and Effect Engine**, giving them access to the same flexible system for conditions, modifiers, persistent effects, damage, restrictions, and other mechanical consequences.

Aura Forge also provides an embedded editor and public API, allowing other Forge modules to create and manage auras while sharing the same runtime and automation system.

**Requires Critical Forge.**

**Aura Forge** can be found here: https://github.com/crypto-vbrthr/pf2e-aura-forge

**Aura Forge is available on Foundry VTT's module repository.**
