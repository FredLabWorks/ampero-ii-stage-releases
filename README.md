# Ampero II Stage — firmware mod (unofficial)

> ⚠️ **Personal project, unofficial, not affiliated with Hotone.** This modified
> firmware is provided with no warranty of any kind. You install it at your
> own risk. Always keep a copy of the official V1.7.0 firmware to go back to.

## The problem

On stage, in **Stomp/Lock** view, bypassed effect blocks are greyed out with
very low contrast — you cannot read a block's content before pressing it.

## What this mod fixes

- **Readability of tiles and inactive labels** (bitmaps + tint)
- **Footswitch LEDs dimmed at rest** (48 % of stock brightness)
- **Bank+/Bank− load patch 1** of the neighbouring bank
- **Wait mode opens on the current bank**
- **The scene is shown in Patch + Lock mode** ("S1"…"S5")

Full detail, checksums and procedure: see the release note attached to each
publication, under the **Releases** tab.

## Installation

1. Download the patcher from this repository's **[Releases](../../releases)** tab
2. Place it in the same folder as the official Hotone V1.7.0 firmware
   (`.bin` or `.zip`, exactly as downloaded)
3. Run the patcher — it checks the firmware's digest before writing anything,
   and refuses if it does not recognise the exact right version
4. Flash the resulting file with the usual Hotone update tool

**If something goes wrong**: unplug the power supply, reflash the official
firmware.

## Status

**Testing phase.** Feedback (bugs, opinions, suggestions) is welcome — through
this repository's issues, or the associated Facebook group.

## Support

This is free and stays free. If it's useful to you and you'd like to chip in:
**[ko-fi.com/fredlabreleases](https://ko-fi.com/fredlabreleases)** — entirely
optional, and it changes nothing about access.

## What is not in this repository

The source code and the reverse-engineering history stay private. This
repository only holds the patcher and its releases — a deliberate choice, not
an oversight.

-- FredLabWorks
