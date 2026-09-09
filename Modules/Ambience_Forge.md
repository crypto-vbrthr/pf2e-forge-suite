# Ambience Forge

**Ambience Forge** is a system-agnostic audio orchestration module for Foundry VTT, designed to help Game Masters build and control rich, layered soundscapes without turning Foundry into an audio editor.

Ambience compositions can combine several independent track types. **Audio Tracks** provide one-shot sounds or seamless loops, **Random Tracks** introduce irregular environmental sounds with configurable pauses and repeat avoidance, **Sequence Tracks** play collections in a defined or randomized order, and **Intensity Tracks** allow a soundscape to shift smoothly between several prepared variants using crossfades.

Each composition has its own **master volume**, while individual tracks retain separate volume controls. During play, the dedicated **Quick Control** interface allows temporary live changes to master volume, track volume, track activation, and intensity without altering the saved composition. Ambience Forge also respects Foundry's normal Environment volume control.

The module supports **Scene Emitters**, allowing complete ambience compositions to be positioned directly on a Scene. Emitters can use a configurable radius, maximum volume, and distance falloff, so the ambience becomes louder as a listener approaches and fades away with distance. Foundry's wall and door geometry can optionally be ignored, attenuate the sound, or block it entirely.

Ambience compositions can be **exported and imported as JSON**, making carefully prepared soundscapes reusable across different Foundry worlds. Exports contain the composition structure, track settings, volumes, intensity variants, timing rules, and audio file references, while the audio files themselves remain external.

Ambience Forge deliberately focuses on **playback orchestration rather than audio processing**. Sound files are prepared externally, while Ambience Forge controls what plays, when it plays, how loudly it plays, how layers interact, and how they transition during the game.

A versioned **public API** allows other modules to start, stop, request, release, and dynamically control ambience compositions. Reference-counted ownership allows several integrations to request the same ambience without accidentally stopping one another. Modules such as **Weather Forge, Atmosphere Forge, Region Forge**, and other Foundry tools can therefore use Ambience Forge as optional shared audio infrastructure while continuing to function normally when it is not installed.

Ambience Forge is available in **English and German**.

**Requires Foundry VTT 14 and Pathfinder 2E 8.4.0 or later.**

The **Ambience Forge** can be found here: https://github.com/crypto-vbrthr/ambience-forge

**Ambience Forge will soon be available on Foundry VTT's module repository.**



## Ambience Forge Integration Convention

Ambience Forge is designed as the shared audio-environment service for modules in the Forge Suite. Other Forge modules may use it optionally to control the acoustic state of a scene without needing to know which audio files, tracks, volumes, random events, or transitions are used internally.

The integration is intentionally semantic:

> External modules describe **what is happening**.  
> Ambience Forge decides **how that situation sounds**.

Ambience Forge remains optional. A Forge module integrating with it must continue to function normally when Ambience Forge is not installed or not active.

---

### Core Concept

An Ambience Forge composition may define several independent **state groups**. Each state group contains mutually exclusive states.

For example:

```text
Composition: Forest

time-of-day
├── dawn
├── day
├── dusk
└── night

weather
├── clear
├── rain
├── heavy-rain
├── storm
├── snow
└── fog

situation
├── calm
├── busy
├── danger
└── combat
```

Different groups may be active simultaneously.

For example:
```
Forest
+ night
+ storm
+ danger
```
Ambience Forge combines the configured changes from all active states and determines the resulting track activation, relative volume, intensity, and transitions.

External modules do not need to know how those changes are implemented.
