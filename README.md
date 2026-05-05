# Rlauncher

Rlauncher is a Windows Minecraft Java launcher focused on stability, clear instance management, modpack support, and a cleaner day-to-day launcher experience.

This repository is the official public distribution channel for the project.

## Status

- Current release line: Beta 0.1
- Platform: Windows desktop
- Distribution model: installer builds and update metadata are published in GitHub Releases
- Auto-update target: this repository is the release source used by the desktop updater

## Downloads

Use the Releases tab of this repository for:

- the Windows installer
- update metadata used by launcher auto-update
- release notes for each published build

## Project Goals

Rlauncher is being built to provide a launcher that feels more controlled and maintainable than the usual overloaded alternatives.

The current direction of the project is centered on:

- isolated instances with clear per-profile settings
- stable vanilla installation and launch flows
- mod loader and modpack support without cluttering the main experience
- practical diagnostics, logs, and maintenance tools
- a Windows-first desktop experience with automatic updates

## Current Capabilities

The launcher already includes these major features:

- instance creation, rename, deletion, and isolated instance directories
- per-instance launch settings such as Java path, memory allocation, resolution, and extra JVM arguments
- offline play with session-level player identity
- Microsoft account sign-in for premium Minecraft Java access
- vanilla version installation and real launch execution
- runtime selection for vanilla, Fabric, Forge, and NeoForge
- managed Java runtime download and reuse when a version needs a newer JDK
- official Minecraft announcements inside the launcher
- modpack discovery and import from Modrinth, Feed The Beast, and CurseForge
- launcher-wide settings, diagnostics, log export, and cache cleanup actions
- packaged auto-update through GitHub Releases

## Experience Overview

Rlauncher is structured around a few main areas:

- Home for launch activity and operational actions
- Announcements for official Minecraft news
- Instances for profile management and per-instance tuning
- Modpacks for online search and import flows
- System for diagnostics, Java management, launcher settings, and update controls

## Current Scope

The current public release line is focused on Windows desktop support.

The project is designed around:

- a desktop launcher shell
- real install and launch orchestration
- modded and vanilla instance management
- user-facing maintenance and troubleshooting tools

## Roadmap Direction

The near-term direction includes continued work on:

- polishing instance workflows
- expanding modpack quality-of-life features
- improving logs, diagnostics, and recovery flows
- tightening update and release delivery
- continuing general launcher stability improvements

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

Rlauncher is an independent project.

- It is not affiliated with, endorsed by, sponsored by, or approved by Mojang Studios or Microsoft.
- Minecraft, Minecraft Java Edition, Mojang, Microsoft, and related names, assets, and brands belong to their respective owners.
- Mods, modpacks, loaders, and third-party platforms remain under their own licenses and terms.

The launcher project itself is distributed under GPL-3.0-only.

## Support

For downloads, use the Releases section of this repository.

If additional public project links are added later, this README should remain the primary public overview of Rlauncher.