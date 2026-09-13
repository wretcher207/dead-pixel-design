> status: maintained, no work in flight | one-liner: canonical ReaPack index for all DPD REAPER scripts | next: nothing pending, and that is the normal state. This repo changes only when a script ships somewhere else; the index is the source of truth for ReaPack installs. Last index change 2026-09-13: the bridge package, now listed as Reaper Daemon, caught up from 3.13.0 to 3.20.0.

# HANDOFF - dead-pixel-design

Changes only when a script ships. The index is the source of truth for ReaPack installs.

Reaper Daemon keeps its own index.xml too. Every bridge release there needs a
matching version here, or ReaPack users of this repo fall behind (it drifted
3.13.0 -> 3.20.0 unnoticed until 2026-09-13). Keep the package name
reaper-agent-bridge.lua and the reaper-agent-bridge/ install path so existing
installs upgrade in place.

Status line reconciled 2026-08-30 against git history and this file's own
description of how the repo works. Nothing is outstanding here.
