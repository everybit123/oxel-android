# Oxel: mods & add-ons for Minecraft Bedrock (Android)

Oxel is a free Android app for Minecraft Bedrock Edition (MCPE) players. It lets players browse add-ons, maps, skins and texture packs from CurseForge, check whether each one fits their Minecraft version, and import it into Minecraft in one tap.

Status: in development. Coming soon to Google Play.

## How Oxel uses the CurseForge API

- Content is loaded live from `api.curseforge.com` (game: Minecraft Bedrock): search, categories, mod details, files and the official file download URL.
- The app calls the API directly from the device. No proxy, no backend server, no saving or caching of API data.
- Every mod shows the creator's name, links to their CurseForge profile and project page, and an "Open on CurseForge" button.
- Mods with `allowModDistribution = false` are link-only: Oxel opens the CurseForge page and does not download the file.
- Files are never re-hosted. Downloads come from CurseForge through the official download URL.
- Creators can ask to be removed at contact@everybitt.store; we act within 48 hours.

## On the phone

- Detects the installed Minecraft version and checks each downloaded pack against it.
- Explains when a pack needs Experiments, and where it appears in Minecraft after import.
- Checks and repairs common file problems (wrong extension, packs zipped twice) before import.

## Tech

Kotlin, Jetpack Compose, Material 3. Android 7.0+.

## Contact

EveryBit · contact@everybitt.store · https://everybitt.store

NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT. Not an official CurseForge product.

Copyright EveryBit. All rights reserved. The full source code is private and can be shared with the CurseForge team on request.
