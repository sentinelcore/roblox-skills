# roblox-skills

Skills for AI coding agents to help with Roblox game development.

## Install

```bash
# Install all skills
npx skills add sentinelcore/roblox-skills

# Install a specific skill
npx skills add https://github.com/sentinelcore/roblox-skills/tree/main/roblox-monetization
```

## Skills

### `roblox-monetization`
End-to-end guide for earning Robux — Game Passes, Developer Products, UGC items, Premium Payouts, and DevEx cash-out. Covers Creator Hub dashboard setup and server-side Lua scripting.

### `roblox-datastores`
Saving and loading player data with `DataStoreService`. Covers `GetAsync`/`SetAsync`/`UpdateAsync`, retry logic, auto-save on `PlayerRemoving` + `BindToClose`, ordered datastores for leaderboards, and data versioning/migration.

### `roblox-remote-events`
Client-server communication with `RemoteEvent`, `RemoteFunction`, and `UnreliableRemoteEvent`. Covers firing patterns, where to store remotes, and critical server-side security validation.

### `roblox-gui`
Building and animating Roblox GUIs. Covers `ScreenGui`, `SurfaceGui`, `BillboardGui`, `UDim2` sizing, `TweenService` animations, responsive scaling, and `LocalScript` placement.

### `roblox-security`
Anti-exploit patterns and server-side validation. Covers secure vs insecure code patterns, distance/cooldown/bounds checks, rate limiting, argument validation, and anti-cheat detection.

### `roblox-animations`
Roblox animation system. Covers `LoadAnimation`, `AnimationTrack` playback and events, priority/blending, Humanoid vs `AnimationController`, replacing default character animations, and common mistakes.

### `roblox-performance`
Performance optimization. Covers `StreamingEnabled`, hot-path loop optimization, `task` library, object pooling, LOD, draw call reduction, and profiling with MicroProfiler.

## Contributing

PRs welcome. Follow the [skills authoring guide](https://skills.sh) when adding new skills.
