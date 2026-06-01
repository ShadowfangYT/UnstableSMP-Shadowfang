# Feature Plan

## Overview
This document outlines the planned features for **UnstableSMP-Shadowfang**.

The plugin is intended to provide:
- per-player gameplay customization
- configurable behavior through commands and a config file

---

## Planned Features

### Per-player KeepInventory
Allow KeepInventory behavior to be controlled on a per-player basis rather than only globally.

**Notes**
- Should be persistent across restarts
- Should be configurable through commands and config
- Consider per-world and per-group overrides

---

## Configuration

### Goals
- The feature should be togglable
- Runtime command controls should match config options
- Config should support future expansion cleanly

### Recommended Config Areas
- Feature toggles
- Per-world settings
- Per-group settings

---

## Persistence

The following data should persist across restarts:
- per-player KeepInventory state, if implemented that way

---

## Design Notes
- Configuration should stay consistent between command-based control and file-based control
