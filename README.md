# RaindanceMC/farmworld

- **`farmworld-module`** — Rain's Flexible Modules — Farm Worlds: Somewhere to strip-mine that is thrown away and made again, so the main world is left alone. This module owns what a farm world actually is — three linked worlds with their own nether and end, the portal linking between them, the schedule and the one rule that decides what may be deleted — built on RainsCore's generic world regeneration and chunk-holding primitives rather than a farm-world concept living in Core itself. What is here besides that: how somebody gets in, scattered rather than dropped on one spot, warned before the ground under them is thrown away, and waited between trips.
- **`farmworld-standalone`** — Rain's Farm Worlds: Rain's Farm Worlds, as a plugin of its own. Nothing here but a build file and a descriptor: the farm worlds module and the standard wrapper are shaded together, and that is the whole plugin.

Part of [RaindanceMC](https://github.com/RaindanceMC); built on [RainsCore](https://github.com/RaindanceMC/RainsCore) and the shared parent in [framework](https://github.com/RaindanceMC/framework). Split out of `rains-flexible-modules` on 16.10.2026, history kept.

## Build

```
mvn install
```

Needs Java 25 and read access to `packages.tstieh.de` (server ids `packages-releases` / `packages-snapshots` in `~/.m2/settings.xml`).

## Plugins

- `farmworld-standalone/target/RainsFarmWorlds-1.6.0.jar` — also published as `de.raindancer.modules:farmworld-standalone:1.6.0`

## Versions

A module's version is a property in this repository's root `pom.xml`, a plugin's is `plugin.version` in its own pom. CI publishes every version that is not in the registry yet on the next push to master.
