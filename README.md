# OLauncher

OLauncher is a Windows Minecraft Java launcher focused on stability, clear instance management, modpack support, and a cleaner day-to-day launcher experience.

This repository is the official public distribution channel for the project.

## Status

- Current release line: Beta 0.6
- Platform: Windows desktop
- Distribution model: installer builds and update metadata are published in GitHub Releases
- Auto-update target: this repository is the release source used by the desktop updater

## Downloads

Use the Releases tab of this repository for:

- the Windows installer
- update metadata used by launcher auto-update
- release notes for each published build

## Project Goals

OLauncher is being built to provide a launcher that feels more controlled, maintainable, and focused than the usual overloaded alternatives.

The current direction of the project is centered on:

- isolated instances with clear per-profile settings
- stable vanilla installation and launch flows
- Fabric, Forge, and NeoForge support
- mod and modpack management without cluttering the main experience
- practical diagnostics, logs, backups, and maintenance tools
- a Windows-first desktop experience with automatic updates
- a clean and responsive user interface

## Current Capabilities

The launcher currently includes these major features:

- instance creation, renaming, deletion, cloning, and isolated instance directories
- per-instance launch settings such as Java path, memory allocation, resolution, and extra JVM arguments
- offline play with session-level player identity
- Microsoft account sign-in for premium Minecraft Java access
- vanilla version installation and real launch execution
- runtime selection for Vanilla, Fabric, Forge, and NeoForge
- managed Java runtime download and reuse when a version requires a newer JDK
- official Minecraft announcements inside the launcher
- mod search and installation through Modrinth
- mod enable, disable, and deletion management
- modpack discovery and import from Modrinth, Feed The Beast, and CurseForge
- cape support for offline profiles
- automatic and manual world backups
- crash report reading and diagnostics
- launcher-wide settings, diagnostics, log export, and cache cleanup actions
- live Minecraft process monitoring
- system notifications
- command palette and global keyboard shortcuts
- packaged auto-update through GitHub Releases

## Experience Overview

OLauncher is structured around a few main areas:

- Home for launch activity and operational actions
- Announcements for official Minecraft news
- Instances for profile management and per-instance tuning
- Modpacks for online search and import flows
- Skins for skin and cape management
- System for diagnostics, Java management, launcher settings, and update controls

## Current Scope

The current public release line is focused on Windows desktop support.

The project is designed around:

- a desktop launcher shell
- real installation and launch orchestration
- vanilla and modded instance management
- modpack management and import
- user-facing maintenance and troubleshooting tools
- automatic updates and release distribution

## Roadmap Direction

The near-term direction includes continued work on:

- polishing instance workflows
- expanding mod and modpack quality-of-life features
- improving logs, diagnostics, and recovery flows
- improving world backup and maintenance tools
- tightening update and release delivery
- expanding launcher customization
- continuing general launcher stability and performance improvements

## Official Repository Policy

This public repository is intentionally kept minimal in its branch contents.

What is published here:

- the official project README
- GitHub Releases with installer binaries and update assets

What is not mirrored in the default branch:

- the full desktop source tree
- internal workspace structure
- development tooling and private repository internals

## Legal and Non-Affiliation

OLauncher is an independent project.

- It is not affiliated with, endorsed by, sponsored by, or approved by Mojang Studios or Microsoft.
- Minecraft, Minecraft Java Edition, Mojang, Microsoft, and related names, assets, and brands belong to their respective owners.
- Mods, modpacks, loaders, and third-party platforms remain under their own licenses and terms.

The launcher project is distributed under a custom proprietary license. Redistribution of the original, unmodified source code is permitted, provided that the copyright and license notices are retained. Modification, redistribution of modified versions, and commercial redistribution are not permitted without prior written permission from the copyright holder.
