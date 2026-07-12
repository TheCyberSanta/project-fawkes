# Implementation Guide

| Item | Value |
|------|-------|
| Project | Project Fawkes |
| Subtitle | An iMac Reborn |
| Author | Fred Beebe |
| Version | 1.0 |
| Status | Planning |

---

# Objective

Replace the existing mechanical hard drive with a solid-state drive and deploy Linux Mint as the primary operating system while preserving the original hardware wherever practical.

---

# Scope

## Included

- Remove existing HDD
- Install SATA SSD
- Clean internal components
- Replace PRAM battery
- Inspect cooling system
- Install Linux Mint
- Validate hardware functionality
- Configure engineering workstation

## Excluded

- Logic board repair
- Component-level electronics repair
- CPU replacement
- Display replacement
- Optical drive replacement

---

# Change Summary

The original 500 GB hard drive will be removed and preserved.

A SATA SSD will be installed in its place.

Linux Mint will replace macOS as the primary operating system.

The original hard drive will be retained as a rollback option.

---

# Risk Assessment

| Risk | Impact | Mitigation |
|------|--------|------------|
| Glass damage | High | Use proper suction cups |
| LCD cable damage | High | Photograph cable routing before removal |
| Lost screws | Medium | Label and organize screws |
| Static discharge | High | Ground yourself before handling components |
| SSD failure | Low | Verify SSD health before installation |
| Driver compatibility | Low | Test using Live USB before installation |

---

# Required Tools

## Hardware

- Torx T6
- Torx T8
- Torx T10
- Phillips screwdriver
- Plastic spudger
- Suction cups
- Compressed air
- Isopropyl alcohol (90%+)
- Microfiber cloths
- Thermal paste
- Anti-static wrist strap (recommended)

## Software

- Linux Mint 22.3 Xfce ISO
- Rufus (Windows) or balenaEtcher
- USB flash drive (8 GB or larger)

---

# Implementation Plan

## Phase 1

- Verify hardware
- Photograph system
- Backup existing data (if required)

---

## Phase 2

- Remove front glass
- Remove LCD
- Photograph internals
- Inspect components
- Clean dust

---

## Phase 3

- Remove HDD
- Install SSD
- Replace PRAM battery
- Replace thermal paste
- Reassemble system

---

## Phase 4

- Boot Linux Mint Live USB
- Validate:
  - Display
  - Keyboard
  - Mouse
  - Ethernet
  - Wi-Fi
  - Bluetooth
  - Audio
  - Webcam
  - SuperDrive

---

## Phase 5

- Install Linux Mint
- Apply updates
- Install Broadcom driver (if needed)

---

## Phase 6

- Install engineering software
- Configure Git
- Configure SSH
- Configure VS Code
- Configure PowerShell
- Document installation

---

# Validation Checklist

## Hardware

- Boots successfully
- SSD detected
- Fans operating normally
- Display functioning
- SuperDrive operational

## Software

- Linux boots successfully
- Network connectivity verified
- Wi-Fi operational
- Audio operational
- Bluetooth operational
- Webcam operational

---

# Rollback Plan

If implementation fails:

1. Remove SSD.
2. Reinstall original HDD.
3. Verify original macOS installation.
4. Review implementation notes.
5. Correct issue before attempting deployment again.

---

# Success Criteria

The implementation is complete when:

- Linux Mint boots reliably.
- All major hardware functions.
- SSD performance is verified.
- Engineering software is installed.
- Documentation is complete.

---

## Revision History

| Version | Date | Author | Notes |
|---------|------|--------|-------|
| 1.0 | July 2026 | Fred Beebe | Initial implementation guide |
