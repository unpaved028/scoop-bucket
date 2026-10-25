# Scoop bucket for ClipTyper

[![Tests](https://github.com/unpaved028/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/unpaved028/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/unpaved028/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/unpaved028/scoop-bucket/actions/workflows/excavator.yml)

[ClipTyper](https://github.com/unpaved028/ClipTyper) types clipboard text as keystrokes where paste is not available: VM consoles, iLO/iDRAC, KVM-over-IP and remote sessions without a shared clipboard.

## Install

```powershell
scoop bucket add unpaved028 https://github.com/unpaved028/scoop-bucket
scoop install unpaved028/cliptyper
```

This installs the portable build. Your settings (`settings.json`) are kept across updates.

## Update

Exit ClipTyper from the tray first, then:

```powershell
scoop update cliptyper
```

New ClipTyper releases are picked up automatically by the update workflow of this bucket.
